<template>
  <!-- ====== Page Title Section Start -->
  <section class="pt-4 pb-1">
    <div class="mx-auto px-4 sm:container">
      <div class=" flex items-center justify-between md:flex">
        <div class=" mb-6 w-full">
          <h2 class="text-2xl font-semibold border border-gray-400 rounded-full px-4 py-2 inline-block dark:border-white dark:text-white">
    {{ title }}
</h2>

        </div>
        <div class="mb-6">
          <router-link
            to="/posts/create"
            class="bg-amber-500 inline-flex items-center justify-center whitespace-nowrap rounded-full py-[10px] px-5 text-sm font-medium text-white hover:bg-amber-400 "
          >
            Tambah Post
            <span class="pl-2">
              <svg
                width="18"
                height="18"
                viewBox="0 0 18 18"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M8.99961 2.39961C5.35453 2.39961 2.39961 5.35453 2.39961 8.99961C2.39961 12.6447 5.35453 15.5996 8.99961 15.5996C12.6447 15.5996 15.5996 12.6447 15.5996 8.99961C15.5996 5.35453 12.6447 2.39961 8.99961 2.39961ZM0.599609 8.99961C0.599609 4.36042 4.36042 0.599609 8.99961 0.599609C13.6388 0.599609 17.3996 4.36042 17.3996 8.99961C17.3996 13.6388 13.6388 17.3996 8.99961 17.3996C4.36042 17.3996 0.599609 13.6388 0.599609 8.99961Z"
                  fill="white"
                />
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M8.99961 5.09961C9.49667 5.09961 9.89961 5.50255 9.89961 5.99961V11.9996C9.89961 12.4967 9.49667 12.8996 8.99961 12.8996C8.50255 12.8996 8.09961 12.4967 8.09961 11.9996V5.99961C8.09961 5.50255 8.50255 5.09961 8.99961 5.09961Z"
                  fill="white"
                />
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M5.09961 8.99961C5.09961 8.50255 5.50255 8.09961 5.99961 8.09961H11.9996C12.4967 8.09961 12.8996 8.50255 12.8996 8.99961C12.8996 9.49667 12.4967 9.89961 11.9996 9.89961H5.99961C5.50255 9.89961 5.09961 9.49667 5.09961 8.99961Z"
                  fill="white"
                />
              </svg>
            </span>
          </router-link>
        </div>
      </div>
    </div>
  </section>
  <!-- ====== Page Title Section End -->
</template>

<script setup>
defineProps({
  title: String,
})
</script>