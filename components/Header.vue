<template>
   <header>
      <div class="lg:container lg:mx-auto">
        <div
          class="
            top-bar
            flex
            flex-col
            lg:flex-row
            lg:justify-between
            bg-devinBlue1
            justify-center
            text-devinBlue2
            text-lg
            text-center
            p-4
            lg:p-2
          "
        >
          <div class="lg:flex-2 lg:text-left">
            <a href="#" class="text-devinBlue2">Social Media Sharing Links</a>
          </div>
          <div class="login-register lg:flex-1">
            <a href="#">Login</a>
            <a href="#">Register</a>
          </div>
          <div class="checkout lg:flex-1">
            <a href="#" class="font-bold">0 items</a>
            <a href="#">Checkout</a>
          </div>
          <nav class="">
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
          class="menu flex flex-col lg:flex-row lg:justify-between lg:mt-4 text-devinBlue1 items-center text-center"
        >
          <div class="logo">
            <a href="#" class="text-devinBlue1 text-3xl">Logo</a>
          </div>
          <div class="right-menu flex flex-col">
            <div class="search order-2 lg:order-1">
              <input type="text" class="border rounded-sm" />
            </div>
            <nav class="m-3 lg:mt-3 order-1 lg:order-2">
              <ul class="navbar lg:flex lg:flex-row text-xl order-1 lg:order-2">
                <li class="lg:mr-6">
<svg aria-hidden="true" focusable="false" data-prefix="fas" data-icon="bookmark" class="svg-inline--fa fa-bookmark fa-w-12 font-bold" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512"><path fill="currentColor" d="M0 512V48C0 21.49 21.49 0 48 0h288c26.51 0 48 21.49 48 48v464L192 400 0 512z"></path></svg>
                </li>
                <li class="lg:mr-6">
                  <a href="#">CUPS</a>
                </li>
                <li class="lg:mr-6">
                  <a href="#">SPOONS</a>
                </li>
                <li class="lg:mr-6">
                  <a href="#">LIDS</a>
                </li>
                <li class="lg:mr-6">
                  <a href="#">ACCESSORIES</a>
                </li>
                <li class="">
                  <a href="#">MARKETING</a>
                </li>
              </ul>
            </nav>
          </div>
        </div>
      </div>
    </header>
</template>
<style>
.login-register a:first-child::after {
  content: "|";
  height: 4px;
  margin-left: 4px;
}
</style>
