<template>
  
  <!-- BEGIN - Primary application deck -->
  <div id="flow-deck">
    
      <!-- BEGIN - Flow Title banner -->
      <div id="flow-start-message" class="notification is-dark has-text-centered is-static is-active" readonly>
        <p>Choose Your Adventure: <b>Workspace</b></p>
      </div> 
      <!-- END - Flow Title banner -->

    
    <!-- BEGIN section -->
    <div class="content has-text-centered" id="flow"> 

      <div class="notification is-danger">
        <strong>STOP HERE</strong>.
      </div>

      <article class="message is-info is-small">
        <div class="message-body has-text-left">
          <p>Use the <b>Workspace Migration</b> tab in the <b>MaaS Tool</b> and load the cart for each migrating domain.</p>
          <p>Be sure to process the entire migration on the same receipt.</p>
        </div>
      </article>

      
      <a href="https://wopr.int.secureserver.net/support.services/MigrationLauncher" target="_blank" title="Launch MaaS Tool" class="button is-small is-dark">
        <span class="icon is-medium">
          <i class="far fa-envelope-open"></i>
        </span>
        <span><b>Launch MaaS Tool</b></span>
      </a>
      <br>
      <br>
      
      <!-- BEGIN - Back button -->
      <p class="buttons">
        <router-link to="/flow/prod/cya/wksp/wksYm" class="button is-small is-info">
          <span class="icon has-text-light">
            <i class="fas fa-chevron-left"></i>
          </span>
          <span>BACK</span>
        </router-link>
      </p>
      <!-- END - Back button -->

      <router-link to="/FlowIndex" class="button is-dark is-fullwidth">Return to start</router-link>

      <router-view/>
      
    </div>
    <!-- END section -->

  </div>
  <!-- END - Primary application deck -->
    
</template>

<script>
export default {

}
</script>

<style></style>