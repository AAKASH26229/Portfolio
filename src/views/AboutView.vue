<template>
  <header>
      <nav>
          <div class="left">Portfolio</div>
          <div class="right">
            <ul>
              <li><a href="/">Home</a></li>
              <li><a href="../views/AboutView.vue">About</a></li>
              <li><a href="/">Projects</a></li>
              <li><a href="/">Contact Me</a></li>
            </ul>
          </div>
      </nav>
  </header>

  
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
  height: 80vh;
}

.text-gray{
  color: gray;
}

.secondSection h1 {
  font-size: 1.9rem;
}

.secondSection .box {
  background: white;
  width: 80vw;
  height: 1px;
  margin: 35px 0;
  display: flex;
}

.secondSection .vertical {
  height: 93px;
  width: 1px;
  background-color: white;
  margin: 0 100px;
}

.button{
  margin-top: 34px;
}

.button button{
  padding: 9px 14px;
  border-radius: 22px;
  color: white;
  background-color: dodgerblue;
  font-weight: bold;
  font-size: 21px;
  margin: 0  3px;
  cursor: pointer;
}

.button button:hover {
  color: dodgerblue;
  background-color: white;
}

</style>


