# 👋 Hi, I’m Esmaeil Alabdullah  

```cpp
#include <iostream>
#include <vector>
#include <string>

class Developer {
public:
    std::string name = "Esmaeil Alabdullah";
    std::string role = "Passionate Coder 💻";
    std::vector<std::string> interests = {
        "Coding", "Open Source", "Problem Solving", "Learning New Tech"
    };
    std::string current_focus = "Building cool projects & leveling up 🚀";
    std::string fun_fact = "I debug with coffee ☕";

    void say_hi() const {
        std::cout << "Thanks for stopping by! Let's build something amazing together!" << std::endl;
    }
};

int main() {
    Developer me;
    me.say_hi();
    return 0;
}
