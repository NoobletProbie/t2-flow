<template>

  <!-- BEGIN - Primary application deck -->
  <div id="swat-deck" class="hello">

    <!-- START - Message of Swat FLow Chart -->
    <div class="content " id="flow-start-message">

      <!-- BEGIN Home page logo section -->
      <div id="logo-main" title="Inbound Flow Tool">
        <img src="../assets/images/gold.png">
      </div>
      <!-- END Home page logo section -->

    </div>

    <!-- BEGIN Start button -->
    <div id="get-start" class="field is-grouped">
      <p class="control">
        <router-link to="/FlowIndex" class="button is-small is-fullwidth is-dark">
          <p><b>SWAT</b> FLOW</p>
        </router-link>
        <br>
        <router-link to="/SwatNote" class="button is-small is-fullwidth is-dark">
          <p><b>SWAT</b> NOTE</p>
        </router-link>
        <br>
        <router-link to="/SwatTools" class="button is-small is-fullwidth is-dark">
          <p><b>SWAT</b> TOOLS</p>
        </router-link>
        <br>
        <router-link to="/SwatLinks" class="button is-small is-fullwidth is-dark">
          <p><b>SWAT</b> LINKS</p>
        </router-link>
      </p>
    </div>
    <!-- END Start button -->

    <!-- BEGIN swat motto statement -->
    <div id="swat-motto">
      <p>"Solve, Wow, Advocate, Transfer."</p>
    </div>
    <!-- END swat motto statement -->

    <!-- END - Message of Swat FLow Chart -->

      <router-view/>

  </div>
  <!-- END - Primary application deck -->

</template>

<script>
export default {

}
</script>

<style></style>
