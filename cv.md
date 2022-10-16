# Łukasz Szynal

## 👋 Introduction

<!--https://user-images.githubusercontent.com/5713670/87202985-820dcb80-c2b6-11ea-9f56-7ec461c497c3.gif-->

![Status](https://img.shields.io/badge/status-up-brightgreen)
![Gender](https://img.shields.io/badge/gender-%F0%9F%A4%B5-lightgrey)
![CodeWars](https://www.codewars.com/users/lukaszynal/badges/micro)

Hi, I'm **Łukasz Szynal**. 
My advantage is reliability and ease in establishing contacts with people. I am a stress-resistant person and I can work under time pressure. I am characterized by punctuality, consistency in action and responsibility in approaching my work. I'm able to work in a group as well as perform individual tasks. I am an ambitious person who's looking for a new challenges. During my professional experience, I have learned to be responsible, reliabile and patient. 

## 🏫 Education

**Akademia Humanistyczno-Ekonomiczna w Łodzi**  
Mar 2021 - Current

## 🎓 Courses

**.NET Development Online Training Program** *Epam*<br>
Jul 2022

**Google Cloud Skill Badges (12 badges)** *Google*<br>
Sep 2021

**PCAP - Programming Essentials In Python** *Cisco Networking Academy*<br>
Aug 2021

**PCAP - Programming Essentials In C++** *Cisco Networking Academy*<br>
Jul 2021

## 💡 Skills

![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![.Net](https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![Html5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Css3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)

![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![Microsoft Office](https://img.shields.io/badge/Microsoft_Office-D83B01?style=for-the-badge&logo=microsoft-office&logoColor=white)

## 📝 Code Example

```cs
using System;
using System.Collections.Generic;
using System.Linq;

public class Kata
{
  public static string High(string s)
  {
    var words = s.Split(' ');
    var wordsScore = new List<int>(words.Length);
    foreach (var word in words)
    {
      var wordScore = 0;
      foreach (var ch in word)
      {
        wordScore += Convert.ToInt32(ch) - 96;
      }
      wordsScore.Add(wordScore);
    }
    var indexOfMax = wordsScore.IndexOf(wordsScore.Max());
    return words[indexOfMax];
  }
}
```

## 💬 Languages

**Polish** - Native language<br>
**English** - Intermediate level<br>
**French** - Beginner level

## 📫 Contact Me on Social Media

<a href="https://www.facebook.com/lukaszynal/"><img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white"></a>
<a href="https://www.linkedin.com/in/lukaszynal/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
<a href="mailto:lukaszynal@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
<a href="https://github.com/lukaszynal/"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>