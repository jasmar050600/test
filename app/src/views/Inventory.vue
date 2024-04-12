<script setup>
import InventoryTable from "./components/InventoryTable.vue";
import SuppliersTable from "./components/SuppliersTable.vue";
</script>
<template>
  <div class="py-4 container-fluid">
    <div class="row">
      <div class="col-12">
        <inventory-table />
      </div>
    </div>
    <div class="mt-4 row">
      <div class="col-12">
        <suppliers-table />
      </div>
    </div>
  </div>
</template>
