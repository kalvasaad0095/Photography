<template>
  <v-container
    id="about"
    class="pa-0"
    fluid
    tag="section"
  >
    <v-row
      class="ma-0"
      no-gutters
    >
      <v-col
        cols="12"
        md="6"
      >
        <v-img
          height="calc(100vh - 96px - 156px)"
          gradient="to top, rgba(0, 0, 0, .7), rgba(0, 0, 0, .6)"
          src="https://images.unsplash.com/photo-1554136545-2f288e8cf4bb?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1351&q=80"
        />
      </v-col>

      <v-col
        class="d-block d-md-flex align-center grey lighten-3 pa-6"
        cols="12"
        md="6"
      >
        <v-responsive
          class="mx-auto px-3 px-md-12"
          max-width="750"
        >
          <h1
            class="mb-6"
            :class="$vuetify.breakpoint.mdAndUp ? 'display-2' : 'display-1'"
          >
            Tere! Olen Krista.<br>
            Mulle meeldib pildistada.
          </h1>

          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Consequatur recusandae esse, vel commodi rem similique totam quis, corrupti rerum veritatis numquam ipsa, nam explicabo nulla! Accusamus deserunt repellendus perspiciatis nulla.
          </p>

          <p>
            Nulla, porro? Quos architecto vero itaque temporibus in illo nam perferendis ex nemo distinctio?
          </p>

          <div class="signature">
            Krista Karro
          </div>
        </v-responsive>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
  export default {
    name: 'About',
  }
</script>

<style lang="sass">
  .signature
    font-family: 'Cedarville Cursive', cursive !important
    font-size: 2rem
    font-style: italic
</style>
