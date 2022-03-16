<template>
  <div class="grid grid-cols-4 gap-4">
    <div
      v-for="i in 10"
      :key="i"
      class="bg-blue-700 hover:bg-blue-800 text-center p-4 text-white rounded-lg text-lg ease-out duration-300"
    >
      {{ i }}
    </div>
  </div>
</template>

<script>
export default {
  name: 'TestGrid'
}
</script>
