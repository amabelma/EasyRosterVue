<template>
  <div>
    <HeaderBar></HeaderBar>
    <h1>Welcome to EasyRoster!</h1>
    <NavigationTable></NavigationTable>
  </div>
</template>

<script>
import NavigationTable from "../components/Home/NavigationTable";
import HeaderBar from "../components/Header/HeaderBar";

export default {
  name: "home",
  components: {
    NavigationTable,
    HeaderBar
  }
};
</script>
