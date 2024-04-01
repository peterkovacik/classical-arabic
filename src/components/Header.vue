<template>
    <div>
      <div class=" header-background">
        <nav class="container px-6 py-8 mx-auto md:flex md:justify-between md:items-center">
          <div class="flex items-center justify-between">
            <!--<g-link to="/" class="text-xl font-bold text-gray-800 md:text-2xl hover:text-blue-400">
              Logo
            </g-link> -->
            <g-link to="/">
              <g-image src="/images/classical-arabic-logo.png" class="arabic-logo" alt="logo for Classical Arabic with Peter Omar Kovacik" />
            </g-link>
            
            <!-- Mobile menu button -->
            <div @click="showMenu = !showMenu" class="flex md:hidden">
              <button
                type="button"
                class="
                  text-gray-800
                  hover:text-gray-400
                  focus:outline-none focus:text-gray-400
                "
              >
                <svg viewBox="0 0 24 24" class="w-6 h-6 fill-current">
                  <path
                    fill-rule="evenodd"
                    d="M4 5h16a1 1 0 0 1 0 2H4a1 1 0 1 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2z"
                  ></path>
                </svg>
              </button>
            </div>
          </div>
  
  
          <!-- Mobile Menu open: "block", Menu closed: "hidden" -->
          <ul
            :class="showMenu ? 'flex' : 'hidden'"
            class="
              flex-col
              mt-8
              space-y-4
              md:flex
              md:space-y-0
              md:flex-row
              md:items-center
              md:space-x-10
              md:mt-0
            "
          >
            <!--
            <li class="text-sm font-bold text-gray-800 hover:text-blue-400">
               Home
            </li>
            <li class="text-sm font-bold text-gray-800 hover:text-blue-400">
               About
            </li>
            -->
            <g-link class="text-md font-bold text-green-800 hover:text-green-700" to="/">
              Home
            </g-link>
            <g-link class="text-md font-bold text-green-800 hover:text-green-700" to="/about">
              About
            </g-link>
            <g-link class="text-md font-bold text-green-800 hover:text-green-700" to="/contact">
              Contact
            </g-link>
            <button class=" w-1/2 bg-transparent hover:bg-green-800 text-green-800 font-semibold hover:text-white py-2 px-4 border border-green-800 hover:border-transparent rounded">
              <g-link class="" to="https://arabicwithomar.teachable.com/" target="_blank">
              Student Portal
              </g-link>
            </button>
          </ul>
        </nav>
      </div>
    </div>
  </template>

<script>
    export default {
        name: 'Header',
        data() {
            return {
                showMenu: false,
            };
        },
    }
</script>

<style scoped>
  .header-background {
    background-image: url('/images/islamic-white-banner.avif');
    background-repeat: no-repeat;
    background-size: cover;
    border-bottom: #eee 1px solid; 
  }

  .arabic-logo {
    width: 214px;
    height: 125px;
  }
</style>