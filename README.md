![](https://skillicons.dev/icons?i=apple,neovim,cpp,java,gradle,mysql)

# Hi, I'm Harrison

```cpp
#include <iostream>
#include <string>

class Profile {
private:
    std::string name;
    std::string discipline;
    std::string university;

public:
    Profile(const std::string& n = "Harrison",
            const std::string& d = "Software Engineering",
            const std::string& u = "RMIT")
        : name(n), discipline(d), university(u) {}

    friend std::ostream& operator<<(std::ostream& os, const Profile& p) {
        os << "Hi, I'm " << p.name
           << ". I'm currently studying " << p.discipline
           << " at " << p.university << ".";
        return os;
    }
};

int main() {
    Profile me;
    std::cout << me << std::endl;
    return 0;
}
```

```text
➜  harrisonablack git:(main) g++ Profile.cpp -o Profile
➜  harrisonablack git:(main) ./Profile

Hi, I'm Harrison. I'm currently studying Software Engineering at RMIT.
```
