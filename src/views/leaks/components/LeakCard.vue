<template>
  <v-card @click="$emit('click')" ripple color="error">
    <v-card-text class="white--text">
      <v-col>
        <v-row align="center">
          <span class="font-weight-bold">
            {{ leak.name }}
          </span>
          <v-spacer></v-spacer>
          <span>01/08/2019</span>
        </v-row>
      </v-col>
    </v-card-text>
  </v-card>
</template>

<script>
export default {
  props: {
    leak: {
      type: Object
    }
  }
}
</script>
