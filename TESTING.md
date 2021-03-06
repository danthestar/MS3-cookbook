# **MMM Full Testing** 

![](mdimg/2.jpg) 

###  *The live Website can be found [here.](https://flask-task-manager-cookbook.herokuapp.com/login)*
---
---
## **Testing Tree**
---
---

- [Testing](#testing)
    - [HTML](#html)
    - [CSS](#css)
    - [JS](#js)
    - [Python](#python)
    - [Compatibility testing](#compatibility-testing)
       - [Mozilla Firefox](#mozilla-firefox)
       - [Opera](#opera)
       - [Google Chrome](#google-chrome)
       - [Microsoft Edge](#microsoft-edge)
- [General testing](#general-testing)
  - [Navigation](#navigation)
  - [Page Load](#page-load)


### **[Back to previous page](README.md)**
---
---
### **Testing**
---
---

### **HTML**
---
HTML Code runn trough [W3C HTML Validator](https://validator.w3.org/#validate_by_input), PASS obtaine after fixing error.

**Error;** this is a warning not an error, the reason it shows is because if no message is rendered, then the heading is not displayed. 
And all the other examples that are listed below will have the same warning (so I will not include this text on each of them)

**Home page - befor log in**
 ![](mdimg/1hpbeforelogin.jpg)

**By** trying to Consider using h2-h6 elements i was getting same results, same as completle removing "section" part, or adding h-element to section, or adding section to h-element.

**'Username already exists' message**
 ![](mdimg/1usernameArdExist.jpg)

**Log In page** 
 ![](mdimg/1login.jpg)

**Home page** 
 ![](mdimg/1homepage.jpg)

**New Task page** 
 ![](mdimg/1addtask.jpg) 

**Manage Categories page** 
 ![](mdimg/1getcategories.jpg)

**Log Out page** 
 ![](mdimg/1logout.jpg)

[Back to Testing Tree](#testing-tree)

### **CSS**
---
Css Code runn trough [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input+with_options), PASS obtaine after fixing error.

**Error**
 ![](mdimg/w3c-error.jpg)

**Pass**  by fixing missing px on 2px: line
  ![](mdimg/wc3-pass.jpg)

 [Back to Testing Tree](#testing-tree)

 ### **JS**
---
JS Code runn trough [jshint Validator](https://jshint.com/), PASS obtaine after fixing error.

**Error**
 ![](mdimg/js1.jpg)

**Better** by changing some parameters
  ![](mdimg/js2.jpg)

[Back to Testing Tree](#testing-tree)

### **Python**
---
Python Code runn trough [PEP8 Validator](http://pep8online.com/), PASS obtaine after fixing error.

**Error**
 ![](mdimg/pyton1.jpg)

**Pass**  by fixing blank lines, and removing back space on the end of the lines.
![](mdimg/pyton2.jpg)
[Back to Testing Tree](#testing-tree)

---
---
### **Compatibility testing**
---
---

### **Mozilla Firefox**
    Works as intended on Mozilla Firefox in big screen, tablet screen and phone screen.
    No misplacing of elements or overlapping them during testing in responsive mode 
    "Hamburger" menu is working properly in responsive mode accordingly to the intend. 
**Medium size screen**
![](mdimg/mz1.png)

**Big size screen**
![](mdimg/mz2.png)

**Smartphone size screen**
![](mdimg/mz3.png)

[Back to Testing Tree](#testing-tree)

### **Opera**
    Works as intended on Opera in big screen, tablet screen and phone screen.
    No misplacing of elements or overlapping them during testing in responsive mode 
    "Hamburger" menu is working properly in responsive mode accordingly to the intend.

**Big size screen**
![](mdimg/op1.png)

**Medium size screen**
![](mdimg/op2.png)

**Smartphone size screen**
![](mdimg/op3.png)

[Back to Testing Tree](#testing-tree)

### **Google Chrome**
    Works as intended on Google Chrome in big screen, tablet screen and phone screen.
    No misplacing of elements or overlapping them during testing in responsive mode 
    "Hamburger" menu is working properly in responsive mode accordingly to the intend.
**Big size screen**
![](mdimg/gc1.png)

**Medium size screen**
![](mdimg/gc2.png)

**Smartphone size screen**
![](mdimg/gc3.png)

[Back to Testing Tree](#testing-tree)

### **Microsoft Edge**
    Works as intended on Microsoft Edge in big screen, tablet screen and phone screen.
    No misplacing of elements or overlapping them during testing in responsive mode 
    "Hamburger" menu is working properly in responsive mode accordingly to the intend.
**Big size screen**
![](mdimg/me1.png)

**Medium size screen**
![](mdimg/me2.png)

**Smartphone size screen**
![](mdimg/me3.png)

[Back to Testing Tree](#testing-tree)

---
---
### **General testing**
---
---

### **Navigation**
---
*Navigation part of testing will be concerned about all pages and how are they working.
On opening application we have Working Home, Log In and Register option is in the header. The addition is searching tab, and reset of the same search tab.*


    All pages are working accordingly to the blueprint. 
    As Admin user on all platforms (Edge, Google Chrome, Firefox and Opera) there is no issues. 
    Same goes for Users, everything is working as planned.
    Home / Profile / New Taks / Manage Categories

#### **Page Load**
---
Log In button, Sign Out or Register options are working with no issues.

    By clicking on Log In button we will be transfred to Log In / Register options.
    On logging in we will be automatically moved to a Profile page, from where we can navigate to:

**Home** 

    - we have visual data of all tasks made by all family members
    
**Profile** 
    
    - still stays the profile

**New Task** 
     
    - opens new Html with functions of creating  a task: having options as Category, Task Name, Task Description, Date and Urgent slider (in case it important tasks and it can not be passed).

**Manage Categories**
    
    - option is available only for Admin users, since he is the one that will be managing all the needs.
    It allows Admin users to create new categories for all future needs of the Family. 

**Log Out**

     - on log out/in we will be automatically moved to a Log In/Register page.

### **[Back to previous page](README.md)**

[Back to Testing Tree](#testing-tree)

### *Daniel Matasic*

