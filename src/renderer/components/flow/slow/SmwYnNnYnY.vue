<template>
  
  <!-- BEGIN - Primary application deck -->
  <div id="swat-deck">
    
    <!-- BEGIN - Flow Title banner -->
      <div id="flow-start-message" class="notification is-dark has-text-centered is-static is-active" readonly>
        <p><b>Slow</b> Site</p>
      </div> 
    <!-- END - Flow Title banner -->

    <!-- BEGIN Net Vio flow section -->
    <div class="content has-text-centered" id="flow">

      <div class="content is-medium">
        <p>Turn on debug mode. Are any issues displayed on site now?</p>
      </div>

      <p class="buttons">
        <router-link to="/flow/slow/SmwYnNnYnYy" class="button is-light">
          <span class="icon has-text-success">
            <i class="fas fa-check-circle"></i>
          </span>
          <span><b>Yes.</b> There are errors.</span>
        </router-link>  
        <router-link to="/flow/slow/SmwYnNnYnYn" class="button is-light">
          <span class="icon has-text-danger">
            <i class="fas fa-check-circle"></i>
          </span>
          <span><b>No.</b> There are no errors.</span>
        </router-link>
      </p>
      
      <!-- BEGIN - Back button -->
      <p class="buttons">
        <router-link to="/flow/slow/SmwYnNnYn" class="button is-small is-info">
          <span class="icon has-text-light">
            <i class="fas fa-chevron-left"></i>
          </span>
          <span>BACK</span>
        </router-link>
      </p>
      <!-- END - Back button -->

      <router-view/>

    </div>
    <!-- END Net Vio flow section -->

  </div>
  <!-- END - Primary application deck -->
    
</template>

<script>

</script>

<style></style>