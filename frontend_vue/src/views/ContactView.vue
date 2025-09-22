<template>
  <main class="contact">
    <div class="wrapper">
      <div class="container m-auto">
        <div class="inner">
          <section class="mb-8">
            <!-- <h2 class="text-2xl font-bold text-zinc-900 dark:text-zinc-100">Get in Touch</h2> -->
            <p class="mt-2 text-zinc-600 dark:text-zinc-400 text-2xl" dir="rtl">
              🍴✨ مرحبًا بكم في 3Foods ✨🍴
              <br />
              المكان اللي بيجمعلكم بين 3 أكلات من أجمل ما يكون:
              <br />
              🍛 الكشري المصري الأصيل بطعمه اللي بيشبع القلب قبل المعدة.
              <br />
              🌯 الكريب الحادق والحلو بأنواعه اللي يناسب كل الأذواق.
              <br />
              🍕 البيتزا الساخنة الطازة بعجينة طرية وجبنة سايحة تخليك تدوب من أول قضمة.
              <br />
              في 3Foods هنقدملك تجربة أكل مختلفة، طعم أصيل وجودة عالية، وسعر يناسب الكل 👌💛.
              <br />
              كل ده في جو مريح وخدمة على أعلى مستوى 😊✨.
            </p>
          </section>
          <section class="space-y-4 mb-8">
            <div
              class="flex items-center gap-4 rounded-lg bg-background-light p-4 shadow-sm dark:bg-background-dark/50"
            >
              <div
                class="flex h-12 w-12 shrink-0 items-center justify-center rounded-full bg-primary/20 text-primary"
              >
                <span class="material-symbols-outlined">location_on</span>
              </div>
              <div>
                <h3 class="font-bold text-zinc-900 dark:text-zinc-100">Address</h3>
                <p class="text-sm text-zinc-600 dark:text-zinc-400">
                  26 خدمات البنفسج - شارع د/ أحمد عكاشة البنفسج (10) , Cairo, Egypt, ١١٨٥٦
                </p>
              </div>
            </div>
            <div
              class="flex items-center gap-4 rounded-lg bg-background-light p-4 shadow-sm dark:bg-background-dark/50"
            >
              <div
                class="flex h-12 w-12 shrink-0 items-center justify-center rounded-full bg-primary/20 text-primary"
              >
                <span class="material-symbols-outlined">phone</span>
              </div>
              <div>
                <h3 class="font-bold text-zinc-900 dark:text-zinc-100">Phone</h3>
                <p class="text-sm text-zinc-600 dark:text-zinc-400">+20 11 10207222</p>
              </div>
            </div>
          </section>
          <div
            class="mb-8 h-48 w-full rounded-lg bg-cover bg-center"
            style="
              background-image: url('https://lh3.googleusercontent.com/aida-public/AB6AXuAm9T0V3xH1pCy4hyF4ftKZkf4H19gfs4OyXQQBN-eehW7wxrXDGg8HXmHP6oESAus0lLw7b0rfq1r9MvQB1bkbzINVstULyAYPTpwccn1L-_5BrXX6AXf1FHcKFhNvJbSaRdULA_XRDvrGY98JRGgeBF-Z2IkPnZuOBmurT-gTVaLrL4Ljgzc6el0m1z-xpGgXNNXqo6HuTY7VZUSkaw_ZuwqTqFInAgSCUlbR1KA4HooLbFVI3zqtOXppO9j63gaQiiuOU7F3nc8');
            "
          ></div>
          <section>
            <h2 class="mb-4 text-2xl font-bold text-zinc-900 dark:text-zinc-100">
              Send Us a Message
            </h2>
            <form class="space-y-4">
              <input
                class="w-full rounded-lg border-zinc-300 bg-background-light p-3 text-zinc-900 placeholder-zinc-400 focus:border-primary focus:ring-primary dark:border-zinc-700 dark:bg-zinc-800 dark:text-zinc-200 dark:placeholder-zinc-500"
                placeholder="Your Name"
                type="text"
              />
              <input
                class="w-full rounded-lg border-zinc-300 bg-background-light p-3 text-zinc-900 placeholder-zinc-400 focus:border-primary focus:ring-primary dark:border-zinc-700 dark:bg-zinc-800 dark:text-zinc-200 dark:placeholder-zinc-500"
                placeholder="Your Email"
                type="email"
              />
              <textarea
                class="w-full rounded-lg border-zinc-300 bg-background-light p-3 text-zinc-900 placeholder-zinc-400 focus:border-primary focus:ring-primary dark:border-zinc-700 dark:bg-zinc-800 dark:text-zinc-200 dark:placeholder-zinc-500"
                placeholder="Your Message"
                rows="5"
              ></textarea>

              <prime_button
                icon="pi pi-plus"
                label="Send Message"
                severity="info"
                @click="visible = true"
                class="class_name"
              />
            </form>
          </section>
        </div>
      </div>
    </div>
  </main>
</template>

<style></style>
