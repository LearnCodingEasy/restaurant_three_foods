<template>
  <div class="Component-Name">
    <footer
      class="bottom-0 bg-background-light dark:bg-background-dark border-t border-primary/20 dark:border-primary/30"
    >
      <nav class="flex justify-around py-2">
        <a class="flex flex-col items-center gap-1 text-primary" href="#">
          <span class="text-xs font-medium">Home</span>
        </a>
        <a
          class="flex flex-col items-center gap-1 text-background-dark/60 dark:text-background-light/60 hover:text-primary"
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
              d="M224,128a8,8,0,0,1-8,8H40a8,8,0,0,1,0-16H216A8,8,0,0,1,224,128ZM40,72H216a8,8,0,0,0,0-16H40a8,8,0,0,0,0,16ZM216,184H40a8,8,0,0,0,0,16H216a8,8,0,0,0,0-16Z"
            ></path>
          </svg>
          <span class="text-xs font-medium">Menu</span>
        </a>
        <a
          class="flex flex-col items-center gap-1 text-background-dark/60 dark:text-background-light/60 hover:text-primary"
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
              d="M205.66,61.64l-144,144a8,8,0,0,1-11.32-11.32l144-144a8,8,0,0,1,11.32,11.31ZM50.54,101.44a36,36,0,0,1,50.92-50.91h0a36,36,0,0,1-50.92,50.91ZM56,76A20,20,0,1,0,90.14,61.84h0A20,20,0,0,0,56,76ZM216,180a36,36,0,1,1-10.54-25.46h0A35.76,35.76,0,0,1,216,180Zm-16,0a20,20,0,1,0-5.86,14.14A19.87,19.87,0,0,0,200,180Z"
            ></path>
          </svg>
          <span class="text-xs font-medium">Offers</span>
        </a>
        <a
          class="flex flex-col items-center gap-1 text-background-dark/60 dark:text-background-light/60 hover:text-primary"
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
              d="M222.37,158.46l-47.11-21.11-.13-.06a16,16,0,0,0-15.17,1.4,8.12,8.12,0,0,0-.75.56L134.87,160c-15.42-7.49-31.34-23.29-38.83-38.51l20.78-24.71c.2-.25.39-.5.57-.77a16,16,0,0,0,1.32-15.06l0-.12L97.54,33.64a16,16,0,0,0-16.62-9.52A56.26,56.26,0,0,0,32,80c0,79.4,64.6,144,144,144a56.26,56.26,0,0,0,55.88-48.92A16,16,0,0,0,222.37,158.46ZM176,208A128.14,128.14,0,0,1,48,80,40.2,40.2,0,0,1,82.87,40a.61.61,0,0,0,0,.12l21,47L83.2,111.86a6.13,6.13,0,0,0-.57.77,16,16,0,0,0-1,15.7c9.06,18.53,27.73,37.06,46.46,46.11a16,16,0,0,0,15.75-1.14,8.44,8.44,0,0,0,.74-.56L168.89,152l47,21.05h0s.08,0,.11,0A40.21,40.21,0,0,1,176,208Z"
            ></path>
          </svg>
          <span class="text-xs font-medium">Contact</span>
        </a>
      </nav>
    </footer>
  </div>
</template>

<script>
export default { name: 'footerView' }
</script>

<style lang="scss" scoped></style>
