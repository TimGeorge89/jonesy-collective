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
            <a href="#">Home</a>
          </li>
          <li>
            <a href="#">About</a>
          </li>
          <li>
            <a href="#">Connect</a>
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
  padding: 8px;
  border-bottom: 2px black solid;

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
      }
    }
  }
}
</style>