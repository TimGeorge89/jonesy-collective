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
            <div class="image-container">
              <img src="/images/jonesybeeasy.jpg">
            </div>
            <div class="b-content">
              <h3>About Us</h3>
                <p>Alex Hwang Jones was a young, visionary leader in the Central Florida electronic arts and dance community. Alex’s passing on June 24, 2020 from an armed robbery is deeply mourned by his hundreds of friends, These friends, his sangha, immediately came together,  raising thousands of dollars in a spontaneous grass-roots effort to memorialize his life.    And telling me stories of their friendship.
                   So I, his mother, in my grief listened to these stories.  Some I knew - that Alex loved the arts in every form, had strong values for the careful use of plant medicines – and had a loving, wise and kind nature.  And I was deeply moved - the stories became countless stories of how he helped, how he impacted so many lives for the better, in inspiration and friendship.  His deep connection with his friends as family was what he lived for - many of whom are tremendous creatives suffering from stress, depression, tough times - and yet with Alex were always looking for ways to help with hope, and strength and doing.   
                   I am so blessed I do not grieve alone.   We will never forget the light that was my son, their friend and brother, Alex Hwang Jones.  In powerful, loving tribute, the Jonesy Collective was founded on Oct. 8, 2020. Together we will make a difference in Central Florida by connecting to the community, providing important education and awareness for harm reduction, finding nurturing ways to help each other and Mother Earth – and inspiring through the arts. Community art, music and film events are being planned where proceeds will be given to national organizations such as MAPs and DanceSafe, as well a local organizations such as Zebra Coalition and iDignity.  This list is just a beginning as we find ways to help that reflect Alex’s work, his wisdom, goals and values. 
                </p>
              <div class="b-buttons">
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
            <iframe class="responsive-iframe" width="740" height="415" src="https://www.youtube.com/embed/k2KgI_x9g_8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
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
            <img src="images/head_shot.jpg">
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
          <!-- <div>
            <img src="images/male.jpg">
          </div> -->
          <div class="team-content">
            <h1>The Collective</h1>
            <!-- team member -->
            <h3>Steve Dykes</h3>
            <p>Treasurer</p>
            <!-- team member -->
            <h3>Kaylee Oberfield</h3>
            <p>Secretary & Art Task Force</p>
            <!-- team member -->
            <h3>Meza Ayala</h3>
            <p>Art Task Force</p>
            <!-- team member -->
            <h3>Tyler Cortez</h3>
            <p>Art Task Force</p>
          </div>
        </div>

        <!-- CARDS -->
        <!-- <div class="team-card">
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
        </div> -->
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

    .b-content {
      p {
        padding: 20px;
      }
    }
    .image-container {
      margin: auto;
      img {
        height: auto;
        padding-right: 30px;
        border-radius: 15px;
        height: 350px;
      }
    }

    
  }

  @media screen and (max-width: 1105px) {
    .b {
      display: block;
      text-align: center;

      p {
        margin: 0 10px;
      }
    }
  }

  @media screen and (max-width: 650px) {
    .b {
      padding: 5px;
      .b-content {
        .b-buttons {
          display: none;
        }
        h3 {
          display: none;
        }
      }
      img {
        display: none;
      }
    }
  }
}

.video-container {
  display: flex;
  justify-content: center;
  margin: 0 0 60px 0;

  .video-wrapper {
    position: relative;
    overflow: hidden;
    width: 100%;
    padding-top: 56.25%;
  }

  .responsive-iframe {
    margin: auto;
    position: absolute;
    top: 0;
    left: 0;
    bottom: 0;
    right: 0;
    width: 90%;
    height: 75%;
  }
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
      display: block;
      justify-content: space-between;

      .team-card {
      width: 90%;
      background-color: white;
      margin: 40px 20px;
      align-items: center;
      padding: 30px 50px;
      border-radius: 10px;
      box-shadow: 5px 10px 15px rgba(#333, 0.5);

      img {
        display: block;
        margin: 0 auto;
        height: 150px;
      }

      .team-content {
        text-align: center;
        h1 {
          margin-bottom: 20px;
          text-decoration: underline;
        }
      }
    } 
  }
}
</style>