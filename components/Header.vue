  <template>
  <vs-navbar
    padding-scroll
    center-collapsed
    shadow
    notLine
    text-dark
    color="white"
    v-model="active"
  >
    <template #left>
      <h4 @click="goHome">PokeDex</h4>
    </template>
    <vs-navbar-item to="/"> Home </vs-navbar-item>
    <vs-navbar-item to="/types"> Types </vs-navbar-item>
    <vs-navbar-item to="/species"> Species </vs-navbar-item>

    <template #right>
      <vs-button flat href="/about" color="primary">About</vs-button>
    </template>
  </vs-navbar>
</template>

<script>
export default {
  data: {
    active: null,
  },
  methods: {
    goHome() {
      this.$router.push('/')
    },
  },
}
</script>