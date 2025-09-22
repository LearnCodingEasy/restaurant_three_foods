<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <div class="wrapper">
    <div class="flex flex-col">
      <header
        class="sticky top-0 z-10 bg-background-light/80 dark:bg-background-dark/80 backdrop-blur-sm"
      >
        <div
          class="flex items-center justify-between p-4 border-b border-primary/20 dark:border-primary/30"
        >
          <RouterLink to="/">
            <img src="./assets/images/logo_only.jpg" class="header_logo" alt="" width="100px" />
          </RouterLink>

          <h1
            class="flex-1 text-xl font-bold text-center text-background-dark dark:text-background-light"
          >
            Koshary Karab Pizza 3Foods
          </h1>
          <button class="p-2 text-background-dark dark:text-background-light">
            <svg
              fill="currentColor"
              height="24"
              viewBox="0 0 256 256"
              width="24"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M222.14,58.87A8,8,0,0,0,216,56H54.68L49.79,29.14A16,16,0,0,0,34.05,16H16a8,8,0,0,0,0,16h18L59.56,172.29a24,24,0,0,0,5.33,11.27,28,28,0,1,0,44.4,8.44h45.42A27.75,27.75,0,0,0,152,204a28,28,0,1,0,28-28H83.17a8,8,0,0,1-7.87-6.57L72.13,152h116a24,24,0,0,0,23.61-19.71l12.16-66.86A8,8,0,0,0,222.14,58.87ZM96,204a12,12,0,1,1-12-12A12,12,0,0,1,96,204Zm96,0a12,12,0,1,1-12-12A12,12,0,0,1,192,204Zm4-74.57A8,8,0,0,1,188.1,136H69.22L57.59,72H206.41Z"
              ></path>
            </svg>
          </button>
        </div>
        <nav class="flex justify-around px-4 border-b border-primary/20 dark:border-primary/30">
          <RouterLink
            to="/"
            class="flex justify-around item-center py-3 text-sm font-bold border-b-2 text-primary border-primary"
            href="#"
          >
            <svg
              fill="currentColor"
              height="24"
              viewBox="0 0 256 256"
              width="24"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M224,115.55V208a16,16,0,0,1-16,16H168a16,16,0,0,1-16-16V168a8,8,0,0,0-8-8H112a8,8,0,0,0-8,8v40a16,16,0,0,1-16,16H48a16,16,0,0,1-16-16V115.55a16,16,0,0,1,5.17-11.78l80-75.48.11-.11a16,16,0,0,1,21.53,0,1.14,1.14,0,0,0,.11.11l80,75.48A16,16,0,0,1,224,115.55Z"
              ></path>
            </svg>
            Home
          </RouterLink>
          <RouterLink
            to="/menu"
            class="py-3 text-sm font-bold text-background-dark/60 dark:text-background-light/60 border-b-2 border-transparent hover:text-primary hover:border-primary"
            href="#"
            >Menu</RouterLink
          >
          <RouterLink
            to="/offers"
            class="py-3 text-sm font-bold text-background-dark/60 dark:text-background-light/60 border-b-2 border-transparent hover:text-primary hover:border-primary"
            href="#"
            >Offers</RouterLink
          >
          <RouterLink
            to="/contact"
            class="py-3 text-sm font-bold text-background-dark/60 dark:text-background-light/60 border-b-2 border-transparent hover:text-primary hover:border-primary"
            href="#"
            >Contact</RouterLink
          >
        </nav>
      </header>
    </div>
    <RouterView />
  </div>
</template>

<style></style>
