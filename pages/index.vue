<template>
  <div class="text-devinBlue2 ">
    <Header />
    <main>
      <div class="lg:container lg:mx-auto">
      <div class="first bg-devinBlue3 mt-3 p-4 text-right lg:flex lg:flex-col lg:items-end">
        <h1 class="text-devinBlue4 text-3xl font-bold lg:w-1/4">
          Suspendise interdum rutum nise.
        </h1>
        <div class="text-devinBlue2 lg:w-1/5 lg:text-xl leading-5">
          Ut tellus quam, venenatis non tempus vitae, volutpat blandit libero
          eget etos.
        </div>
      </div>
      <div class="banners grid grid-cols-1 lg:grid-cols-3 gap-2 mt-3 lg:mt-10 lg:mb-10 justify-items-center">
        <div class="banner">
          <img src="https://via.placeholder.com/200" alt="Banner" class="lg:w-full"/>
        </div>
        <div class="banner">
          <img src="https://via.placeholder.com/200" alt="Banner" class="" />
        </div>
        <div class="banner">
          <img src="https://via.placeholder.com/200" alt="Banner" class="" />
        </div>
      </div>
      <div class="featured-products grid grid-cols-1 gap-3 mt-3">
        <h1 class="text-devinBlue4 text-2xl font-bold mb-2 text-center">
          Featured Products
        </h1>
        <div class="grid grid-cols-1 lg:grid-cols-4 gap-3 justify-items-center">
          <div class="fproduct">
            <img src="https://via.placeholder.com/200" alt="image" class="w-full" />
            <div class="desc flex justify-between p-2 items-center">
              <span class="text-devinBlue2 text-base">
                Lorem ipsum dolor, sit amet consectetur adipisicing elit.
              </span>
              <span class="text-devinBlue2 font-bold">$199.29</span>
            </div>
            <div class="addToCart">
              <button type="button" class="bg-devinBlue5 text-white px-3 py-2">
                Add to Cart
              </button>
            </div>
          </div>
          <div class="fproduct">
            <img src="https://via.placeholder.com/200" alt="image" class="w-full"/>
            <div class="desc flex justify-between p-2 items-center">
              <span class="text-devinBlue2 text-base">
                Lorem ipsum dolor, sit amet consectetur adipisicing elit.
              </span>
              <span class="text-devinBlue2 font-bold">$199.29</span>
            </div>
            <div class="addToCart">
              <button type="button" class="bg-devinBlue5 text-white px-3 py-2">
                Add to Cart
              </button>
            </div>
          </div>
          <div class="fproduct">
            <img src="https://via.placeholder.com/200" alt="image" class="w-full"/>
            <div class="desc flex justify-between p-2 items-center">
              <span class="text-devinBlue2 text-base">
                Lorem ipsum dolor, sit amet consectetur adipisicing elit.
              </span>
              <span class="text-devinBlue2 font-bold">$199.29</span>
            </div>
            <div class="addToCart">
              <button type="button" class="bg-devinBlue5 text-white px-3 py-2">
                Add to Cart
              </button>
            </div>
          </div>
          <div class="fproduct">
            <img src="https://via.placeholder.com/200" alt="image" class="w-full"/>
            <div class="desc flex justify-between p-2 items-center">
              <span class="text-devinBlue2 text-base">
                Lorem ipsum dolor, sit amet consectetur adipisicing elit.
              </span>
              <span class="text-devinBlue2 font-bold">$199.29</span>
            </div>
            <div class="addToCart">
              <button type="button" class="bg-devinBlue5 text-white px-3 py-2">
                Add to Cart
              </button>
            </div>
          </div>
        </div>
        <div class="viewAll flex flex-col items-center lg:m-6">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-6 w-6 text-devinBlue2"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M14 5l7 7m0 0l-7 7m7-7H3"
            />
          </svg>
          <span class="text-devinBlue5 font-bold">View All</span>
        </div>
      </div>
      </div>
    </main>
  <Footer />
  </div>
</template>

<script>
import Header from '../components/Header.vue'
import Footer from '../components/Footer.vue'
export default {
  name:'app',
  components: {
    Header,
    Footer
  }
};
</script>

<style>

.checkout a:first-child::after {
  content: "|";
  height: 8px;
  margin-left: 4px;
}
</style>
