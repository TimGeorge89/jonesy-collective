<template>
  <div class="home">
    
    <div class="hero">
      <div class="wrapper">
        <div class="main-hero">
        <h1>The Jonesy Collective</h1>
        <p>In tribute to the life and love of Alex Hwang Jones.</p>
        <div>
          <router-link to="/about"><button class="button-2">About</button></router-link>
          <router-link to="/connect"><button class="button-2">Connect</button></router-link>
        </div>
      </div>
      </div>
    </div>

    <div class="content-2">
        <div class="wrapper">
          <div class="a">
            <h3>Our Mission Summary</h3>
            <p>The Jonesy Collective provides a forum for creative artists to express and celebrate themselves in ways that inspire and support their peers – assisting young people who face homelessness, isolation from family, anxiety and depression, addictions and drug abuse - through art and cultural events where proceedings will be used to promote health and safety,  education and awareness on substance abuse issues, and support for our mother earth.</p>
          </div>
          <div class="b">
            <div class="b-content">
              <h3>About Us</h3>
              <p>The Jonesy Collective was founded on Oct. 8, 2020.  Local community art events are being planned where proceeds will be given to more mature national organizations such as MAPs and DanceSafe - organizations that reflect Alex’s goals and values, and where research and safety activities raise hope for more positive outcomes on mental health issues.</p>
              <p>Over the next several weeks this website will be built and updated to include calanders, events, videos, and pictures, as well as a way to donate to the foundation!</p>
              <div class="about-buttons">
                <router-link to="/about"><button class="button-2">About</button></router-link>
                <a href="https://www.facebook.com/thejonesycollective" target="_blank" ><button class="button-2">Facebook</button></a>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="villan">
        <div class="wrapper">
          <!-- TIPPLE CARD -->
          <div class="tripple">
            <div class="tripple-content">
              <h3>Events</h3>
              <p>Events are being planned and will be updated here. If you have any questions or would like to plan an event you can contact us here or through our facebook page.</p>
              <router-link to="/connect"><button class="button">Connect</button></router-link>
            </div>
          </div>
          <!-- TIPPLE CARD -->
          <div class="tripple">
            <div class="tripple-content">
              <h3>Artists</h3>
              <p>A big part of the Jonesy Collective is our collective of artisits from all walks of life. Our artists are an integral part of our identity and what we stand for. You can check out our artisits here.</p>
              <button>JC Artists</button>
            </div>
          </div>
          <!-- TIPPLE CARD -->
          <div class="tripple">
            <div class="tripple-content">
              <h3>Donate</h3>
              <p>Help our cause and many others by donating to the Jonesy Collective. 100% of your donation goes to helping educate, support and connect through visionary art and dance.</p>
              <button>Donate</button>
            </div>
          </div>
        </div>
      </div>

      

  </div>
</template>

 <script>

 </script>

<style lang="scss" scoped>

.hero {
  background-image: url('/images/lowpoly.jpg');
  background-position: top;
  background-size: cover;
  height: 500px;
  width: 100%; 

  .wrapper {
    display: flex;
    align-items: center;
  }

  .main-hero {
    border-radius: 10px 50px;
    height: 100%;
    width: 1000px;
    text-align: center;
    margin: 0 auto;
    padding-top: 170px;

    h1 {
      font-size: 60px;
      color: white;
    }

    p {
      font-size: 20px;
      color: white;
    }
  }
}

// BEGIN MEDIA QUERY

// END MEDIA QUERY

.content-2 {
  display: flex;
  padding: 60px 30px;

  .wrapper {
    display: flex;
    align-items: center;
    margin: 0 auto;
  }

  .a {
    width: 50%;
    padding-right: 50px;
    margin-left: 0 auto;
    
  }

  .b {
    display: flex;
    width: 40%;
    color: white;
    background: linear-gradient(45deg, rgba($dark-green, 1) 0%, rgba($light-green, 1) 100%);
    border-radius: 10px 40px;
    box-shadow: 5px 10px 15px rgba(#333, 0.2);
    margin-top: -150px;
    margin-left: auto;
    padding: 50px;
  }
}

@media screen and (max-width: 426px) {
  .button-2 {
  color: white;
  padding: 10px 20px;
  text-align: center;
  text-decoration: none;
  font-size: 15px;
  margin-right: 15px;
  }
}

@media only screen and (max-width: 1000px) {
  .content-2 {

    .wrapper {
      flex-direction: column;
    }

    .a {
      text-align: center;
      width: 100%;
      margin: 0;
      padding: 0;
    }

    .b {
      width: 100%;
      margin: 0;
    }
  }

  .villan {
    padding: 0;
    margin: 0;

    .wrapper {
      flex-direction: column;
      padding: 0;
      margin: 0;
    }

    .tripple {
      align-self: center;
      margin: 20px;
      min-width: 100%;
      min-height: 350px;

      .tripple-content {
        text-align: center;
      }
    }
  }
}

  .villan {
    background-color: #eee;
    padding: 60px 30px;

    .wrapper {
      display: flex;
      justify-content: space-between;
      
    }

    .tripple {
      display: flex;
      width: 31%;
      background-color: white;
      align-items: center;
      padding: 60px 20px;
      border-radius: 10px;
      box-shadow: 5px 10px 15px rgba(#333, 0.2);

      .tripple-content {
        text-align: center;
      }
    }
  }
</style>
