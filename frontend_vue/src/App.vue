<!-- <script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />

      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

 -->
<template>
  <div class="wrapper">
    <div class="flex flex-col min-h-screen">
      <header
        class="sticky top-0 z-10 bg-background-light/80 dark:bg-background-dark/80 backdrop-blur-sm"
      >
        <div
          class="flex items-center justify-between p-4 border-b border-primary/20 dark:border-primary/30"
        >
          <img src="./assets/images/logo_only.jpg" class="header_logo" alt="" width="100px" />

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
          <a
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
          </a>
          <a
            class="py-3 text-sm font-bold text-background-dark/60 dark:text-background-light/60 border-b-2 border-transparent hover:text-primary hover:border-primary"
            href="#"
            >Menu</a
          >
          <a
            class="py-3 text-sm font-bold text-background-dark/60 dark:text-background-light/60 border-b-2 border-transparent hover:text-primary hover:border-primary"
            href="#"
            >Offers</a
          >
          <a
            class="py-3 text-sm font-bold text-background-dark/60 dark:text-background-light/60 border-b-2 border-transparent hover:text-primary hover:border-primary"
            href="#"
            >Contact</a
          >
        </nav>
      </header>
      <main class="flex-grow">
        <section class="p-4">
          <h2
            class="px-4 pt-4 pb-4 text-2xl font-bold text-background-dark dark:text-background-light"
          >
            Our Menu Koshary
          </h2>
          <div class="inner grid xxlg_grid_3 xlg_grid_3 laptop_lg_grid_2 md_grid_3 gap_20">
            <!-- Start Card -->
            <prime_card style="width: 25rem; overflow: hidden">
              <template #header>
                <img alt="user header" src="./assets/images/Koshary_1.png" />
              </template>
              <template #title>
                <div class="" dir="rtl">🍛✨ تعالوا دوقوا الكشري الأصلي!</div>
              </template>
              <template #subtitle>
                <div class="" dir="rtl">أشهى وأطيب كشرى مصري على الطراز التقليدي 😋👌</div>
              </template>
              <template #content>
                <p class="m-0" dir="rtl">
                  مع العدس، الأرز، المكرونة، صوص الطماطم الحار والسلطة الطازة 🥗🔥
                  <br />
                  كل لقمة مليانة طعم ولا أحلى!
                </p>
              </template>
              <template #footer>
                <div class="flex gap-4 mt-1">
                  <prime_button label="Cancel" severity="secondary" outlined class="w-full" />
                  <prime_button label="Save" class="w-full" />
                </div>
              </template>
            </prime_card>
            <!-- End Card -->
            <!-- Start Card -->
            <prime_card style="width: 25rem; overflow: hidden">
              <template #header>
                <img alt="user header" src="./assets/images/Koshary_2.png" class="image_scale" />
              </template>
              <template #title>
                <div class="" dir="rtl">🍛🔥 الكشري اللي هيخليك تقول واو!</div>
              </template>
              <template #subtitle>
                <div class="" dir="rtl">عدس، أرز، مكرونة، صوص طماطم حار 🌶️، وصلصة ثومية 😋💛</div>
              </template>
              <template #content>
                <p class="m-0" dir="rtl">كل لقمة مليانة حب وطعم أصلي 🇪🇬👌</p>
              </template>
              <template #footer>
                <div class="flex gap-4 mt-1">
                  <prime_button label="Cancel" severity="secondary" outlined class="w-full" />
                  <prime_button label="Save" class="w-full" />
                </div>
              </template>
            </prime_card>
            <!-- End Card -->
            <!-- Start Card -->
            <prime_card style="width: 25rem; overflow: hidden">
              <template #header>
                <img
                  alt="user header"
                  src="./assets/images/Koshary_3.png"
                  height="300px"
                  width="100%"
                />
              </template>
              <template #title>
                <div class="" dir="rtl">🍛😂 الكشري مش أي كشرى… ده كشرى البطولات!</div>
              </template>
              <template #subtitle>
                <div class="" dir="rtl">العدس بيغني، المكرونة بترقص، وصوص الطماطم 🔥 بيولع!</div>
              </template>
              <template #content>
                <p class="m-0" dir="rtl">مين عنده الجرأة يجرب ويقاوم الطعم ده؟ 😎👌</p>
              </template>
              <template #footer>
                <div class="flex gap-4 mt-1">
                  <prime_button label="Cancel" severity="secondary" outlined class="w-full" />
                  <prime_button label="Save" class="w-full" />
                </div>
              </template>
            </prime_card>
            <!-- End Card -->
            <!-- Start Card -->
            <prime_card style="width: 25rem; overflow: hidden">
              <template #header>
                <img alt="user header" src="./assets/images/sauce.png" />
              </template>
              <template #title>
                <div class="" dir="rtl">🔴 الصلصة (طماطم)</div>
              </template>
              <template #subtitle>
                <div class="" dir="rtl">🌶️ الصلصة الحارة اللي بتولع الطعم 🔥</div>
              </template>
              <template #content>
                <p class="m-0" dir="rtl">اللي يحب الطعم القوي مش هيقدر يقاوم! 😋</p>
              </template>
              <template #footer>
                <div class="flex gap-4 mt-1">
                  <prime_button label="Cancel" severity="secondary" outlined class="w-full" />
                  <prime_button label="Save" class="w-full" />
                </div>
              </template>
            </prime_card>
            <!-- End Card -->
            <!-- Start Card -->
            <prime_card style="width: 25rem; overflow: hidden">
              <template #header>
                <img alt="user header" src="./assets/images/Hot_pepper.png" />
              </template>
              <template #title>
                <div class="" dir="rtl">🌶️ الشطة</div>
              </template>
              <template #subtitle>
                <div class="" dir="rtl">🌶️ الشطة اللي بتولع الطعم 🔥</div>
              </template>
              <template #content>
                <p class="m-0" dir="rtl">للناس اللي بتحب الحار والجرأة في الكشري 😏👌</p>
              </template>
              <template #footer>
                <div class="flex gap-4 mt-1">
                  <prime_button label="Cancel" severity="secondary" outlined class="w-full" />
                  <prime_button label="Save" class="w-full" />
                </div>
              </template>
            </prime_card>
            <!-- End Card -->
            <!-- Start Card -->
            <prime_card style="width: 25rem; overflow: hidden">
              <template #header>
                <img alt="user header" src="./assets/images/onion.png" />
              </template>
              <template #title>
                <div class="" dir="rtl">⚪ البصل المحمر</div>
              </template>
              <template #subtitle>
                <div class="" dir="rtl">🧅 البصل المحمر المقرمش، طعمه يفرق مع كل لقمة 😋</div>
              </template>
              <template #content>
                <p class="m-0" dir="rtl">
                  مع العدس، الأرز، المكرونة، صوص الطماطم الحار والسلطة الطازة 🥗🔥
                  <br />
                  كل لقمة مليانة طعم ولا أحلى!
                </p>
              </template>
              <template #footer>
                <div class="flex gap-4 mt-1">
                  <prime_button label="Cancel" severity="secondary" outlined class="w-full" />
                  <prime_button label="Save" class="w-full" />
                </div>
              </template>
            </prime_card>
            <!-- End Card -->
            <!-- Start Card -->
            <prime_card style="width: 25rem; overflow: hidden">
              <template #header>
                <img alt="user header" src="./assets/images/accuracy.png" />
              </template>
              <template #title>
                <div class="" dir="rtl">🟤 الثومية / الصوص الأبيض</div>
              </template>
              <template #subtitle>
                <div class="" dir="rtl">🧄 ثومية سحرية تضيف الطعم اللي يخلي كل حاجة لذيذة 💛</div>
              </template>
              <template #content>
                <p class="m-0" dir="rtl">الرشّة السحرية لكل كشرية 😎</p>
              </template>
              <template #footer>
                <div class="flex gap-4 mt-1">
                  <prime_button label="Cancel" severity="secondary" outlined class="w-full" />
                  <prime_button label="Save" class="w-full" />
                </div>
              </template>
            </prime_card>
            <!-- End Card -->
          </div>
        </section>
      </main>
      <!-- <footer
        class="sticky bottom-0 bg-background-light dark:bg-background-dark border-t border-primary/20 dark:border-primary/30"
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
      </footer> -->
    </div>
  </div>
</template>

<style></style>
