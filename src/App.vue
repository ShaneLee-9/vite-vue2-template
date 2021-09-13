<template>
  <div>
    <input v-model="msg" type="text">
    <p>{{ msg }}</p>
  </div>
</template>

<!-- <script lang="ts">
import { ref, defineComponent } from '@vue/composition-api'


export default defineComponent({
  setup() {
    const msg = ref('')

    return {
      msg
    }
  }
})
</script> -->

<script setup lang="ts">
import { ref } from "@vue/composition-api";

const msg = ref('')
</script>