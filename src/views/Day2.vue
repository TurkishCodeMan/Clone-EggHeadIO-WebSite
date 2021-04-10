<template>
  <div class="day2">
    <Header />
    <Banner />
    <section class="languages mt-4">
      <div class="grid">
        <div class="grid grid-cols-4 gap-5 md:grid-cols-5 lg:grid-cols-8 lg:gap-7">
          <a href="#" class="card hover:bg-hoverCard    grid place-items-center bg-backgroundCard md:gap-6 text-baslikText rounded-md py-10 px-2">
            <i class="fab fa-react text-6xl py-1 text-blue-300"></i>
            <p class="text-lg font-semibold mb-2">REACT</p>
          </a>
             <a href="#" class="card hover:bg-hoverCard   grid place-items-center bg-backgroundCard md:gap-6 text-baslikText rounded-md py-10 px-2">
            <i class="fab fa-js text-6xl py-1 text-yellow-300"></i>
            <p class="text-lg font-semibold mb-2">JAVASCRIPT</p>
          </a>
             <a href="#" class="card  hover:bg-hoverCard   grid place-items-center bg-backgroundCard md:gap-6 text-baslikText rounded-md py-10 px-2">
            <i class="fab fa-vuejs text-6xl py-1 text-green-300"></i>
            <p class="text-lg font-semibold mb-2">VUEJS</p>
          </a>
             <a href="#" class="card hover:bg-hoverCard   grid place-items-center bg-backgroundCard md:gap-6 text-baslikText rounded-md py-10 px-2">
            <i class="fab fa-angular text-6xl py-1 text-red-300"></i>
            <p class="text-lg font-semibold mb-2">ANGULAR</p>
          </a>
             <a href="#" class="card hover:bg-hoverCard    grid place-items-center bg-backgroundCard md:gap-6 text-baslikText rounded-md py-10 px-2">
            <i class="fab fa-node text-6xl py-1 text-green-300"></i>
            <p class="text-lg font-semibold mb-2">NODEJS</p>
          </a>
             <a href="#" class="card hover:bg-hoverCard   grid place-items-center bg-backgroundCard md:gap-6 text-baslikText rounded-md py-10 px-2">
            <i class="fab fa-npm text-6xl py-1 text-red-300"></i>
            <p class="text-lg font-semibold mb-2">NPM</p>
          </a>
             <a href="#" class="card  hover:bg-hoverCard  grid place-items-center bg-backgroundCard md:gap-6 text-baslikText rounded-md py-10 px-2">
            <i class="fab fa-aws text-6xl py-1 text-yellow-300"></i>
            <p class="text-lg font-semibold mb-2">AWS</p>
          </a>
             <a href="#" class="card  hover:bg-hoverCard  grid place-items-center bg-backgroundCard md:gap-6 text-baslikText rounded-md py-10 px-2">
            <i class="fab fa-python text-6xl py-1 text-yellow-600"></i>
            <p class="text-lg font-semibold mb-2">PYTHON</p>
          </a>
      
        </div>
      </div>
    </section>
    <section class="cards"></section>
  </div>
</template>

<script>
import Header from "@/components/Day2/Header";
import Banner from "@/components/Day2/Banner";
export default {
  components: { Header, Banner },
};
</script>

<style scoped lang="postcss">
.day2 {
  @apply md:container md:mx-auto md:px-4 flex flex-col w-full min-h-screen;
}
.card{
  @apply transition-all
}
</style>