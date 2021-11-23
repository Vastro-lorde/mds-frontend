<template>
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/news">News</router-link> |
    <router-link to="/about">About</router-link> |
    <router-link to="/login">Login</router-link> |
    <router-link to="/profile">Profile</router-link>
  </div>
  <router-view/>
  <footer class="text-white text-center text-lg-start " style="background-color: #414d6f;">
    <!-- Grid container -->
    <div class="container p-4">
      <!--Grid row-->
      <div class="row mt-4">
        <!--Grid column-->
        <div class="col-lg-4 col-md-12 mb-4 mb-md-0">
          <h5 class="text-uppercase mb-4">About Our School</h5>

          <p>
            At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium
            voluptatum deleniti atque corrupti. <a href="/about">more..</a>
          </p>

          <p>
            Blanditiis praesentium voluptatum deleniti atque corrupti quos dolores et quas
            molestias.
          </p>

          <div class="mt-4" style="color: #f4e534">
            <!-- Facebook -->
            <a type="button" class="btn btn-floating btn-danger btn-lg" href="https://www.facebook.com/Mater-Dei-College-101146149060499/" target="_blank">Facebook<i class="fab fa-facebook-f"></i></a>
            <!-- Gmail materdeicollege35@gmail.com-->
            <a type="button" class="btn btn-floating btn-danger btn-lg" href="mailto:materdeicollege35@gmail.com" target="_blank">Gmail<i class="fab fa-google-plus-g"></i></a>
          </div>
        </div>
        <!--Grid column-->

        <!--Grid column-->
        <div class="col-lg-4 col-md-6 mb-4 mb-md-0">

          <ul class="fa-ul" >
            <li class="mb-3">
              <span class="fa-li"><i class="fas fa-home"></i></span><span class="ms-2">Ashaka, Delta State, Nigeria</span>
            </li>
            <li class="mb-3">
              <span class="fa-li"><i class="fas fa-envelope"></i></span><span class="ms-2">info@example.com</span>
            </li>
            <li class="mb-3">
              <span class="fa-li"><i class="fas fa-phone"></i></span><span class="ms-2"><a href="tel:+2348033813025">+2348033813025</a></span>
            </li>
            <li class="mb-3">
              <span class="fa-li"><i class="fas fa-print"></i></span><span class="ms-2"><a href="tel:+2348134149257">+2348134149257</a></span>
            </li>
          </ul>
        </div>
        <!--Grid column-->

        <!--Grid column-->
        <div class="col-lg-4 col-md-6 mb-4 mb-md-0">
          <h5 class="text-uppercase mb-4">Opening hours</h5>

          <table class="table text-center text-white">
            <tbody class="font-weight-normal">
              <tr>
                <td>Mon - Thu:</td>
                <td>8am - 9pm</td>
              </tr>
              <tr>
                <td>Fri - Sat:</td>
                <td>8am - 1am</td>
              </tr>
              <tr>
                <td>Sunday:</td>
                <td>9am - 10pm</td>
              </tr>
            </tbody>
          </table>
        </div>
        <!--Grid column-->
      </div>
      <!--Grid row-->
    </div>
    <!-- Grid container -->

    <!-- Copyright -->
    <div class="text-center p-3" style="background-color: #313b56;">
      © 2021 Copyright:
      <a class="text-white" href="">Mater Dei College</a>
    </div>
    <!-- Copyright -->
  </footer>
</template>
<script>

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 5px;
  margin-bottom: 50px;
  margin-right: 1%;
  margin-top: 1%;
  text-align: right;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #F5E434;
}

</style>
