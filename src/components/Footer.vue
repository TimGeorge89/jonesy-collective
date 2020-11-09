<template lang="html">

  <div class="bottom-nav">
    <div class="fwrapper">
      <!-- FOOTER CONTENT -->
      <div class="footer">
        <div class="footer-content">
          <p>Copyright © 2020 Jonesy Collective, All Rights Reserved</p>
        </div>
      </div>

      
      <div class="footer">
        <div class="footer-content">
          <a href="https://www.facebook.com/thejonesycollective" target="_blank"><img src="/images/facebook.png"></a>
          <a href=""><img src="/images/instagram.png"></a>
          <a href=""><img src="/images/twitter.png"></a>
          
          
        </div>
      </div>

    </div>
  </div>
</template>

<script>

</script>

<style lang="scss">
  .bottom-nav {
    height: 60px;
    background: $grey;
    color: white;

    .fwrapper {
      display: flex;
      margin: 0;
      padding: 0;
    }

    .footer {
      display: flex;
      height: 60px;
      width: 33%;
      
      

      .footer-content {
        display: flex;
        height: 60px;
        margin: auto;
        align-items: center;

        p {
          font-size: 15px;
        }

        h3 {
          font-size: 30px;
        }

        img {
          height: 30px;
          padding-right: 20px;
        }
      }
    }
  }
</style>