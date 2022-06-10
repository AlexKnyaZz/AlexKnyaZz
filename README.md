# Hello.cpp
```cpp
#include <iostream>
#include <windows.h>
using namespace std;

void setColorGreen(HANDLE h) {
    SetConsoleTextAttribute(h, FOREGROUND_GREEN);
}
void setColorStandart(HANDLE h) {
    SetConsoleTextAttribute(h, FOREGROUND_INTENSITY);
}

int main(){
  HANDLE handle = GetStdHandle(STD_OUTPUT_HANDLE);
  setColorGreen(handle);
  cout << "Greetings. Have a nice day!" << endl;
  setColorStandart(handle);
  return 0;
 }
```

<details><summary><i><h2>About me</h2></i></summary>
<li>I am a student from Russia, studying at the Department of Corporate Information Systems Development</li>
<li>Like to play games and develop them</li>
</details>
    
## _My contacts_
[![VK](https://ia.wampi.ru/2022/06/10/QEvZrVy0.png)](https://vk.com/korolandshutforever)
<!--
**AlexKnyaZz/AlexKnyaZz** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
