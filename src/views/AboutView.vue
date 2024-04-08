<template>
  <div class="about">
    <!-- <form class="pure-form">
      <fieldset>
        <legend>Confirm password with HTML5</legend>

        <input type="password" placeholder="Password" id="password" required />
        <input type="password" placeholder="Confirm Password" id="confirm_password" required />

        <button type="submit" class="pure-button pure-button-primary">Confirm</button>
      </fieldset>
    </form> -->
    <v-container>
      <v-form>
        <v-text-field
          class="block"
          label="Password"
          type="password"
          autocomplete="new-password"
        ></v-text-field>
        <v-text-field
          class="block"
          label="Confirm password"
          type="password"
          autocomplete="new-password"
        ></v-text-field>
        <!-- <v-text-field label="test"></v-text-field> -->
      </v-form>
    </v-container>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
  .block {
    display: inline-block;
    width: 200px;
    padding-left: 10px;
  }
}
</style>
