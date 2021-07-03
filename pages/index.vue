<template>
  <div>
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
      <div class="banners grid grid-cols-1 gap-2 mt-3">
        <div
          class="
            bannerOne
            bg-devinBlue3
            p-4
            text-center text-devinBlue2
            font-bold
          "
        >
          BannerOne
        </div>
        <div class="bannerTwo">BannerTwo</div>
        <div class="bannerThree">BannerOne</div>
      </div>
    </main>
    <footer>footer</footer>
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
