<template>
  <div class="connect">
    
    <div class="hero">
      <div class="wrapper">
        <div class="main-hero">
          <h1>Connect With Us</h1>
          <p>We would love to hear from you!</p>
        </div>
      </div>
    </div>

    <div class="form-container">
        <div class="wrapper">
          <div class="form">
            <form class="contact-form">
              <!-- FORM TOP -->
              <div class="form-top">
                <!-- NAME FORM -->
                <div class="name">
                  <label>Name:</label>
                  <input type="text" name="user_name">
                </div>
                  <!-- EMAIL FORM -->
                <div class="email">
                  <label>Email:</label>
                  <input type="email" name="user_email">
                </div>

              </div>
              <!-- FORM BOTTOM -->
              <div class="form-bottom">
                <!-- MESSAGE FORM -->
                <div class="message">
                  <label>Message:</label>
                  <textarea name="message"></textarea>
                    <!-- SUBMIT BUTTON -->
                  <div class="submit">
                    <input type="submit" value="Send">
                  </div>
                </div>
                
              </div>
            </form>
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

  .form-container {
    padding: 60px 30px;

  .wrapper {
    display: flex;
    align-items: center;
    margin: 0 auto;
  }

  .form {
    display: flex;
    width: auto;
    color: white;
    background: linear-gradient(45deg, rgba($dark-green, 1) 0%, rgba($light-green, 1) 100%);
    border-radius: 10px 40px;
    box-shadow: 5px 10px 15px rgba(#333, 0.5);
    margin: -150px auto 0 auto;
    padding: 50px;

    .contact-form {
      
    }
  }
}
</style>