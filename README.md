

#
<p align=center>
<a href="">
</a>
  </p>
<p align=center>
 <img src="https://komarev.com/ghpvc/?username=beshizumoto&style=for-the-badge&logo=Streamlit&color=blueviolet&logo=Bookmeter">
  </p>

```cpp
#!/usr/bin/g++
class BESHIZUMOTO {
public:
    BESHIZUMOTO() :
        name("BESHIZUMOTO"),
        role("C++ Dev"),
        languages({"C++"}),
        languages_learning({"ASM", "PYTHON"}),
        languages_spoken({"fr_FR", "en_US", "ar_AR"})
    {}

    void say_hi() {
        std::cout << "Hope you find some of my work interesting." << std::endl;
    }

private:
    std::string name;
    std::string role;
    std::vector<std::string> languages;
    std::vector<std::string> languages_learning;
    std::vector<std::string> languages_spoken;
};
int main() {
    BESHIZUMOTO me;
    me.say_hi();

    return 0;
}
```



