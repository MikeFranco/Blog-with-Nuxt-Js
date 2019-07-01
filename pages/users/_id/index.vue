<template>
  <h1> Just an another page inside "users" page, with ID: {{ $route.params.id }} </h1>
</template>

<script>
export default {
  validate(data){
    console.log(data);
    return /^\d+$/.test(data.params.id)
  },
  layout: 'users'
}
</script>

<style>

</style>
