<template>
  
  <!-- BEGIN - Primary application deck -->
  <div id="swat-deck">
    
    <!-- BEGIN - Flow Title banner -->
      <div id="flow-start-message" class="notification is-dark has-text-centered is-static is-active" readonly>
        <p><b>Form Mail</b> Error</p>
      </div> 
    <!-- END - Flow Title banner -->

    
    <!-- BEGIN Form mail Error flow section -->
    <div class="content has-text-centered" id="flow">
      <div class="content is-medium">
        <p>What did <strong>Splunk</strong> show as a result for this email?</p>
      </div>
      <p class="buttons">
          <router-link to="/flow/form/FormNaYa" class="button is-light">
            <span class="icon has-text-warning">
              <i class="fas fa-exclamation-triangle"></i>
            </span>
            <span>Email shows as <strong>CMAE-SPAM</strong></span>
          </router-link>  
          <router-link to="/flow/form/FormNaYb" class="button is-light">
            <span class="icon has-text-warning">
              <i class="fas fa-exclamation-triangle"></i>
            </span>
            <span>Email shows as <strong>Accept/Delivered</strong></span>
          </router-link>
          <router-link to="/flow/form/FormNaYc" class="button is-light">
            <span class="icon has-text-warning">
              <i class="fas fa-exclamation-triangle"></i>
            </span>
            <span>Email shows <strong>Bad-Subject</strong></span>
          </router-link>
        </p>
      
        <!-- BEGIN - Back button -->
        <p class="buttons">
          <router-link to="/flow/form/FormNa" class="button is-small is-info">
            <span class="icon has-text-light">
              <i class="fas fa-chevron-left"></i>
            </span>
            <span>BACK</span>
          </router-link>
        </p>
        <!-- END - Back button -->

      <router-view/>
    </div>
    <!-- END Form mail Error flow section -->

  </div>
  <!-- END - Primary application deck -->
    
</template>

<script>
export default {
  
}
</script>

<style></style>