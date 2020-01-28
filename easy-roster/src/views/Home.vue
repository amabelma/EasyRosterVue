<template>
  <div>
    <h1>Welcome to EasyRoster!</h1>
    <NavigationTable></NavigationTable>
  </div>
  
</template>

<script>
  import NavigationTable from '../components/Home/NavigationTable';

export default {
  name: 'home',
  components: {
    NavigationTable,
  }
}
</script>
