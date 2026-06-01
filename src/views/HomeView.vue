<template>
  <main>
    <!-- carousel -->
    <Showcase4Boxes title="Most popular" :boxes="mostPopularDonut" />
    <Showcase4Boxes title="New Donuts" :boxes="newDonut" />
    <!-- some text -->

    <Showcase4Boxes title="Mini Donuts" :boxes="miniDonut" />
    <Showcase4Boxes title="Alligic Donuts" :boxes="allergicDonut" />
  </main>
</template>

<script setup lang="ts">
import Showcase4Boxes from '../components/Showcase4Boxes.vue'

const mostPopularDonut = [
  {
    image:
      'https://res.cloudinary.com/llbg/image/fetch/dpr_2.0,c_fill,g_center,f_avif,q_auto,fl_progressive,w_648,h_484/d_default-image-llbg-logo_pngnpe.png/https://dammanager.llbg.com/digizuitecore/legacyservice/api/assetstream/19122/50475',
    title: 'Raspberry Jam',
    description: 'The Raspberry Jam donut from La Larraine Bakery Group',
  },
  {
    image:
      'https://res.cloudinary.com/llbg/image/fetch/dpr_2.0,c_fill,g_center,f_avif,q_auto,fl_progressive,w_648,h_484/d_default-image-llbg-logo_pngnpe.png/https://dammanager.llbg.com/digizuitecore/legacyservice/api/assetstream/19113/50475',
    title: 'Holy choc',
    description: 'The Holy choc donut from La Larraine Bakery Group',
  },
  {
    image:
      'https://res.cloudinary.com/llbg/image/fetch/dpr_2.0,c_fill,g_center,f_avif,q_auto,fl_progressive,w_648,h_484/d_default-image-llbg-logo_pngnpe.png/https://dammanager.llbg.com/digizuitecore/legacyservice/api/assetstream/21148/50475',
    title: 'Cupidoh',
    description: 'The Cupidoh donut from La Larraine Bakery Group',
  },
]

const newDonut = [
  {
    image:
      'https://res.cloudinary.com/llbg/image/fetch/dpr_2.0,c_fill,g_center,f_avif,q_auto,fl_progressive,w_648,h_484/d_default-image-llbg-logo_pngnpe.png/https://dammanager.llbg.com/digizuitecore/legacyservice/api/assetstream/23850/50475',
    title: 'Dubai Diva',
    description: 'The Dubai Diva donut from La Larraine Bakery Group',
  },
  {
    image:
      'https://res.cloudinary.com/llbg/image/fetch/dpr_2.0,c_fill,g_center,f_avif,q_auto,fl_progressive,w_648,h_484/d_default-image-llbg-logo_pngnpe.png/https://dammanager.llbg.com/digizuitecore/legacyservice/api/assetstream/19109/50475',
    title: 'Lemon Squeezy',
    description: 'The Lemon Squeezy donut from La Larraine Bakery Group',
  },
  {
    image:
      'https://res.cloudinary.com/llbg/image/fetch/dpr_2.0,c_fill,g_center,f_avif,q_auto,fl_progressive,w_648,h_484/d_default-image-llbg-logo_pngnpe.png/https://dammanager.llbg.com/digizuitecore/legacyservice/api/assetstream/19199/50475',
    title: 'Strawjelly jam',
    description: 'The Strawjelly jam donut from La Larraine Bakery Group',
  },
]

const miniDonut = [
  {
    image:
      'https://res.cloudinary.com/llbg/image/fetch/dpr_2.0,c_fill,g_center,f_avif,q_auto,fl_progressive,w_648,h_484/d_default-image-llbg-logo_pngnpe.png/https://dammanager.llbg.com/digizuitecore/legacyservice/api/assetstream/19091/50475',
    title: 'Willamon Tell',
    description: 'The Willamon Tell donut from La Larraine Bakery Group',
  },
  {
    image:
      'https://res.cloudinary.com/llbg/image/fetch/dpr_2.0,c_fill,g_center,f_avif,q_auto,fl_progressive,w_648,h_484/d_default-image-llbg-logo_pngnpe.png/https://dammanager.llbg.com/digizuitecore/legacyservice/api/assetstream/26684/50475',
    title: 'Dark color spinkles',
    description: 'The Dark color spinkles donut from La Larraine Bakery Group',
  },
  {
    image:
      'https://res.cloudinary.com/llbg/image/fetch/dpr_2.0,c_fill,g_center,f_avif,q_auto,fl_progressive,w_648,h_484/d_default-image-llbg-logo_pngnpe.png/https://dammanager.llbg.com/digizuitecore/legacyservice/api/assetstream/26682/50475',
    title: 'Pink color spinkles',
    description: 'The Pink color spinkles donut from La Larraine Bakery Group',
  },
]

const allergicDonut = [
  {
    image:
      'https://res.cloudinary.com/llbg/image/fetch/dpr_2.0,c_fill,g_center,f_avif,q_auto,fl_progressive,w_648,h_484/d_default-image-llbg-logo_pngnpe.png/https://dammanager.llbg.com/digizuitecore/legacyservice/api/assetstream/26679/50475',
    title: 'Cinnamonsta',
    description: 'The Cinnamonsta donut from La Larraine Bakery Group',
  },
  {
    image:
      'https://res.cloudinary.com/llbg/image/fetch/dpr_2.0,c_fill,g_center,f_avif,q_auto,fl_progressive,w_648,h_484/d_default-image-llbg-logo_pngnpe.png/https://dammanager.llbg.com/digizuitecore/legacyservice/api/assetstream/19098/50475',
    title: 'Passonista',
    description: 'The Passonista donut from La Larraine Bakery Group',
  },
  {
    image:
      'https://res.cloudinary.com/llbg/image/fetch/dpr_2.0,c_fill,g_center,f_avif,q_auto,fl_progressive,w_648,h_484/d_default-image-llbg-logo_pngnpe.png/https://dammanager.llbg.com/digizuitecore/legacyservice/api/assetstream/19218/50475',
    title: 'Candy white',
    description: 'The Candy white donut from La Larraine Bakery Group',
  },
]
</script>
