<template>
  <b-navbar toggleable="lg" type="dark" variant="dark" sticky>
    <b-navbar-brand to="/">Gray's Nursery</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
    <b-collapse id="nav-collapse" is-nav>
      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">

        <b-nav-item to="/about">About Us</b-nav-item>
        <b-nav-item to="/Location">Location</b-nav-item>

        <!--
        <b-nav-item-dropdown text="Lang" right>
          <b-dropdown-item href="#">EN</b-dropdown-item>
          <b-dropdown-item href="#">ES</b-dropdown-item>
          <b-dropdown-item href="#">RU</b-dropdown-item>
          <b-dropdown-item href="#">FA</b-dropdown-item>
        </b-nav-item-dropdown>

        <b-nav-item-dropdown right>
           Using 'button-content' slot
          <template #button-content>
            <em>User</em>
          </template>
          <b-dropdown-item href="#">Profile</b-dropdown-item>
          <b-dropdown-item href="#">Sign Out</b-dropdown-item>
        </b-nav-item-dropdown>
        -->
        <b-button title="Facebook">
            <b-icon icon="facebook" aria-hidden="true" @click="goToFacebook()"></b-icon>
        </b-button>
        <b-button title="Load file">
            <b-icon icon="cloud-download" aria-hidden="true"></b-icon>
        </b-button>
        <b-button title="New document">
            <b-icon icon="file-earmark" aria-hidden="true"></b-icon>
        </b-button>

      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>

<script>
export default {
    methods:{
        goToFacebook(){
            window.open("https://www.facebook.com/Grays-Wholesale-Nursery-103254578571278/", '_blank').focus();
        }
    }

    
}
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Amatic+SC&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Roboto&display=swap");

.navbar-dark .navbar-brand {
    font-family: 'Amatic SC', cursive;
    font-size: 2.5em;
    font-weight: bold;
    color: #fff;
}

.navbar-dark .navbar-brand:hover{
    font-size: 2.6rem;
}

.navbar-dark .navbar-nav .nav-link {
    font-family: 'Roboto', sans-serif;
    color: #fff;
}

.navbar-dark .navbar-nav .nav-link:hover  {
    font-size: 1.2rem;
}

.bg-dark {
    background-color: #506369!important;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}

.btn-secondary {
    color: #fff;
    background-color: #506369!important;
    border-color: #506369;
}

</style>
