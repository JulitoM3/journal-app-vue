<template>
  <nav class="navbar bg-primary">
    <a href="" class="navbar-brand text-white">
      <img src="@/assets/logo.png"
           class="d-inline-block align-text-top mx-2"
           alt="Vue logo"
           height="24"
      >
      DayBook
    </a>
    <div class="d-flex">
      <button class="btn btn-outline-info mx-2">
        <i class="fa fa-sign-out-alt"></i>
        Logout
      </button>
    </div>
  </nav>
</template>

<script>
export default {
  name: "NavBar"
}
</script>

<style scoped>

</style>