<template>
  <div class="main-container">
    <h1>PEDIDOS</h1>
    <Dashboard />
  </div>
</template>


<script> 
import { defineComponent } from "vue";
import Dashboard from "@/components/Dashboard.vue";

export default defineComponent({
    name: "Pedidos",
    components: {
      Dashboard 
    }
})
</script>