<template>
  <footer class="footer">
  <div class="container">
    <div class="content has-text-centered">
      <div class="columns">
        <div class="column">
          <strong>Contact</strong>
        </div>
      </div>
      <div class="columns">
        <div class="column">
          <a class="button is-medium is-white" href="https://github.com/struthj">
            <span class="icon">
              <i class="fa fa-github"></i>
            </span>
            <span>GitHub</span>
          </a>
        </div>
          <div class="column">
            <a class="button is-medium is-white" href="mailto:struthj@oregonstate.edu" v-bind:class="{ hover: is-primary }">
            <span class="icon">
              <i class="fa fa-envelope-o"></i>
            </span>
            <span>struthj@oregonstate.edu</span>
          </a>
          </div>
          <div class="column">
            <a class="button is-medium is-white" href="https://linkedin.com/in/jstruth">
            <span class="icon">
              <i class="fa fa-linkedin-square"></i>
            </span>
            <span>LinkedIn</span>
          </a>
          </div>
        </div>
      </div>
  </div>
</footer>
</template>

<script>
export default {
  name: "ContactFooter"
};
</script>

