<template>
  <section class="languages mt-4">
    <div class="grid">
      <div
        class="grid grid-cols-3 gap-5 md:grid-cols-5 lg:grid-cols-8 lg:gap-7"
      >
        <a
          href="#"
          class="card hover:bg-hoverCard grid place-items-center bg-backgroundCard md:gap-6 text-baslikText rounded-md py-10 px-2"
        >
          <i class="fab fa-react text-5xl md:text-6xl py-1 text-blue-300"></i>
          <p class="text-base md:text-sm font-bold mb-2">REACT</p>
        </a>
        <a
          href="#"
          class="card hover:bg-hoverCard grid place-items-center bg-backgroundCard md:gap-6 text-baslikText rounded-md py-10 px-2"
        >
          <i class="fab fa-js text-5xl md:text-6xl py-1 text-yellow-300"></i>
          <p class="text-base md:text-sm font-bold mb-2">JAVASCRIPT</p>
        </a>
        <a
          href="#"
          class="card hover:bg-hoverCard grid place-items-center bg-backgroundCard md:gap-6 text-baslikText rounded-md py-10 px-2"
        >
          <i class="fab fa-vuejs text-5xl md:text-6xl py-1 text-green-300"></i>
          <p class="text-base md:text-sm font-bold mb-2">VUEJS</p>
        </a>
        <a
          href="#"
          class="card hover:bg-hoverCard grid place-items-center bg-backgroundCard md:gap-6 text-baslikText rounded-md py-10 px-2"
        >
          <i class="fab fa-angular text-5xl md:text-6xl py-1 text-red-300"></i>
          <p class="text-base md:text-sm font-bold mb-2">ANGULAR</p>
        </a>
        <a
          href="#"
          class="card hover:bg-hoverCard grid place-items-center bg-backgroundCard md:gap-6 text-baslikText rounded-md py-10 px-2"
        >
          <i class="fab fa-node text-5xl md:text-6xl py-1 text-green-300"></i>
          <p class="text-base md:text-sm font-bold mb-2">NODEJS</p>
        </a>
        <a
          href="#"
          class="card hover:bg-hoverCard grid place-items-center bg-backgroundCard md:gap-6 text-baslikText rounded-md py-10 px-2"
        >
          <i class="fab fa-npm text-5xl md:text-6xl py-1 text-red-300"></i>
          <p class="text-base md:text-sm font-bold mb-2">NPM</p>
        </a>
        <a
          href="#"
          class="card hover:bg-hoverCard grid place-items-center bg-backgroundCard md:gap-6 text-baslikText rounded-md py-10 px-2"
        >
          <i class="fab fa-aws text-5xl md:text-6xl py-1 text-yellow-300"></i>
          <p class="text-base md:text-sm font-bold mb-2">AWS</p>
        </a>
        <a
          href="#"
          class="card hover:bg-hoverCard grid place-items-center bg-backgroundCard md:gap-6 text-baslikText rounded-md py-10 px-2"
        >
          <i
            class="fab fa-python text-5xl md:text-6xl py-1 text-yellow-600"
          ></i>
          <p class="text-base md:text-sm font-bold mb-2">PYTHON</p>
        </a>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style scoped lang="postcss">
.card {
  @apply transition-all;
}
</style>