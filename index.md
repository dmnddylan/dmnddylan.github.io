<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
* {
  box-sizing: border-box;
}

.menu {
  float: left;
  width: 35%;
  text-align: center;
}

.menu a {
  background-color: #e5e5e500;
  padding: 8px;
  margin-top: 7px;
  display: block;
  width: 100%;
  color: black;
}

.main {
  float: left;
  width: 45%;
  padding: 0 20px;
}

.right {
  background-color: #e5e5e500;
  float: left;
  width: 20%;
  padding: 15px;
  margin-top: 7px;
  text-align: left;
}

@media only screen and (max-width: 620px) {
  /* For mobile phones: */
  .menu, .main, .right {
    width: 100%;
  }
}
</style>
</head>
<body style="font-family:Verdana;color:#aaaaaa;">

<div style="background-color:#e5e5e500;padding:15px;text-align:left;">
  <h1>Source 2</h1>
</div>

<div style="overflow:auto">
  <div class="menu">
    <a href="#">Half Life 2: Episode 1 Level Recreation</a>
    <a href="#">Link 2</a>
    <a href="#">Link 3</a>
    <a href="#">Link 4</a>
  </div>

<!-- Make this part have images -->

  <div class="main">
    <h2>Lorum Ipsum</h2>
    <p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.</p>
  </div>

  <div class="right">
    <h2>About</h2>
    <p>I'm a Kansas based game devloper person.</p>
  </div>
</div>

</body>
</html>