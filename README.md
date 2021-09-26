
#include <iostream>
#include <string>

int main()
{
    int sides;
    std::cout << "Please enter number of sides: ";
    std::cin >> sides;

    if (sides == 3)
    {
        std::cout << "Triangle has " << sides << " sides";
    }
    else if (sides == 4)
    {
        std::cout << "Square has " << sides << " sides";
    }
    else if (sides == 5)
    {
        std::cout << "Pentagon has " << sides << " sides";
    }
    else if (sides == 6)
    {
        std::cout << "Hexagon has " << sides << " sides";
    }
    else if (sides == 7)
    {
        std::cout << "Heptagon has " << sides << " sides";
    }
    else if (sides == 8)
    {
        std::cout << "Octagon has " << sides << " sides";
    }
    else if (sides == 9)
    {
        std::cout << "Nonagon has " << sides << " sides";
    }
    else if (sides == 10)
    {
        std::cout << "Decagon has " << sides << " sides";
    }
    else
    {
        std::cout << "Not a valid input.";

    }
    return 0;
}
