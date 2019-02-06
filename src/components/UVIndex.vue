<template>
  <div id="uvindex">
    <p>UV Index: {{ uvindex }}</p>
  </div>
</template>

<script>

export default {
  props: ["highl"],
  data () {
    return {
      uvindex: this.highl.uvindex
    }
  },
  methods: {

  },
  computed: {

  },
}
</script>

<style>

</style>
