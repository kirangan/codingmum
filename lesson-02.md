# CODING MUM

| [Home][0] | [Lesson 01][1] | [Lesson 02][2] | [Lesson 03][3] | [Lesson 04][4] | [Lesson 05][5] | [Lesson 06][6] | [Lesson 07][7] | [Presentation][8] |
|:---------:|:--------------:|:--------------:|:--------------:|:--------------:|:--------------:|:--------------------:|:--------------:|:-----------------:|

---

### LESSON 02: PENGENALAN HTML DAN CSS

---

### Objectives
1. Peserta mampu membuat **HTML** dan **CSS** dasar dengan text editor.
2. Peserta mengerti pemisahan **HTML sebagai struktur** dan **CSS sebagai presentasi** dalam website.

---

### Software yang harus dibutuhkan
  * [Sublime](https://www.sublimetext.com/3)
  * [Google Chrome](https://support.google.com/chrome/answer/95346?co=GENIE.Platform%3DDesktop&hl=id)

---

### Material

#### 1. HTML
* Heading
  ```html
  <h1>Heading 1</h1>
  <h2>Heading 2</h2>
  <h3>Heading 3</h3>
  <h4>Heading 4</h4>
  <h5>Heading 5</h5>
  <h6>Heading 6</h6>
  ```
* Anchor / Link
  ```html
  <a href="http://google.com">Ini text link menuju Google</a>
  ```
  ```html
  <a href="about-us.html">Ini text link menuju file about-us.html</a>
  ```
* Paragraph
  ```html
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
  ```
* List
  ```html
  <ul>
    <li>Unordered list 1</li>
    <li>Unordered list 2</li>
  </ul>
  ```
  ```html
  <ol>
    <li>Ordered list 1</li>
    <li>Ordered list 2</li>
  </ol>
  ```
* Image
  ```html
  <img src="nama_folder/nama_file.jpg">
  <img src="nama_folder/nama_file.png">
  <img src="nama_folder/nama_file.gif">
  ```
* Video
  ```html
  <iframe width="560" height="315" src="https://www.youtube.com/embed/-We_dYsLTtY" frameborder="0" allowfullscreen></iframe>
  ```
* Form
  ```html
  <form>
    <input type="text" name="search">
    <input type="submit" value="Submit">
  </form>
  ```

#### 2. CSS
* Class
  ```css
  .header {
    background-color: #ff0000;
  }

  .logo {
    color: #000;
    font-size: 20px;
  }
  ```

---

### Execises
1. Buat file HTML dengan:
    * Logo
    * Navigation anchor / link
    * Heading
    * Content
    * Images
    * Video
2. Buat file CSS eksternal dengan:
    * Class
    * Aturan:
      * background-color
      * color
      * font-size
      * dll

---

### Feedback
1. Apa yang menjadi bottleneck dari **lesson 02** ini?
2. Apa yang sebaiknya ditambah dan ditiadakan dari materi **lesson 02** ini?

---

### References
1. [Intro to HTML and CSS](https://www.udacity.com/course/intro-to-html-and-css--ud304 "Intro to HTML and CSS")
2. [HTML & CSS for Beginners](https://www.codecademy.com/en/tracks/htmlcss "HTML & CSS for Beginners")

---

| [Home][0] | [Lesson 01][1] | [Lesson 02][2] | [Lesson 03][3] | [Lesson 04][4] | [Lesson 05][5] | [Lesson 06][6] | [Lesson 07][7] | [Presentation][8] |
|:---------:|:--------------:|:--------------:|:--------------:|:--------------:|:--------------:|:--------------------:|:--------------:|:-----------------:|

[0]: README.md "Home"
[1]: lesson-01.md "Internet dan Web Development"
[2]: lesson-02.md "Pengenalan HTML dan CSS"
[3]: lesson-03.md "Pembahasan Lebih Rinci Tentang HTML"
[4]: lesson-04.md "Pembahasan Lebih Rinci Tentang CSS"
[5]: lesson-05.md "Framework Bootstrap"
[6]: lesson-06.md "Personal Project"
[7]: lesson-07.md "Domain, Hosting dan GitHub"
[8]: lesson-08.md "Presentation"
