<template>
  
  <!-- BEGIN - Primary application deck -->
  <div id="flow-deck">
    
    <!-- START Opening comments for Swat Flow Chart -->
    <div id="flow-start-message" class="notification is-dark has-text-centered is-static is-active" readonly>
        <center><p><b>Flow</b> Guide</p></center>
    </div>
    <!-- END Opening comments for Swat Flow Chart -->

    <!-- BEGIN Error flow section -->
    <div class="content has-text-centered" id="flow">
      <div class="content is-medium">
        <p>Here are your recommended call flows.</p>
      </div>
      <p class="buttons"> 
        <router-link to="/flow/howto/Wp" class="button is-dark is-small">
          <span class="icon has-text-success">
            <img src="../../../assets/icons/png/blu16.png"/>
          </span>
          <span><b>WordPress</b> Support</span>
        </router-link>
        <router-link to="/flow/FiveError" class="button is-dark is-small">
          <span class="icon has-text-success">
            <img src="../../../assets/icons/png/blu16.png"/>
          </span>
          <span><b>500</b> Error</span>
        </router-link>
      </p>

      <!-- BEGIN - Back button -->
      <p class="buttons">
        <router-link to="/flow/guide/GwL" class="button is-small is-info">
          <span class="icon has-text-light">
            <i class="fas fa-chevron-left"></i>
          </span>
          <span>BACK</span>
        </router-link>
      </p>
      <!-- END - Back button -->
      

      <router-view/>

    </div>
    <!-- END Error flow section -->

  </div>
  <!-- END - Primary application deck -->
    
</template>

<script>
export default {
  
}
</script>

<style></style>