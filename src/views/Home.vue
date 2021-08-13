<template>
  <div class="w-100">
    <main>
      <Sidebar />
      <div class="dash-container">
        <Navbar />
        <div class="dash-wrapper">
          test
        </div>
      </div>
    </main>
  </div>
</template>

<script>
import Sidebar from './../components/Body/Sidebar.vue'
import Navbar from './../components/Body/Navbar.vue'

export default {
  components: {
    Sidebar, Navbar
  }
}
</script>