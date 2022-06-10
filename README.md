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


<details><summary><i><h2>Works</h2></i></summary>
<table>
    <tr>
    <th>Work</th>
    <th>Mine/Coop</th>
    <th>Contribution*</th>
    </tr>
    <tr> <td>super_bot</td> <td>Coop</td> <td>Building (from setup.py), documentation</td> </tr>
    </table>
    <i><p>*filled in if "Coop"</p></i>
</details>

    
## _My contacts_
<div align="center"><p>
    <a href="https://vk.com/korolandshutforever"><img src="https://ia.wampi.ru/2022/06/10/QEvZrVy0.png" alt="VK"></a>
    <a href="https://discord.com/"><img src="https://github.com/AlexKnyaZz/AlexKnyaZz/blob/main/forContacts/Discord-Logo-White.png?raw=true" alt="Discord"></a>
    <a href="https://steamcommunity.com/id/AlexKnyaZz/"><img src="https://ie.wampi.ru/2022/06/10/toppng.com-steam-logo-png-transparent-894x894.png" alt="Steam"></a>
</p></div>

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
