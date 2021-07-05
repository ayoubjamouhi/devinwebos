<template>
  <div class="text-devinBlue2 ">
    <Header />
    <main class="mt-10">
      <div class="lg:container lg:mx-auto">
        <div class="nav-tree">
          <ul class="flex flex-row">
            <li><a href="#" class="">Home</a></li>
            <li><a href="#" class="font-bold">Category Name</a></li>
          </ul>
        </div>
      <div class="first bg-devinBlue3 mt-3 p-4 text-right ">
        <h1 class="text-devinBlue4 text-3xl font-bold lg:w-1/4 text-left p-6">
          Category Banner
        </h1>
      </div>
      <div class="flex flex-col lg:flex-row lg:gap-20 my-8">
        <div class="left flex flex-col gap-4 items-center">
          <div class="filtername">
            <input type="text" placeholder="FILTER NAME" class="bg-devinBlue3 text-devinBlue4 px-3">
            <div class="options flex flex-col">
              <span>Option One</span>
              <span>Second Option</span>
              <span>Add Anothor</span>
              <span>Last Option</span>
            </div>
          </div>
          <div class="filtername">
            <input type="text" placeholder="FILTER NAME" class="bg-devinBlue3 text-devinBlue4 px-3">
            <div class="options flex flex-col">
              <span>Option One</span>
              <span>Second Option</span>
              <span>Add Anothor</span>
              <span>Last Option</span>
            </div>
          </div>
        </div>
        <div class="featured-products grid grid-cols-1 gap-3 mt-3 lg:mt-0 px-2">
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
main .nav-tree ul li::after {
  content: ">";
  height: 8px;
  margin-left: 4px;
  margin-right: 4px;
}
main .nav-tree ul li:last-child::after {
  display: none;
}
</style>
