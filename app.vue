<!--konfigurator: 

-zwei main container -> zeilen container und spalten container
- zwei main objekte -> Zeile und Spalte

-->





<script setup lang="ts">
import RowObject from './components/RowObject.vue';
import Matrix from './components/Matrix.vue';
import { ref } from 'vue'
const props = defineProps({
    zylindernr: Object // Hier definieren Sie den Typ der `row`-Prop
  })
</script>
  
 
 
<template>
  
  <Matrix/>
</template>
 
 