<template>
  <div class="q-pa-md example-row-equal-width">
    <q-btn push color="teal" label="Change image" @click="refresh" />

    <q-img
      :src="url"
      spinner-color="white"
      style="height: 140px; max-width: 150px"
    />
</div>
</template>

<style>
</style>

<script>
export default {
  name: 'HelloWorld'
}
</script>
