<template>
  <div class="home">
    
    <!-- <Navigation></Navigation> -->

    <div class="hero">
      <div class="wrapper">
        <div class="main-hero">
        <h1>The Jonesy Collective</h1>
        <p>In tribute to the life and love of Alex Hwang Jones.</p>
        <div>
          <button>About</button>
          <button>Connect</button>
        </div>
      </div>
      </div>
    </div>

    <div class="content-2">
        <div class="wrapper">
          <div class="a">
            <h3>Our Mission</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          </div>
          <div class="b">
            <div class="b-content">
              <h3>About Us</h3>
              <p>The Jonesy Collective was founded on Oct. 8, 2020.  Local community art events are being planned where proceeds will be given to more mature national organizations such as MAPs and DanceSafe - organizations that reflect Alex’s goals and values, and where research and safety activities raise hope for more positive outcomes on mental health issues.</p>
              <p>Over the next several weeks this website will be built and updated to include calanders, events, videos, and pictures, as well as a way to donate to the foundation!</p>
              <div>
                <a href=""><button class="button-2">About</button></a>
                <a href="https://www.facebook.com/thejonesycollective" target="_blank" ><button class="button-2">f</button></a>
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
              <h3>Statement</h3>
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
              <button>Click here</button>
            </div>
          </div>
          <!-- TIPPLE CARD -->
          <div class="tripple">
            <div class="tripple-content">
              <h3>Statement</h3>
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
              <button>Click here</button>
            </div>
          </div>
          <!-- TIPPLE CARD -->
          <div class="tripple">
            <div class="tripple-content">
              <h3>Statement</h3>
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. </p>
              <button>Click here</button>
            </div>
          </div>
        </div>
      </div>

  </div>
</template>

 <script>
// import Navigation from '@/components/Navigation'

// export default {
//   data() {
//     return {

//     }
//   },
//   components: {Navigation}
// }
 </script>

<style lang="scss" scoped>

.hero {
  background: $light-blue;
  background: radial-gradient(circle, rgba($dark-blue, 1) 0%, rgba(darken($blue, 20%), 1) 100%);
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

.content-2 {
  margin: 0 30px;

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
     width: 40%;
     display: flex;
     background: linear-gradient(45deg, rgba($dark-green, 1) 0%, rgba($light-green, 1) 100%);
     border-radius: 10px 40px;
     box-shadow: 5px 10px 15px rgba(#333, 0.5);
     margin-top: -150px;
     margin-left: auto;
    // height: 500px;
     padding: 40px;
    
  }
}

  .villan {
    height: 500px;
    background: $light-blue;
    background: radial-gradient(circle, rgba(darken($light-green, 20%), 1) 0%, rgba($dark-green, 1) 100%);
    margin-top: 50px;
    padding-top: 30px;

    .wrapper {
      display: flex;
    }

    .tripple {
      display: flex;
      width: 33%;
      height: 400px;
      background-color: white;
      align-items: center;
      margin: 30px 20px;
      padding: 30px 15px;
      border-radius: 10px;
      box-shadow: 5px 10px 15px rgba(#333, 0.5);

      .tripple-content {
        text-align: center;
      }
    }
  }
</style>
