<h1 align="center">
  <br>
 <img src="https://github.com/prokittikun/issue/assets/76927239/2f59eb0b-d725-4d2f-b325-51c885a22479" alt="Markdownify" width="200">
  <br>
  <span style="color: #C73618;">CS211-611 Project Event Hub</span>
  <br>
</h1>


<p style="text-align: center; ">
    <b>โปรเจกต์นี้เป็นส่วนหนึ่งของ รายวิชา 01418211 - การสร้างซอฟต์แวร์ (Software Construction)</b> <br>
    <b>ภาคการศึกษาที่ 1 ปีการศึกษา 2566</b> <br>
</p>


<p align="center">
<a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a>
&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a>
&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a>
&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://www.figma.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/> </a> 
&nbsp;&nbsp;&nbsp;&nbsp;
</p>

<p align="center">
  <a href="#introduction">Introduction</a> •
  <a href="#download">Download</a> •
  <a href="#installation">Installation</a> •
  <a href="#usage">Usage/Examples</a> •
  <a href="#account/tests">Account Tests</a> •
  <a href="#project-structure">Project Structure</a>
</p>

## Introduction[![](https://raw.githubusercontent.com/aregtech/areg-sdk/master/docs/img/pin.svg)](#introduction)

<div style="display: flex; gap: 5px; margin-bottom: 10px">
<img src="https://github.com/prokittikun/issue/assets/76927239/83e78f1e-19c9-44b0-b589-a5ae4620b21a" width="350">
<img src="https://github.com/prokittikun/issue/assets/76927239/e10b3351-029a-47f0-9828-a68ce41647d1" width="350">
</div>

**Event Hub** (*อิเวนต์ ฮับ*) เป็นโปรแกรมที่ถูกพัฒนาขึ้นเพื่อให้ความสะดวกในการจัดการกับกิจกรรมและอิเวนต์ต่าง ๆ ในที่เดียว โดยเราได้รวบรวมฟีเจอร์ต่าง ๆ เพื่อให้ผู้ใช้สามารถสร้างและจัดการกับอิเวนต์ได้อย่างมีประสิทธิภาพและง่ายดายมากยิ่งขึ้น ภายใน "Event Hub" มีฟีเจอร์หลากหลายที่สำคัญ เช่น ระบบสมาชิก, การสร้างอิเวนต์, การเข้าร่วมอิเวนต์, การสร้างทีมภายใต้อิเวนต์, การสร้างกำหนดการต่าง ๆ และอื่น ๆ อีกมากมายภายในระบบ



## Download[![](https://raw.githubusercontent.com/aregtech/areg-sdk/master/docs/img/pin.svg)](#introduction)
#### jar file for Windows and MacOs
- Download <b>Event-Hub.zip</b> from [Release tags](https://github.com/CS211-661/cs211-661-project-phuea-khrai-party/tags) or click the link [Click](https://github.com/CS211-661/cs211-661-project-phuea-khrai-party/archive/refs/tags/3.0.0.zip)

## Installation[![](https://raw.githubusercontent.com/aregtech/areg-sdk/master/docs/img/pin.svg)](#introduction)
#### 1. Extract Zip File
![install1](https://github.com/prokittikun/issue/assets/76927239/1e8498e7-2eb3-4163-9db7-b3515069d36c)

#### 2. Select Unzip folder
![install2](https://github.com/prokittikun/issue/assets/76927239/fb603a3c-cba3-46b9-85e6-3df31043da8e)

#### 3. Select Event-Hub-jar-file
![install3](https://github.com/prokittikun/issue/assets/76927239/7e900e7e-c303-4740-8920-743473cf3b56)

#### 4. Double Click Event-Hub.jar
![install4](https://github.com/prokittikun/issue/assets/76927239/212188d3-428a-4c49-85bf-0b710c6862c5)
### Or
```bash
# ~\Event-Hub-jar-file
$ java -jar Event-Hub.jar
```
### 5. Congratulations, you have succeeded. 🎉
![install5](https://github.com/prokittikun/issue/assets/76927239/791f7ad0-b4a4-4edd-aba0-a91e5b53e29a)

## Usage[![](https://raw.githubusercontent.com/aregtech/areg-sdk/master/docs/img/pin.svg)](#introduction)

This is User Manual [Guide](https://github.com/CS211-661/cs211-661-project-phuea-khrai-party/blob/develop/data/user-guide.pdf) or click according to the picture
![example](https://github.com/prokittikun/issue/assets/76927239/7d495146-e1bb-4dfb-9322-c8bfafeccf29)


## Account Tests[![](https://raw.githubusercontent.com/aregtech/areg-sdk/master/docs/img/pin.svg)](#introduction)

| username                  | password | role  |
|--------------------------|-------|-------|
| admin | 1234 | admin |
| Yada       | 2609 | user  |
| Jimin  | 1111      | user  |
| star     | 2468 | user |
| kura  |9999| staff |

## Project Structure
<pre>
📦cs211-661-project-phuea-khrai-party
┣ 📂data
┃ ┣ 📂event
┃ ┃ ┣ 📜activity.csv
┃ ┃ ┣ 📜answer.csv
┃ ┃ ┣ 📜event.csv
┃ ┃ ┣ 📜joinEvent.csv
┃ ┃ ┗ 📜question.csv
┃ ┣ 📂image
┃ ┃ ┣ 📂avatar
┃ ┃ ┗ 📂event
┃ ┣ 📂team
┃ ┃ ┣ 📜activity.csv
┃ ┃ ┣ 📜chat.csv
┃ ┃ ┣ 📜team.csv
┃ ┃ ┗ 📜teamMember.csv
┃ ┣ 📜user-guide.pdf
┃ ┗ 📜user.csv
┣ 📂src
┃ ┣ 📂main
┃ ┃ ┣ 📂java
┃ ┃ ┃ ┣ 📂cs211
┃ ┃ ┃ ┃ ┗ 📂project
┃ ┃ ┃ ┃ ┃ ┣ 📂controllers
┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂components
┃ ┃ ┃ ┃ ┃ ┣ 📂cs211661project
┃ ┃ ┃ ┃ ┃ ┣ 📂models
┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂collections
┃ ┃ ┃ ┃ ┃ ┣ 📂services
┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂alert
┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂comparator
┃ ┃ ┃ ┃ ┃ ┗ 📜Main.java
┃ ┃ ┃ ┗ 📜module-info.java
┃ ┃ ┗ 📂resources
┃ ┃ ┃ ┗ 📂cs211
┃ ┃ ┃ ┃ ┗ 📂project
┃ ┃ ┃ ┃ ┃ ┗ 📂views
┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂assets
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂admin
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂background
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂banner
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂fonts
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂Icons
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂logo
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂professor
┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂components
┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂style
┣ 📜.gitignore
┣ 📜mvnw
┣ 📜mvnw.cmd
┣ 📜pom.xml
┗ 📜README.md
</pre>
