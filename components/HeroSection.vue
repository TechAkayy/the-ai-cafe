<script setup lang="ts">
  // const props = defineProps({
  // 	name: {
  // 		type: String,
  // 		default: 'HeroSection',
  // 	},
  // })

  // const emit = defineEmits(['addToCart'])

  // // Use the addToCart function like this:
  // // Eg-1: addToCart('pizza', 10)
  // // Eg-2: (event) => addToCart('pizza', 10, event)
  // const addToCart = (item, quantity /*, event*/) => {
  // 	emit('addToCart', { item, quantity })
  // }
</script>
<template>
  <v-carousel>
    <v-carousel-item
      src="https://images.unsplash.com/photo-1511920170033-f8396924c348?ixid=M3wyMDkyMnwwfDF8c2VhcmNofDl8fGNhZmV8ZW58MHx8fHwxNjk5Njc4NDEyfDA&ixlib=rb-4.0.3q=85&fm=jpg&crop=faces&cs=srgb&w=1200&h=800&fit=crop"
      cover
    ></v-carousel-item>
    <v-carousel-item
      src="https://images.unsplash.com/photo-1534040385115-33dcb3acba5b?ixid=M3wyMDkyMnwwfDF8c2VhcmNofDE0fHxjYWZlfGVufDB8fHx8MTY5OTY3ODQxMnww&ixlib=rb-4.0.3q=85&fm=jpg&crop=faces&cs=srgb&w=1200&h=800&fit=crop"
      cover
    ></v-carousel-item>
    <v-carousel-item
      src="https://images.unsplash.com/photo-1495474472287-4d71bcdd2085?ixid=M3wyMDkyMnwwfDF8c2VhcmNofDh8fGNhZmV8ZW58MHx8fHwxNjk5Njc4NDEyfDA&ixlib=rb-4.0.3q=85&fm=jpg&crop=faces&cs=srgb&w=1200&h=800&fit=crop"
      cover
    ></v-carousel-item>
  </v-carousel>
</template>
<style scoped></style>
