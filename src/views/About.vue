<template>
  <div class="about">

    <div class="hero">
      <div class="wrapper">
        <div class="main-hero">
        <h1>About The Collective</h1>
        <p>Our Team and Our Mission.</p>
        <!-- <div>
          <button class="button-2">About</button>
          <button class="button-2">Connect</button>
        </div> -->
      </div>
      </div>
    </div>

    <div class="content-2">
        <div class="wrapper">
          <div class="b">
            <div>
              <img src="/images/jonesybeeasy.jpg">
            </div>
            <div class="b-content">
              <h3>About Us</h3>
                <p>Alex Hwang Jones was a young, visionary leader in the Central Florida
                  electronic arts and dance community. Alex had a huge love of the arts in
                  every form, as well as deep plant knowledge and strong values for the careful
                  use of plant medicines - values he widely espoused with his peers, many of whom
                  are young adults alienated in today’s difficult economy, who are suffering
                  from stress, depression, and are looking for safe creative outlets that inspire
                  hope. As his family mourned Alex’s passing this past summer from gun violence, 
                  his hundreds of friends came to me with thousands of dollars they raised through
                  a grass-roots effort to memorialize his life. Together we will make a difference 
                  in Central Florida by connecting to his community, providing important education 
                  and peer-awareness for harm reduction – through the arts. The Jonesy Collective 
                  was founded on Oct. 8, 2020. Local community art events are being planned where 
                  proceeds will be given to more mature national organizations such as MAPs and 
                  DanceSafe - organizations that reflect Alex’s goals and values
                </p>
              <div>
                <!-- <router-link to="/about" class="button-2">About</router-link> -->
                <a href="https://www.facebook.com/thejonesycollective" target="_blank" ><button class="button-2">Facebook</button></a>
                <a href="https://maps.org/" target="_blank" ><button class="button-2">MAPS</button></a>
                <a href="https://dancesafe.org/" target="_blank" ><button class="button-2">DanceSafe</button></a>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- VIDEO -->
      <div class="video-container">
        <div class="video-wrapper">
          <div class="video">
            <iframe width="740" height="415" src="https://www.youtube.com/embed/k2KgI_x9g_8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
          </div>
        </div>
      </div>

    <!-- FOUNDERS -->
    <div class="founders">
      <div class="team-title">
          <h1>Our Amazing Team</h1>
        </div>
      <div class="wrapper">
        <!-- CARDS -->
        <div class="team-card">
          <div>
            <img src="images/woman.jpg">
          </div>
          <div class="team-content">
            <h3>Mimi Hwang</h3>
            <p>Mimi Hwang is the founder and chair of the Jonesy Foundation,
               created in loving tribute to her son Alex Hwang Jones. Mimi is
               an artist with residency at McRae Arts and Beaux Arts, two of 
               the largest artist collectives in Central Florida. In her professional
               life, Mimi spent decades in publishing and media in various executive 
               roles at Time Inc. (Time Warner) and HBO in NYC, and at Harcourt after 
               moving to Orlando, FL. Mimi also founded Kao eTechnologies, a technology 
               consulting firm in Orlando. Mimi is active in her local community serving 
               on the Timucua Arts Board as Secretary, and the Orange County Democratic 
               Party as Precinct Woman. Mimi attended University of Wisconsin-Madison 
               with a degree in Psychology. Mimi currently resides in Winter Park, Fl.
            </p>
          </div>
        </div>

        <!-- CARDS -->
        <div class="team-card">
          <div>
            <img src="images/male.jpg">
          </div>
          <div class="team-content">
            <h3>Mimi Hwang</h3>
            <p>Mimi Hwang is the founder and chair of the Jonesy Foundation,
               created in loving tribute to her son Alex Hwang Jones. Mimi is
               an artist with residency at McRae Arts and Beaux Arts, two of 
               the largest artist collectives in Central Florida. In her professional
               life, Mimi spent decades in publishing and media in various executive 
               roles at Time Inc. (Time Warner) and HBO in NYC, and at Harcourt after 
               moving to Orlando, FL. Mimi also founded Kao eTechnologies, a technology 
               consulting firm in Orlando. Mimi is active in her local community serving 
               on the Timucua Arts Board as Secretary, and the Orange County Democratic 
               Party as Precinct Woman. Mimi attended University of Wisconsin-Madison 
               with a degree in Psychology. Mimi currently resides in Winter Park, Fl.
            </p>
          </div>
        </div>

        <!-- CARDS -->
        <div class="team-card">
          <div>
            <img src="images/woman.jpg">
          </div>
          <div class="team-content">
            <h3>Mimi Hwang</h3>
            <p>Mimi Hwang is the founder and chair of the Jonesy Foundation,
               created in loving tribute to her son Alex Hwang Jones. Mimi is
               an artist with residency at McRae Arts and Beaux Arts, two of 
               the largest artist collectives in Central Florida. In her professional
               life, Mimi spent decades in publishing and media in various executive 
               roles at Time Inc. (Time Warner) and HBO in NYC, and at Harcourt after 
               moving to Orlando, FL. Mimi also founded Kao eTechnologies, a technology 
               consulting firm in Orlando. Mimi is active in her local community serving 
               on the Timucua Arts Board as Secretary, and the Orange County Democratic 
               Party as Precinct Woman. Mimi attended University of Wisconsin-Madison 
               with a degree in Psychology. Mimi currently resides in Winter Park, Fl.
            </p>
          </div>
        </div>
      </div>
    </div>

  </div>
</template>

<style lang="scss">

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


.content-2 {
  padding: 60px 30px;

  .wrapper {
    display: flex;
    align-items: center;
    margin: 0 auto;
  }

  .b {
    display: flex;
    width: 100%;
    color: white;
    background: linear-gradient(45deg, rgba($dark-green, 1) 0%, rgba($light-green, 1) 100%);
    border-radius: 10px 40px;
    box-shadow: 5px 10px 15px rgba(#333, 0.5);
    margin: -150px auto 0 auto;
    padding: 50px;

     img {
       height: auto;
       padding-right: 30px;
       border-radius: 15px;
       height: 500px;

     }
  }
}

.video-container {
  display: flex;
  justify-content: center;
  margin: 0 0 60px 0;
}


.founders {
    background-color: #eee;
    padding: 0 30px 30px 30px;
    

    .team-title {
      text-align: center;
      padding: 50px 0;

      h1 {
        font-size: 60px;
      }
    }  

    .wrapper {
      display: flex;
      justify-content: space-between;

      .team-card {
      width: 31%;
      background-color: white;
      align-items: center;
      padding: 30px 20px;
      border-radius: 10px;
      box-shadow: 5px 10px 15px rgba(#333, 0.5);

      img {
        display: block;
        margin: 0 auto;
        height: 150px;
      }

      .team-content {
        text-align: center;
      }
    } 
  }
}

</style>