<template lang="html">
  <div class="adobe-toolbar">
    <slot></slot>
  </div>
</template>

<script>
export default {
  data() {
    return {

    }
  },
  methods: {
    
  },
}
</script>

<style lang="css">
.adobe-toolbar {
  margin: .5rem 2%;
  display: flex;
  flex-wrap: wrap;
  justify-content: flex-start;
  align-items: center;
}

</style>
