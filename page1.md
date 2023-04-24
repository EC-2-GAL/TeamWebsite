<html>
  <head>
    <link rel="stylesheet" href="page1.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
  </head>
  <body>
    <button id="dark" onclick="darkMode()">Dark Mode</button>
    <h3><img id= "EC2" src ="images/fav.png"></h3>
    <h4><i class="material-icons">favorite</i>click on each topic to learn more!<i class="material-icons">favorite</i></h4>
        <div class="row">
        <button onclick="visibility()">Basic User Interface (UI) Properties</button>
        </div>
        <div class="column" id="column1">
        <h2>Properties:</h2>
    <p>
        <ul>
          <li>Color: This refers to the hue, saturation, and brightness of the UI elements such as background, text, buttons, etc.</li>
            <a href="https://htmlcolorcodes.com/">HTML Color Codes</a><br>
            <img src ="images/css4.jpg">
            <br><br>
          <li>Font: This refers to the typeface, size, weight, and style of the text displayed on the UI.</li>
            <a href="https://www.w3schools.com/css/css_font.asp">HTML Fonts</a><br>
            <img src ="images/css3.jpg">
            <br><br>
          <li>Layout: This refers to the arrangement and positioning of UI elements such as buttons, text boxes, images, etc</li>
            <p>Make wireframes to plan Layout!</p>
            <p>Resources: canva</p>
            <br><br>
          <li>Icons: These are small graphical symbols used to represent actions or ideas in the UI.</li>
            <br><br>
          <li>Interactivity: This refers to how the UI responds to user actions, such as clicking, tapping, dragging, and scrolling.</li>
            <br><br>
          <li>Accessibility: This refers to the ability of the UI to be used by people with disabilities, such as support for screen readers, keyboard navigation, and color contrast.</li>
        </ul>
      <br>
      <p>Identify all these properties on this page</p>
    </p>
        </div>
        <div class="row">
        <button onclick="visibility2()">Adding/Changing Colors</button>
        </div>
    <div class="column" id="column2">
        <h2>Changing Text and Background Color:</h2>
        <p>
    Programming languages: To change the color of text, you will need to know how to write code in a programming language that supports text formatting. Some common programming languages that support this include HTML, CSS, JavaScript, and Python.
    <br><br>
    Color codes: To change the color of text, you will need to know the hexadecimal or RGB color code for the color you want to use. The hexadecimal code is a six-digit code that represents the red, green, and blue values of a color, while the RGB code represents the red, green, and blue values as integers between 0 and 255.
    <br><br>
    CSS syntax: If you are using CSS to change the color of text, you will need to know the syntax for defining styles for HTML elements. This includes understanding the selector, property, and value syntax used in CSS.
    <br><br>
    HTML structure: To change the color of text in HTML, you will need to understand the basic structure of an HTML document and how to add styles to individual elements using inline styles or external style sheets.
    <br>
    </p>
    <img src ="images/css1.jpg">
    <img src ="images/css2.jpg">
    <h2>Themes</h2>
    <p>
    1. Create a file called /assets/css/style.scss in your site
    <br><br>
    2. Add the following content to the top of the file, exactly as shown: 
    <img src ="images/themecode.png">
    <br><br>
    3. Add any custom CSS (or Sass, including imports) you’d like immediately after the @import line
    <br><br>
    Stylesheets: To change the visual appearance of an application or platform, you may need to modify the stylesheets that control the presentation of the user interface elements. This may involve editing existing styles or creating new ones.
    <br><br>
    Configuration files: Some applications and platforms may have configuration files that control the behavior and appearance of the application. To change the theme, you may need to modify these configuration files.
    <br>
    </p>
    </div>
      <div class="row">
    <button onclick="visibility3()">Images</button>
    </div>
    <div class="column" id="column3">
    <p>
      <h2>Styling Images (No Animation)</h2>
        - rounded corners on images and buttons
        - center
        - opacity
        - grayscale
      <img src ="images/EC2.png" id="EC2">
      <h2>Other Things You Need to Know for the AP Exam</h2>
      <h5>Data Compression</h5>
        <img src ="images/loss.jpg" id="loss">
        <br><br>
      <h5>base 64</h5>
        Binary data: Base64 is used to encode binary data, such as images, audio, and video files. You will need to understand how binary data is represented and stored in computing systems.
        <br><br>
        ASCII encoding: Base64 converts binary data into ASCII text format, which can be transmitted and stored more easily than binary data. You will need to understand ASCII encoding and how it works.
        <br><br>
        Encoding process: Base64 encodes binary data by splitting it into 6-bit chunks and encoding each chunk as a single character in the Base64 character set. You will need to understand how this encoding process works.
        <br><br>
        Decoding process: Base64 also includes a decoding process that converts Base64-encoded text back into binary data. You will need to understand how this decoding process works.
    </p>
    </div>
        <div class="row">
        <button onclick="visibility4()">Importance of Wireframes</button>
        </div>
        <div class="column" id="column4">
        <h2>Properties:</h2>
    <img src ="images/Page1WF.jpg">
    </div>
    <script>
    var visibility = (function() {
      var first = true;
      return function() {
        first ? showColumn() : hideColumn();
        first = !first;
      }
    })();
    hideColumn();
      function hideColumn(){
    document.getElementById("column1").style.visibility = "hidden";
    }
        function showColumn() {
      document.getElementById("column1").style.visibility = "";
    }
    var visibility2 = (function() {
      var first = true;
      return function() {
        first ? showColumn2() : hideColumn2();
        first = !first;
      }
    })();
    hideColumn2();
      function hideColumn2(){
    document.getElementById("column2").style.visibility = "hidden";
    }
        function showColumn2() {
      document.getElementById("column2").style.visibility = "";
    }
    var visibility3 = (function() {
      var first = true;
      return function() {
        first ? showColumn3() : hideColumn3();
        first = !first;
      }
    })();
    hideColumn3();
      function hideColumn3(){
    document.getElementById("column3").style.visibility = "hidden";
    }
        function showColumn3() {
      document.getElementById("column3").style.visibility = "";
    }
    var visibility4 = (function() {
      var first = true;
      return function() {
        first ? showColumn4() : hideColumn4();
        first = !first;
      }
    })();
    hideColumn4();
      function hideColumn4(){
    document.getElementById("column4").style.visibility = "hidden";
    }
        function showColumn4() {
      document.getElementById("column4").style.visibility = "";
    }
    function darkMode() {
      var element = document.body;
      element.classList.toggle("dark-mode");
    }
    </script>
