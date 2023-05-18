<template>
    <div class="login">
        <h1>Sign In</h1>
        <div class="username">
            <p>Username</p>
            <input type="text" placeholder="Username">
        </div>
        <div class="username">
            <p>Password</p>
            <input type="password" placeholder="Password">
        </div>
        <p>Don't have an account? Register <a href="">here</a></p>
    </div>
</template>
<script>
export default {
    name: 'SigninPage'
}
</script>
<style scoped>
   * {
    background: url('https://www.pixelstalk.net/wp-content/uploads/images2/Teal-Background.png');
   }
</style>