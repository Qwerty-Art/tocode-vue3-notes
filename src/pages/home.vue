<template>
  <div class="md-body">
    <Form @onSubmit="handleSubmit"></Form>
  </div>
</template>

<script>
import Form from "@/components/Notes/Form";
export default {
  components: {
    Form
  },
  methods: {
    handleSubmit(note) {
      console.log(note)
    }
  }
}
</script>

<style lang="scss" scoped>
</style>