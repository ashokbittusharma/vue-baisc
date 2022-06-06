<template>
  <h1>{{title}}</h1>
</template>

<script>

export default {
  data(){
    return{
      title : 'My ToDo App',
      task : [
        {id: 1, name: "vue version1", finished : false},
        {id: 2, name: "vue version2", finished : false},
        {id: 3, name: "vue version3", finished : false},
      ]
    }
  }
}
</script>