<template>
  <div class="services">
    <Service
      title="Front End"
      description="Lorem, ipsum dolor sit amet consectetur adipisicing elit. Deleniti doloremque inventore maxime voluptate illo corrupti itaque? Nobis sed neque, ratione nihil deleniti adipisci natus, recusandae pariatur quibusdam cumque excepturi libero"
    />

    <Service
      title="Back End"
      description="Lorem, ipsum dolor sit amet consectetur adipisicing elit. Deleniti doloremque inventore maxime voluptate illo corrupti itaque? Nobis sed neque, ratione nihil deleniti adipisci natus, recusandae pariatur quibusdam cumque excepturi libero"
    />

    <Service
      title="Manutenção"
      description="Lorem, ipsum dolor sit amet consectetur adipisicing elit. Deleniti doloremque inventore maxime voluptate illo corrupti itaque? Nobis sed neque, ratione nihil deleniti adipisci natus, recusandae pariatur quibusdam cumque excepturi libero"
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

<style lang="scss" scoped>
.services {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 5rem;
}
</style>
