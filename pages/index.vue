<template>
    <div className="container">
        <h1>Conner's Top 5 Shows</h1>
      <Navigation />
      <h2>Home Page</h2>
      <p>This site was created to showcase my Top 4 favourite shows. Click on each page to view more about why I like each one.
        <br></br>
        Shoutout to my brother. I've watched all these shows because I saw him watching them first.
      </p>
    </div>
  </template>
 
  <script setup>
  
  </script>
  
  <style scoped>

.container {
    margin: 0 auto;
  }

@media screen and (min-width: 300px) {
    .container {
        width: 299px;
    }
}

@media screen and (min-width: 600px) {
    .container {
        width: 599px;
    }
}

@media screen and (min-width: 900px) {
    .container {
        width: 899px;
    }
}

@media screen and (min-width: 1200px) {
    .container {
        width: 1199px;
    }
}
  
  h1 {
    color: red;
    text-align: center;
    font-size: 64px;
  }

  h2 {
    font-size: 48px;
    text-align: center;
  }

  h3 {
    font-size: 32px;
    text-align: center;
  }

  p {
    font-size: 24px;
    text-align: center;
  }

  </style>
  