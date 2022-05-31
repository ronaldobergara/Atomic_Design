<template>
  <div class="component">
    <Service
      title="Front End"
      description="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Corporis numquam optio ipsam rerum culpa voluptas blanditiis incidunt eum, temporibus accusamus mollitia. Eos quos ratione debitis dicta expedita quis molestias quia."
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue"
import { Service } from "@/components/molecules"

export default defineComponent({
  components: { Service }
})
</script>

<style scoped>
.component {
  margin: 5rem;
}
</style>
