<template>
  <div class="home">
    <section class="flex flex-col sm:flex-row items-center justify-content-between md:mt-8 mx-auto">
      <div class="mb-4">
        <h1 class="text-2xl ml-6 md:text-6xl mt-8 p-2">Welcome to Proserve</h1>
      </div>
      <div class="w-full md:w-6/12">
        <img :src="require('@/assets/tools.jpeg')" alt="">
      </div>
    </section>
    <section class="mt-10 p-4">
      <div class="my-6">
        <h2 class="text-3xl">Premium Property Maintenance</h2>
      </div>
      <div class="flex flex-col md:flex-row items-center mx-auto justify-between p-4 w-full">
        <div class="text w-full md:w-6/12">
          <p class="p-2">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Esse eos officia, pariatur
            eveniet
            unde
            recusandae
            quibusdam facilis quos ipsum? Deserunt, fuga maiores? Quibusdam perferendis dignissimos assumenda ut
            sapiente,
            sunt nemo!</p>
        </div>
        <div class="image w-full mt-4 md:mr-12 md:w-4/12">
          <h2 class="text-2xl my-2">Our services</h2>
          <AppAccordion />
        </div>
      </div>
      <div class="mt-12">
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Maiores, at aperiam magni recusandae officia
          cupiditate laboriosam modi tenetur alias aspernatur sed animi optio similique possimus non minus enim amet
          placeat!</p>
      </div>
    </section>
  </div>
</template>

<script>
import AppAccordion from '../components/AppAccordion.vue'
// @ is an alias to /src
export default {
  name: 'HomeView',
  components: {
    AppAccordion
  }
}
</script>
