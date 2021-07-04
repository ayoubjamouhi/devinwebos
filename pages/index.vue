<template>
  <div class="text-devinBlue2">
    <header>
      <div class="container">
        <div
          class="
            top-bar
            grid grid-col-1
            bg-devinBlue1
            justify-center
            text-devinBlue2 text-lg text-center
            p-4
          "
        >
          <div>
            <a href="#" class="text-devinBlue2">Social Media Sharing Links</a>
          </div>
          <div class="login-register">
            <a href="#">Login</a>
            <a href="#">Register</a>
          </div>
          <div class="checkout">
            <a href="#" class="font-bold">0 items</a>
            <a href="#">Checkout</a>
          </div>
          <nav>
            <ul class="flex flex-wrap flex-grow justify-center">
              <li class="mr-2">
                <a href="#">About</a>
              </li>
              <li class="mr-2">
                <a href="#">Partner Program</a>
              </li>
              <li class="mr-2">
                <a href="#">Franchise</a>
              </li>
              <li class="mr-2">
                <a href="#">How To Order</a>
              </li>
              <li class="mr-2">
                <a href="#">Contact</a>
              </li>
            </ul>
          </nav>
        </div>
        <div
          class="menu flex flex-col text-devinBlue1 items-center text-center"
        >
          <div class="logo">
            <a href="#" class="text-devinBlue1 text-3xl">Logo</a>
          </div>
          <div class="right-menu flex flex-col">
            <div class="search order-2">
              <input type="text" class="border rounded-sm" />
            </div>
            <nav class="m-3">
              <ul class="text-xl order-1">
                <li>
                  <i class="hidden">icon</i>
                </li>
                <li>
                  <a href="#">CUPS</a>
                </li>
                <li>
                  <a href="#">SPOONS</a>
                </li>
                <li>
                  <a href="#">LIDS</a>
                </li>
                <li>
                  <a href="#">ACCESSORIES</a>
                </li>
                <li>
                  <a href="#">MARKETING</a>
                </li>
              </ul>
            </nav>
          </div>
        </div>
      </div>
    </header>
    <main>
      <div class="first bg-devinBlue3 mt-3 p-4 text-right">
        <h1 class="text-devinBlue4 text-3xl font-bold">
          Suspendise interdum rutum nise.
        </h1>
        <div class="text-devinBlue2">
          Ut tellus quam, venenatis non tempus vitae, volutpat blandit libero
          eget etos.
        </div>
      </div>
      <div class="banners grid grid-cols-1 gap-2 mt-3 justify-items-center">
        <div class="banner">
          <img src="https://via.placeholder.com/200" alt="Banner" class="" />
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
        <div class="grid grid-cols-1 gap-3 justify-items-center">
          <img src="https://via.placeholder.com/200" alt="image" />
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
        <div class="viewAll flex flex-col items-center">
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
    </main>
    <footer class="flex flex-col bg-devinBlue3 px-4">
      <div class="logo m-3 flex justify-center">
        <a href="#" class="text-devinBlue1 text-3xl">Logo</a>
      </div>
      <div class="shop mb-2">
        <h1 class="text-devinBlue4 text-xl font-bold mb-2">SHOP</h1>
        <ul class="text-devinBlue2">
          <li>CUPS</li>
          <li>SPOONS</li>
          <li>LIDS</li>
          <li>ACCESSORIES</li>
          <li>MARKETING</li>
        </ul>
      </div>
      <div class="info mb-2">
        <h1 class="text-devinBlue4 text-xl font-bold mb-2">INFO</h1>
        <ul class="text-devinBlue2">
          <li>COMPANY</li>
          <li>FRANCHISE</li>
          <li>PARTNERS</li>
          <li>CONTACT</li>
          <li>FAQ</li>
        </ul>
      </div>
      <div class="folow-us mb-2 flex flex-col gap-2">
        <h1 class="text-devinBlue4 text-xl font-bold mb-2">FOLLOW US</h1>
        <span>GET OUR NEWSLETTER</span>
        <input type="text" class="border block" />
        <button type="button" class="bg-devinBlue5 text-white px-1 py-2">
          SIGN UP
        </button>
        <div class="social-media"></div>
      </div>
    </footer>
  </div>
</template>

<script>
export default {};
</script>

<style>
.login-register a:first-child::after {
  content: "|";
  height: 4px;
  margin-left: 4px;
}
.checkout a:first-child::after {
  content: "|";
  height: 8px;
  margin-left: 4px;
}
</style>
