<template>
  
  <!-- BEGIN - Primary application deck -->
  <div id="flow-deck">
    
      <!-- BEGIN - Flow Title banner -->
      <div id="flow-start-message" class="notification is-dark has-text-centered is-static is-active" readonly>
        <p>Choose Your Adventure: <b>3rd Party IMAP</b></p>
      </div> 
      <!-- END - Flow Title banner -->

    <!-- BEGIN section -->
    <div class="content has-text-centered" id="flow">

      <div class="content is-medium">
        <p>Are the domains related to each other or a part of the same business? (do they need to be a part of the same organization?)</p>
      </div>

      <p class="buttons">

        <router-link to="/flow/prod/cya/other/imap/iNmY" class="button is-light">
          <span class="icon has-text-success">
            <i id="itcolor" class="fas fa-chevron-circle-right"></i>
          </span>
          <span><b>Yes</b>. The domains are related.</span>
        </router-link>
      
        <router-link to="/flow/prod/cya/other/imap/iNmN" class="button is-light">
          <span class="icon has-text-danger">
            <i id="itcolor" class="fas fa-chevron-circle-right"></i>
          </span>
          <span><b>No</b>. The domains are not related.</span>
        </router-link>

      </p>
      
      <!-- BEGIN - Back button -->
      <p class="buttons">
        <router-link to="/flow/prod/cya/other/imap/iN" class="button is-small is-info">
          <span class="icon has-text-light">
            <i class="fas fa-chevron-left"></i>
          </span>
          <span>BACK</span>
        </router-link>
      </p>
      <!-- END - Back button -->

      <router-view/>

    </div>
    <!-- END flow section -->

  </div>
  <!-- END - Primary application deck -->
    
</template>

<script>

</script>

<style></style>