<template lang="html">
  <div class="nav">
    <!-- NAV CONTAINER -->
    <div class="nav-container">
      <!-- LOGO -->
      <div class="logo">
        <div class="logo-container">
          <img src="images/jonesycollectivecat.jpg" alt="">
        </div>
        <h3>Jonesy Collective</h3>
      </div>
      <!-- NAVIGATION -->
      <div v-bind:class="{ active: isActive }" class="navigation">
        <ul>
          <li>
            <router-link @click.native="toggle()" to="/">Home</router-link>
          </li>
          <li>
            <router-link @click.native="toggle()" to="/about">About</router-link>
          </li>
          <li>
            <router-link @click.native="toggle()" to="/connect">Connect</router-link>
          </li>
          <li>
            <a href="#">JC Artists</a>
          </li>
        </ul>
      </div>
       <!-- MOBILE NAV -->
      <a @click="toggle()" class="burger">
        <div class="line1"></div>
        <div class="line2"></div>
        <div class="line3"></div>
      </a>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      isActive: false
    }
  },
  methods: {
    toggle() {
      this.isActive = !this.isActive
    }
  }
}
</script>

<style lang="scss">

  .nav-container {
    display: flex;
    background-color: $grey;
    color: white;
    padding: 11px;

    .logo {
      display: flex;
      align-self: center;
      margin-left: 10px;

      .logo-container {
        
        img {
        border-radius: 50px;
        // object-fit: contain;
        max-width: 50px;
      }
      }

      h3 {
        align-self: center;
        margin-left: 20px;
      }
    }

    .navigation {
      display: block;
      margin-left: auto;
      align-self: center;
      font-size: 20px;

      ul {
        display: flex;
        list-style: none;

        li {
        margin-right: 15px;

        a {
          font-size: 20px;
        }

        .router-link-exact-active {
          color: $light-green;
          position: relative;

          &:after {
            content: '';
            position: absolute;
            left: 0;
            right: 0;
            bottom: -3px;
            height: 3px;
            background: $light-green;

          }
        }
      }
    }

    .burger {
      display: none;
    }
  }

  @media screen and (max-width: 700px) {
    
    .navigation {
      // display: none;
      position: absolute;
      right: -200px;
      // height: auto;
      top: 7vh;
      background-color: $grey;
      transition: 0.15s ease-in;

      ul {
        display: flex;
        flex-direction: column;
        margin: 20px 30px;
        text-align: center;

        li {
          margin-bottom: 28px;
          margin-left: 10px;
        }
          
      }
    }

    .active {
      right: 0;
    }

    .burger {
      display: inline-block;
      margin-left: auto;
      align-self: center;

      &:hover {
        cursor: pointer;
      }

        
      div {
        width: 25px;
        height: 3px;
        background-color: white;
        margin: 5px;
      }
    }
  }
}
</style>