<script setup></script>

<template>
  <!-- Hero Section Start -->
  <div class="container mx-auto px-5 overflow-x-hidden lg:overflow-x-visible">
    <section class="grid grid-cols-none lg:grid-cols-2 pb-16 pt-8 items-center">
      <div class="lg:w-5/6 order-2 lg:order-none">
        <h1 class="text-4xl xl:text-5xl font-bold font-theme-heading text-center lg:text-left">Wappi - Tu Solución para la Comunicación Empresarial</h1>
        <p class="lg:text-xl mt-10 font-theme-content text-theme-grayish-blue text-center lg:text-left">Nuestra plataforma proporciona una solución sencilla y eficaz para enviar mensajes de WhatsApp a gran escala, permitiendo a las empresas comunicarse con sus clientes de manera rápida y personalizada.</p>
        <div class="flex justify-center lg:justify-start mt-10">
          <a class="font-theme-heading font-medium bg-[#11D28C] px-6 py-2 text-white rounded shadow-md hover:bg-white border-2 border-transparent hover:border-theme-primary hover:text-theme-primary cursor-pointer transition duration-200 mr-5" href="https://home-mingle.vercel.app/">
            <button>Live Demo</button>
          </a>

          <a class="font-theme-heading font-medium bg-gray-100 text-gray-500 px-6 py-2 rounded shadow-md hover:bg-white border-2 border-transparent hover:border-theme-grayish-blue hover:text-theme-grayish-blue cursor-pointer transition duration-200" href="https://github.com/laamyry/HomeMingle/">
            <button>Github Repo</button>
          </a>
        </div>
      </div>
      <div class="relative order-1 lg:order-none mb-20 lg:mt-0 lg:mb-0 lg:-mr-10 shadow-md rounded-md">
        <img class="z-10 w-full" src="/images/home.png" />
        <div class="-z-10 bg-[#11D28C] h-52 w-full sm:h-80 sm:w-full rounded-l-full absolute -right-28 md:-right-48 -bottom-8"></div>
      </div>
    </section>
  </div>
  <!-- Hero Section End -->
</template>
