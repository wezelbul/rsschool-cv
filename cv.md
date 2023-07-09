# CV Dmitrii Chesnokov

## About me

I have been successfully engaged in UI and API testing of web applications on projects of varying complexity for 2
years. Confident Linux user (can install and configure Arch distribution from scratch), write bash scripts, administer a
mini-server for personal use. Of course, I know how to exit vim :) I'm interested in low-level programming (
assembly/disassembly, bytecode, interaction of components at the hardware level). My hobbies are hiking, board games,
science fiction, puzzles. Open to relocate.

## Contacts

- [Igalo, Montenegro](https://www.google.com/maps/place/Igalo,+Montenegro/@42.4589467,18.5076016,16z)
- [d.chesnokov.01@yandex.ru](mailto:d.chesnokov.01@yandex.ru)
- [+7 917 984 82 15](tel:+79179848215)
- [@DmitriiChes](https://t.me/DmitriiChes)
- [LinkedIn](https://www.linkedin.com/in/dmitrii-c-26421b252/)

## Education

- Saratov State University named after N.G.Chernyshevsky
    - Institute of Chemistry
    - 2017 - 2019
    - Organic Chemistry, Master's degree

## Courses

- A1QA Test automation Training Center - Test Developer
- RS School - JS / Front-end. Stage 0 (RU)
- [Coursera - Kotlin for Java Developers](https://coursera.org/share/27089f081c94b0c105ae5b9dedafcb68)

## Skills:

<h4>Testing:</h4>
<p align="left">
<a href="https://junit.org/junit5/">
<img src="https://raw.githubusercontent.com/wezelbul/wezelbul/main/icons/tools/06_JUnit5.svg" alt="JUnit Jupiter" title="JUnit Jupiter" width="40" height="40"/> </a>
<a href="https://www.selenium.dev" target="_blank" rel="noreferrer">
<img src="https://raw.githubusercontent.com/wezelbul/wezelbul/main/icons/tools/07_Selenium.svg" alt="Selenium" title="Selenium" width="40" height="40"/> </a>
<a href="https://selenide.org" target="_blank" rel="noreferrer">
<img src="https://raw.githubusercontent.com/wezelbul/wezelbul/main/icons/tools/10_Selenide.svg" alt="Selenide" title="Selenide" width="40" height="40"/> </a>
<a href="https://rest-assured.io" target="_blank" rel="noreferrer">
<img src="https://raw.githubusercontent.com/wezelbul/wezelbul/main/icons/tools/11_Rest_Assured.svg" alt="Rest Assured" title="Rest Assured" width="40" height="40"/> </a>
<a href="https://docs.cucumber.io" target="_blank" rel="noreferrer">
<img src="https://raw.githubusercontent.com/wezelbul/wezelbul/main/icons/tools/12_Cucumber.svg" alt="Cucumber" title="Cucumber" width="40" height="40"/> </a>
  </p>

<h4>Develop:<h4>
  <p align="left">
    <a href="https://git-scm.com" target="_blank" rel="noreferrer"> 
      <img src="https://raw.githubusercontent.com/wezelbul/wezelbul/main/icons/tools/04_Git.svg" alt="Git" title="Git" width="40" height="40"/> </a> 
   <a href="https://www.jetbrains.com/idea/" target="_blank" rel="noreferrer"> 
      <img src="https://raw.githubusercontent.com/wezelbul/wezelbul/main/icons/tools/05_IntelliJ_IDEA.svg" alt="Intellij IDEA" title="Intellij IDEA" width="40" height="40"/> </a> 
    <a href="https://spring.io" target="_blank" rel="noreferrer"> 
      <img src="https://raw.githubusercontent.com/wezelbul/wezelbul/main/icons/tools/08_Spring.svg" alt="Spring" title="Spring" width="40" height="40"/> </a> 
    <a href="https://maven.apache.org" target="_blank" rel="noreferrer"> 
      <img src="https://raw.githubusercontent.com/wezelbul/wezelbul/main/icons/tools/09_Maven.svg" alt="Maven" title="Maven" width="40" height="40"/> </a> 
    <a href="https://www.mysql.com" target="_blank" rel="noreferrer"> 
      <img src="https://raw.githubusercontent.com/wezelbul/wezelbul/main/icons/tools/13_MySQL.svg" alt="MySQL" title="MySQL" width="40" height="40"/> </a> 
  </p>

<h4>Tools:</h4>
  <p align="left">
    <a href="https://www.microsoft.com/en-us/windows" target="_blank" rel="noreferrer"> 
      <img src="https://raw.githubusercontent.com/wezelbul/wezelbul/main/icons/tools/01_Windows.svg" alt="Windows" title="Windows" width="40" height="40"/> </a>
    <a href="https://getfedora.org" target="_blank" rel="noreferrer"> 
      <img src="https://raw.githubusercontent.com/wezelbul/wezelbul/main/icons/tools/02_Fedora.svg" alt="Fedora Linux" title="Fedora Linux" width="40" height="40"/> </a>
    <a href="https://github.com" target="_blank" rel="noreferrer"> 
      <img src="https://raw.githubusercontent.com/wezelbul/wezelbul/main/icons/tools/14_GitHub.svg" alt="GitHub" title="GitHub" width="40" height="40"/> </a>
    <a href="https://www.postman.com" target="_blank" rel="noreferrer"> 
      <img src="https://raw.githubusercontent.com/wezelbul/wezelbul/main/icons/tools/15_Postman.svg" alt="Postman" title="Postman" width="40" height="40"/> </a>
    <a href="https://insomnia.rest" target="_blank" rel="noreferrer"> 
      <img src="https://raw.githubusercontent.com/wezelbul/wezelbul/main/icons/tools/16_Insomnia.svg" alt="Insomnia" title="Insomnia" width="40" height="40"/> </a>
  </p>

## Code example

```java
public class DigPow {
    public static long digPow(int n, int p) {
        int sum = 0;
        int pow = p;
        for (char ch : String.valueOf(n).toCharArray()) {
            sum += Math.pow(Character.getNumericValue(ch), pow);
            pow += 1;
        }
        if (sum % n == 0) {
            return (long) sum / n;
        } else {
            return -1;
        }
    }
}
```
## Projects

- [Kanban board (backend, Java)](https://github.com/wezelbul/java-kanban)
- [Service for movie lovers (backend, Java)](https://github.com/wezelbul/java-filmorate)

## Languages

- Russian - native
- English - B1