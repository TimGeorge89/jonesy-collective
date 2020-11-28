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
          <div class="form-box">
            <form>
              <div class="field">
                <label for="name">Name</label>
                <input type="text" placeholder="Name" id="name">
              </div>
              <div class="field">
                <label for="name">Email</label>
                <input type="text" placeholder="Email" id="name">
              </div>
              <div class="field">
                <label for="name">Message</label>
                <textarea placeholder="Type your message here"></textarea>
              </div>
              <button class="button-2">Send</button>
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

  .form-box {
    display: flex;
    width: auto;
    color: black;
    // background: linear-gradient(45deg, rgba($dark-green, 1) 0%, rgba($light-green, 1) 100%);
    border-radius: 10px 40px;
    box-shadow: 5px 10px 15px rgba(#333, 0.5);
    margin: -150px auto 0 auto;
    // padding: 50px;

    form {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: space-between;
      background: linear-gradient(45deg, rgba($dark-green, 1) 0%, rgba($light-green, 1) 100%);
      padding: 60px;
      border-radius: 10px 40px;

  .field {
    width: 100%;
    margin-bottom: 16px;
    
    label {
      display: block;
      font-weight: bold;
      margin-bottom: 5px;
    }
    input {
      width: 100%;
      padding: 5px;
    }
    textarea {
      width: 100%;
      padding: 5px;
      min-height: 125px;
    }
  }

  // button {
  //   padding: 10px 20px;
  //   background: steelblue;
  //   color: #fff;
  //   outline: 0;
  //   border: 0;
  //   border-radius: 5px;
  // }
}

form {
  .field {

    &:nth-child(1),
    &:nth-child(2) {
      width: 48%;
    }
  }
}
  }
}
</style>