![userpic](https://fastly.4sqi.net/img/user/260x260/ASDNPYERKO3QAIS0.jpg)
# **Anton Blagoveshchenskiy, JS Student, QA Junior, former editor-in-chief**

**email:** <zzzebra@gmail.com>

**Github:** <https://github.com/mmoresun>
 
**Telegram:** <https://t.me/zzebra>

**Discord:** mmoresun#0451

**Phone number:** +90 551 099 3779

**Location:** Antalya, Turkey

Hi, I'm Anton. I was born in Moscow at 1980, studied at the Moscow Institute of Electronic Technology (MIET), have an engineer degree in technical sciences (radio electronics). In 2021, I moved from Moscow to Kyiv, and soon got married. For a long time I worked as a technical journalist, but I decided to find a job in IT (QA, programming). 

## **Work Experience:**

### **News Editor - Ferra.ru (Rambler Internet Holding)**

_Moscow (remotely from Kyiv) - 2002 to 2005_

**Duties:**

- writing high-tech news; 
- writing device reviews; 
- managing a team of authors;
- creating videos.

### **News Editor - Webplanet.ru**

- writing high-tech news; 
- writing device reviews; 
- managing a team of authors.

_Moscow (remotely from Kyiv)_

### **Editor-in-chief - RG Digital (digital.rg.ru)**

_Moscow (remotely from Kyiv) - November 2008 to March 2022_

**Duties:**

- writing high-tech news; 
- writing device reviews; 
- managing a team of authors (5 people) - learning, text editing;
- interaction with PR, SMM (Apple, Sony, Xiaomi, Panasonic, Microsoft, realme and more);
- social media advertising; 
- making a fact-checking;
- writing expert columns;
- creating social media content (Instagram, Facebook).

### **QA Volunteer**

_(August 2020 to September 2021, remotely from Kyiv):_

- **Travelrank.me** site
- **Sports.ru** site
- **Lose It!** mobile health app 

**Duties**

- drawing up a mindmap of the project;
- test analysis making;
- test design creation;
- test cases making;
- writing checklists taking using testing specifics;
- bug tracking (Redmine, Jira, Bugzilla, Mantis, Testlink);
- functional testing (usability, search performance, interactive elements operation, localization);
- non-functional testing;
- existing project testing;
- web services testing;
- mobile apps testing; 
- writing tests according to the terms of reference;
- test documentation, test plans creation;
- testing without an interface (REST API, SOAP API).

## **Education**

Engineer in Microdevices and Technical Cybernetics, Moscow Institute of Electronic Engineering
_(September 1997 to May 2002)_

## **Skills**

- Quality Assurance (manual)
- HTML 
- CSS
- text works (writing, editing - excellent level)
- fast learner

## **Languages:** 
- Russian (fluent)
- Ukrainian (expert)
- English (Intermediate)

## **Certifications and Licenses**:

- Code Academy JavaScript Courses (February 2022 - March 2022)
- Software-testing.ru QA Courses (June 2020 - September 2020)

## **Code example 1 (uppercasing first letters of the string):** 
```
String.prototype.toJadenCase = function () {

const myString = 'i am the best of the best'; // our original myString

const splittedString = myString.split(" "); // making an array "splittedString" from "myString" with " " separator

for (let i = 0; i < splittedString.length; i++) {
  splittedString[i] = splittedString[i][0].toUpperCase() + splittedString[i].slice(1);
 }

// going thru "splittedString" array:
// - finding first (0th) letter at every cell, capitalize it and adding to "splittedString" array, the same cell 
// - adding to capitalized letters rest of cell content (from place 1)

return myStringUp = splittedString.join(" ");

// join array "splittedString" to myString

}
```


## Code example 2 (function receives one side of the DNA and returns the other complementary side):

```
function DNAStrand(dna){
  
    const newDNA = dna.split(''); // crecating splitted array from entered string

  let resultDNA = ''; // creating empty variable to saving the result

    for (i = 0; i < dna.length; i++) {

      if (newDNA[i] === 'A') {
        resultDNA = resultDNA + 'T';
      }
      else if (newDNA[i] === 'T') {
        resultDNA = resultDNA + 'A';
      }

      else if (newDNA[i] === 'C') {
        resultDNA = resultDNA + 'G';
      }

      else if (newDNA[i] === 'G') {
        resultDNA = resultDNA + 'C';
      }
      else {resultDNA = resultDNA;}

    }
    
  // going thru every cell of the array. when found "A", add "T" to resultDNA, when found "C", add "G" to resultDNA, etc.
  
  return resultDNA; // return result 
  
}
```
