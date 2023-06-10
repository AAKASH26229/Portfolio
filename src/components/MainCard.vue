<template>
    <header>
        <nav>
            <div class="left">Portfolio</div>
            <div class="right">
              <ul>
                <li><a href="/">Home</a></li>
                <li><a href="/">About</a></li>
                <li><a href="/">Projects</a></li>
                <li><a href="/">Contact Me</a></li>
              </ul>
            </div>
        </nav>
    </header>

    <main>
      <section class="firstSection">
        <div class="leftSection">
          Hi, My name is <span class="purple">Aakash Parate</span>
          <div>and I am a passionate</div>
          <div>web developer</div>
          <span id="element"></span>
        </div>
        <div class="rightSection">
          <img src="../assets/bg.png" alt="background image">
        </div>
      </section>
<hr>
      <section class="secondSection">
        <span class="grey">What I have done so far</span>
        <h1>Work Experience</h1>
      </section>
    </main>
  </template>


  <style > 
  *{
    margin: 0;
    padding: 0;
  }

  body{
    background-color: rgb(4, 4, 62);
    color: white;
    font-family: 'Poppins', sans-serif;
  }

  nav {
    display: flex;
    justify-content: space-around;
    align-items: center;
    height: 75px;
    background-color: rgb(37, 40, 108);
  }

  nav ul {
    display: flex;
    justify-content: center;
  }

  nav ul li {
    list-style: none;
    margin: 0 23px;
  }

  nav ul li a {
    text-decoration: none;
    color: white;
  }

  nav ul li a:hover {
    color: blueviolet;
    font-size: 1.02rem;
  }

  main hr {
    border: 0;
    background: #9C97f1;
    height: 1.4px;
    margin: 60px 104px;
  }

  .left {
    font-size: 1.5rem;
  }

  .firstSection{
    display: flex;
    justify-content: space-around;
    margin: 100px 0;
    align-items: center;
  }

  .firstSection > div{
    width: 30%;
  }
  
  .leftSection{
    font-size: 3rem;
  }
  
  .rightSection img{
    width: 80%;
   
  }
  
  .purple{
    color: chartreuse;
  }

  .secondSection{
    max-width: 80vw;
    margin: auto;
  }

  .secondSection h1 {
    font-size: 1.9rem;
  }
  </style>


