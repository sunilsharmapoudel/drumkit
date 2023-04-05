# DurnKit - Fun with all drum sets.

This is complete project on using DOM manupulation while learning Full Stack.
## Table of contents

- [Overview](#overview)
  - [Screenshots](#screenshots)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)
## Overview
### Screenshots

Desktop Screenshot

![Desktop](/images/DurmKit-Desktop.png)
Moile Screenshot

![Mobile](/images/DurmKit-Mobile.png)
### Links

- Live Site URL: [https://sunilsharmapoudel.github.io/dogmate/](https://sunilsharmapoudel.github.io/dogmate/)

### Built with

- HTML5 markup
- CSS custom properties
- JavaScript

### What I learned

From this project I learned to manipulate HTML DOM elements, using setTimeout, using Event Listener.

```
<body>

  <h1 id="title">Drum 🥁 Kit</h1>
  <div class="set">
    <button class="w drum">w</button>
    <button class="a drum">a</button>
    <button class="s drum">s</button>
    <button class="d drum">d</button>
    <button class="j drum">j</button>
    <button class="k drum">k</button>
    <button class="l drum">l</button>
  </div>


  <footer>
    <p> By <a class="author" href="http://sunilsharmapoudel.com">Sunil Sharma</a></p>
  </footer>
  <script src="index.js"></script>
  </body>

```
```css
body {
  text-align: center;
  background-color: #283149;
}

h1 {
  font-size: 5rem;
  color: #DBEDF3;
  font-family: "Arvo", cursive;
  text-shadow: 3px 0 #DA0463;

}

footer {
  color: #DBEDF3;
  font-family: sans-serif;
}

.w {
  background-image:url(./images/crash.png);
}

.a {
 background-image:url(./images/kick.png);
}

.s {
 background-image:url(./images/snare.png);
}

.d {
 background-image:url(./images/tom1.png);
}

.j {
 background-image:url(./images/tom2.png);
}

.k {
 background-image:url(./images/tom3.png);
}

.l {
 background-image:url(./images/tom4.png);
}

.set {
  margin: 10% auto;
}

.game-over {
  background-color: red;
  opacity: 0.8;
}

.pressed {
  box-shadow: 0 3px 4px 0 #DBEDF3;
  opacity: 0.5;
}

.red {
  color: red;
}

.drum {
  outline: none;
  border: 10px solid #404B69;
  font-size: 5rem;
  font-family: 'Arvo', cursive;
  line-height: 2;
  font-weight: 900;
  color: #DA0463;
  text-shadow: 3px 0 #DBEDF3;
  border-radius: 15px;
  display: inline-block;
  width: 150px;
  height: 150px;
  text-align: center;
  margin: 10px;
  background-color: white;
}

.author {
  text-decoration: none;
  color: blue;
  background-color: orange;
  padding: 5px;
  font-style: bold;
  border-radius: 5px;
}
```

## Author

- Website - [Sunil Sharma](https://github.com/sunilsharmapoudel)
- Facebook - [@mesunilsharmapoudel](https://www.facebook.com/mesunilsharmapoudel)
- Twitter - [@techsunilsharma](https://www.twitter.com/techsunilsharma)

## Acknowledgments
Thanks to Dr. Angela Yu, my instructor who instructed me during her course. She guided me during the course and I followed her approach.