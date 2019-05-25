  <template>
  <div class="home">
    <h1>Home page</h1>

    <v-btn class="pink white--text">getting started</v-btn>
    <v-btn dark depressed color="pink">click me</v-btn>
    <v-btn flat color="pink">Click me</v-btn>

    <!-- marterial design icon -->
    <v-btn depressed class="pink white--text">
      <v-icon left>email</v-icon>
      <span>Email me</span>
    </v-btn>

    <v-btn depressed color="pink white--text" small>
      <v-icon left small>alarm</v-icon>
      <span>Clock</span>
    </v-btn>

    <v-btn depressed color="pink white--text" large>
      <span>Clock</span>
      <v-icon right large>android</v-icon>

    </v-btn>

    <v-btn fab flat dark color="purple"> 
      <v-icon>favorite</v-icon>
    </v-btn>


  </div>
</template>

  <script>
export default {
  components: {}
};
</script>
