<template>
  <header class="shadow w-screen">
    <nav>
      <nav class="flex items-center justify-between flex-wrap bg-green-400 p-6">
        <router-link :to="{ name: 'home' }">
          <div class="flex items-center flex-shrink-0 text-white mr-6">
            <icon-component class="mr-2"></icon-component>
            <span class="font-semibold text-xl tracking-tight"
              >Currency Exchange</span
            >
          </div>
        </router-link>
        <div class="relative">
          <router-link
            to="/"
            class="text-base font-medium text-white hover:text-gray-900 mx-4"
            >Home
          </router-link>

          <router-link
            to="/about"
            class="text-base font-medium text-white hover:text-gray-900 mx-4"
            >About
          </router-link>
        </div>
        <div
          class="
            hidden
            sm:block
            w-full
            lg:flex lg:items-center lg:wauto
            ms-center
            lg:wauto
            to
          "
        >
          <div class="text-sm lg:flex-grow"></div>
        </div>
      </nav>
    </nav>
  </header>
</template>

<script>
import IconComponent from '@/components/IconComponent'
export default {
  name: 'HeaderComponent',
  components: { IconComponent },
}
</script>
