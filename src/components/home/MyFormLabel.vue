<template>
    <span :class="'text-' + lableClass">
      {{ textLength }} / {{ maximumLength }}
    </span>
  </template>
   
  <script>
  export default {
    name: 'MyFormLabel',
    props: {
      lableClass: String,
      maximumLength: Number,
      textLength: Number
    }
  }
  </script>
   
  <style scoped>
      span {
          margin-bottom: 4px;
      }
  </style>