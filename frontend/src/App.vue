<template>
  <div class="component">
    <Logo />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue"
import { Logo } from "@/components/atoms"

export default defineComponent({
  components: { Logo }
})
</script>

<style scoped>
.component {
  width: 300px;
}
</style>
