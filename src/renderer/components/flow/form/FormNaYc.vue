<template>
  
  <!-- BEGIN - Primary application deck -->
  <div id="swat-deck">
    
    <!-- BEGIN - Flow Title banner -->
      <div id="flow-start-message" class="notification is-dark has-text-centered is-static is-active" readonly>
        <p><b>Form Mail</b> Error</p>
      </div> 
    <!-- END - Flow Title banner -->

    
    <!-- BEGIN Form mail Error section -->
    <div class="content has-text-centered" id="flow">    
      <div class="notification is-danger">
        <strong>STOP HERE</strong>.
      </div>
      <article class="message is-small is-info">
        <div class="message-body">
          Advise the customer that they need to change the subject line they are using for form mail. Have them send another form mail after they have completed this step.
        </div>
      </article>
      <article class="message is-small is-success">
        <div class="message-body">
          If this is a Wordpress based form mailer offer <strong>WPPS (Wordpress Premium Support)</strong> to help resolve this issue.
        </div>
      </article>

      <!-- BEGIN - Back button -->
        <p class="buttons">
          <router-link to="/flow/form/FormNaY" class="button is-small is-info">
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
    <!-- END Form mail Error section -->

  </div>
  <!-- END - Primary application deck -->
    
</template>

<script>
export default {

}
</script>

<style></style>