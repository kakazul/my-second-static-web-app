<template>
  <div>
    Hello {{ value }}
    <div>
      <a href="/.auth/login/b2c">Login</a>
    </div>
    <div>
      <a href="/.auth/me">My Info</a>
    </div>
    <div>
      <a href="https://b2adaldesktopapps.b2clogin.com/b2adaldesktopapps.onmicrosoft.com/B2C_1_susi/oauth2/v2.0/logout?post_logout_redirect_uri=https://lively-flower-07afe6200.azurestaticapps.net/.auth/logout">Logout</a>
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      value: "World",
    };
  },
};
</script>
