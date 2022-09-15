<template>
  <v-app>
    <SimpleMenu/>
    <!-- <Heading Heading="Data Table of Employee"/> -->
    <!-- <DataTable/> -->
    <!-- <Heading Heading="Date Picker"/> -->
    <!-- <DatePicker /> -->
    <!-- <SimpleTable/> -->
  </v-app>
</template>

<script>

// import DataTable from './components/DataTable.vue';
// import Heading from './components/Heading.vue';
import SimpleMenu from './components/SimpleMenu.vue';
// import DatePicker from './components/DatePicker.vue';
// import SimpleTable from './components/SimpleTable.vue';

export default {
  name: 'App',

  components: {
    // Heading,
    // DataTable,
    SimpleMenu
},

  data: () => ({
    //
  }),
};
</script>
