

<template>
  <div class="card flex justify-center">
      <DatePicker v-model="date" />
  </div>
</template>

<script setup>
import { ref } from "vue";
import DatePicker from 'primevue/datepicker';

const date = ref();
</script>
