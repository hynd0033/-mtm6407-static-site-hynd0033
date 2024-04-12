<template>
    <div className="container">
        <h1>Conner's Top 5 Shows</h1>
      <Navigation />
      <h2>Breaking Bad</h2>
      <h3>Premise from Wikipedia:</h3>
      <p>Created by Vince Gilligan, the series follows the exploits of Walter White, a modest high school chemistry teacher, who discovers a new purpose in life when he learns he has terminal cancer and turns to a life of crime to provide for his family.
      </p>
      <h3>My opinion:</h3>
      <p> If you haven't seem this show or been spoiled by any of it's plot points, you should be studied in a lab as you probably have superpowers. What else can be said about this show 
        that hasn't been said. Iconic, funny, dramatic. There is a reason it won many awards and still has memes made about it. 10/10. Walter White really is the one who knocks.
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
    }
    </style>