
<html>
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-5162521429185697"
     crossorigin="anonymous"></script>
<style>
    #container_div {
  width: 25%;
  height: 500px;
  border-radius: 5px;
  border: 4px solid black;
  background-image: url(54850_naruto.jpg);
  background-size: cover;
  margin: auto;
}

div > h1 {
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
      -ms-flex-pack: center;
          justify-content: center;
  margin-top: auto;
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  margin-bottom: 50px;
}

#btn_1 {
  width: 50%;
  margin-left: 25%;
  height: 70px;
  margin-top: 10px;
  display: block;
  background-color: red;
  margin-bottom: 10px;
  font-weight: bolder;
  font-size: 30px;
  border-radius: 5px;
}

#btn_2 {
  width: 50%;
  margin-left: 25%;
  height: 70px;
  background-color: green;
  font-size: 30px;
  font-weight: bolder;
}

@media screen and (max-width: 600px) {
  body {
    background-color: #2c2c2c;
    background-size: cover;
  }
  body div {
    min-height: 50%;
    min-width: 60%;
  }
  #btn_1 {
    width: 50%;
    margin-left: 25%;
    height: 70px;
    margin-top: 10px;
    display: block;
    background-color: red;
    margin-bottom: 10px;
    font-weight: bolder;
    font-size: 30px;
    border-radius: 5px;
    border: white;
  }
  #btn_2 {
    width: 50%;
    margin-left: 25%;
    height: 70px;
    border: white;
    background-color: green;
    font-size: 30px;
    font-weight: bolder;
  }
}

#paragraph {
  font-weight: bolder;
  font-size: 25px;
  color: black;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
      -ms-flex-pack: center;
          justify-content: center;
}
/*# sourceMappingURL=countApp.css.map */
</style>
</head>
<body id="body">
    <div id="container_div">
        <h1>People entered:</h1>
        <h1 id="count">0</h1>
        <button id="btn_1" onclick="counter()">Count</button>
        <button id="btn_2" onclick="safe()">Save</button>
        <p id="paragraph"></p>
    </div>
    <script>
    let number = document.getElementById("count")
 let buttonClick = document.getElementById("btn_1")
let count = 0
function counter(){
    let x = count += 1
    number.innerText = x
}
// next stuffs 
document.getElementById("btn_2")
function safe(){
let paragraph = document.getElementById("paragraph")
let p = paragraph.innerText = "_" + number.innerText + "_"
number.textContent = "0"
count = 0
}
// a comment
    </script>
 <h1>Counter App</h1>
<p>hey.. this is my counter web application with html, css and js. Now off you go</p>
</body>
</html>
