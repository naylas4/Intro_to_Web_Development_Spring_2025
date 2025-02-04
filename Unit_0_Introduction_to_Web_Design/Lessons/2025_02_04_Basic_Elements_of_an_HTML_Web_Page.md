# Introduction to Web Development
Tuesday, February 4th 2025

## Basic Elements of an HTML Web Page

**AIM:** What are the basic elements of an HTML web page, and what purpose does each element serve?

**OUTCOME ALIGNMENT:**
<br><ins>IEC.TQS11T.2</ins>: Use HTML to create a website.

**SUCCESS CRITERIA:**
- [ ] I can describe the basic elements of an HTML webpage, and what purpose each element serves.
- [ ] I can construct the basic layout of an HTML webpage.

|DO NOW|
|---|
|Name something you are passionate about.|

**AGENDA:**

1. Personal Passion Shareout
2. Basic Elements of an HTML Webpage
    * `<!DOCTYPE html>`
    * `<HTML></HTML>`
    * `<HEAD></HEAD>`
    * `<BODY></BODY>`
    * `<TITLE></TITLE>`
3. Start Tags and End Tags
4. Nesting
5. Build a Paper Webpage

**ASSIGNMENT:** 
<br>[Unit 0 Assignment 03 - My First Webpage, Version 0](https://github.com/MrJSwotinsky/Intro_to_Web_Development_Spring_2025/blob/main/Unit_0_Introduction_to_Web_Design/Assignments/03_My_First_Webpage_v0.md)

## Resources
**Notes**
|Notes||
|---|---|
|**Tags**|All HTML elements are enclosed in tags.<br><br>For example, the title of a webpage is enclosed in the tags, `<title>` and `</title>`.<br><br>The first tag, known as the **start tag**, has no backslash.<br><br>The second tag, known as the **end tag**, begins with a backslash.<br><br>**Example/**<br><br>`<title>Page Title</title>`<br><br>**Start Tag:** `<title>`<br>**End Tag:** `</title>`|
|**Nesting**|HTML elements can be **nested** inside of each other.<br><br>For major elements of a webpage, indentation should be used for nesting to make code more readable.|

**Nesting Example:**
In the example below, the `<HEAD></HEAD>` element is nested inside the `<HTML></HTML>` element using indentation.

```HTML
<HTML>
  <HEAD>
  </HEAD>
<HTML>
```

**Code Reference**

|Code|Description|
|---|---|
|`<!DOCTYPE html>`|`<!DOCTYPE html>` should be included at the top of every HTML file.<br><br>`<!DOCTYPE html>` declares the file as an HTML file so that the browser knows it is HTML.|
|`<HTML></HTML>`|serves as the main container for all HTML.|
|`<HEAD></HEAD>`|contains meta information.<br><br>For example, `<TITLE></TITLE>` is contained within `<HEAD></HEAD>`.|
|`<BODY></BODY>`|contains the content to be displayed in the browser.|
|`<TITLE></TITLE>`|contains the title of the webpage.|
