<template>
  <div>
    <h4>Oups! There was an error : </h4>
    <p>{{ error }}</p>
  </div>
</template>

<script>
export default {
  props: {
    error: {
      type: String,
      required: true
    }
  }
}
</script>
