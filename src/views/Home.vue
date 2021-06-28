<template>
  <v-container>
    <v-row>
      <v-col>
        <v-tabs centered>
          <v-tab> Login </v-tab>
          <v-tab-item class="pa-5">
            <Login></Login>
          </v-tab-item>
          <v-tab> Signup </v-tab>
          <v-tab-item class="pa-5">
            <Signup></Signup>
          </v-tab-item>
        </v-tabs>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
import Login from "../components/Login.vue";
import Signup from "../components/Signup.vue";

export default {
  name: "Home",
  data: () => ({}),
  components: {
    Login,
    Signup,
  },
};
</script>
