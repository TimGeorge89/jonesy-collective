<template lang="html">
  <div class="nav">
    <!-- NAV BAR -->
    <div class="nav-container">
      <div class="logo">
        <img src="images/jonesycollectivecat.jpg" alt="">
        <h3>Jonesy Collective</h3>
      </div>
      <div class="navigation">
        <ul>
          <li>
            <router-link to="/">Home</router-link>
          </li>
          <li>
            <router-link to="/about">About</router-link>
          </li>
          <li>
            <router-link to="/connect">Connect</router-link>
          </li>
          <li>
            <a href="#">JC Artists</a>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>

</script>

<style lang="scss">
  .nav-container {
  display: flex;
  background-color: $grey;
  color: white;
  padding: 8px;

  .logo {
    display: flex;
    align-self: center;
    margin-left: 10px;

    img {
      border-radius: 50px;
      max-width: 50px;
    }

    h3 {
      align-self: center;
      margin-left: 20px;
    }
  }

  .navigation {
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
  }
}
</style>