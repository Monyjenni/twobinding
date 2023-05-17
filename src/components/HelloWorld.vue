<!-- view part -->
<template>
  <div>
    <h1>Yoo</h1>
    <!-- {{  }} is used to print the data -->
    <h2>{{ data }}</h2>
    <input type="text" v-model="data" />
  </div>
</template>

<!-- model part__will be changed, reflect and update -->
<script>
export default {
  //name should has multi wordss
  name: "JennieProfile",
  // return properties
  data() {
    return {
      data:0,
    };
  },
};
</script>
