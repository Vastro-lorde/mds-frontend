<template>
  <div id="login-form">
        
        <form method="get" action="">
            <div class="form-group">
                <label for="email">Email address</label>
                <input type="email" class="form-control" id="email" aria-describedby="emailHelp" placeholder="Enter email" required>
                <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
            </div>
            <div class="form-group">
                <label for="password">Password</label>
                <input type="password" class="form-control" id="password" placeholder="Password" required>
            </div>
            <p>{{msg}}</p>
            <button type="submit" class="btn btn-success">Login</button>
        </form>
</div>
</template>

<script>

export default {
  name: 'loginForm',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
#login-form {
    background-color: rgb(204, 255, 237);
    margin: auto;
    margin-bottom: 5%;
    padding: 1%;
    width: 30%;
}
</style>
