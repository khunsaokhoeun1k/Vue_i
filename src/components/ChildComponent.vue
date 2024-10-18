<template>
    <h1>{{message}}</h1>
    <!-- <h2>{{ type }}</h2> -->
    <p>
      For a guide and recipes on how to configure / My  project,<br>
      check out the
      <a href="#">laravel documentation</a>.
    </p>
    <h2>Installe documentation </h2>
</template>

<script>
 export default {
  name: 'ChildComponent',
  props: {
    message:String,
    // type:String
  }
}
</script>