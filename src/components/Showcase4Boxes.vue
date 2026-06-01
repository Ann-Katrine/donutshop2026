<template>
  <div class="flex justify-center">
    <div>
      <h2>{{ title }}</h2>
      <div class="flex flex-row gap-x-24">
        <img
          v-for="box in boxes"
          :key="box.image"
          :src="box.image"
          :alt="box.title"
          height="50"
          width="350"
        />
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
interface Showcase4BoxesProps {
  title: string
  boxes: Box[]
}

interface Box {
  image: string
  title: string
  description: string
}

defineProps<Showcase4BoxesProps>()
</script>
