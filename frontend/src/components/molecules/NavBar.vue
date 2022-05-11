<template>
  <nav class="nav-bar">
    <NavItem text="Serviços" to="/servico" />
    <NavItem text="Sobre mim" to="/sobre mim" />
    <NavItem text="Cases" to="casos" />
    <NavItem text="Contato" to="contato" />
  </nav>
</template>

<script lang="ts">
import { defineComponent } from "vue"
import { NavItem } from "@/components/atoms"

export default defineComponent({
  components: { NavItem }
})
</script>

<style lang="scss" scoped>
.nav-bar {
  width: max-content;
  display: grid;
  grid-auto-flow: column;
  grid-gap: 2rem;
}
</style>
