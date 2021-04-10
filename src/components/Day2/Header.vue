<template>
  <header class="shadow-md">
    <div class="logo flex items-center">
      <img src="@/assets/day2/logoday2.svg" width="35" height="35" alt="Logo" />
      <h3 class="logo-text mx-2 text-baslikText text-xl">egghead.io</h3>
    </div>
    <div
      class="primary-menu absolute top-12 flex-col flex text-left transform transition-all bg-background md:relative md:top-0 md:flex md:flex-row justify-around w-11/12"
      :class="{ hidden: !toggleMenu }"
    >
      <div class="search flex relative items-center md:w-2/4">
        <img
          src="@/assets/day2/search.svg"
          class="absolute top-7 md:top-3"
          alt=""
        />
        <input
          placeholder="What do you want to learn today ?"
          class="px-8 py-2 w-full mt-5 md:m-0 bg-backgroundCard text-left"
          type="text"
        />
        <button
          class="btn absolute top-5 md:top-0 p-2 right-0 rounded-tr-md rounded-br-md"
        >
          Search
        </button>
      </div>
      <div class="header-end py-4 md:py-0">
        <button
          class="btn hidden lg:inline-block rounded-md text-baslikText p-2"
        >
          Own Your Online Presence
        </button>
        <a
          href="#"
          class="sign-in text-baslikText text-center text-md mx-3 py-3"
          >Sign in</a
        >
      </div>
    </div>
    <a
      href=""
      class="bars inline-block md:hidden text-red-50 px-3"
      @click.prevent="toggleMenu = !toggleMenu"
    >
      <i class="fas fa-bars text-xl my-1"></i>
    </a>
  </header>
</template>

<script>
export const Header = {
  data() {
    return {
      toggleMenu: false,
    };
  },
};
export default Header;
</script>

<style scoped lang="postcss">
header {
  @apply flex justify-between w-full py-3;
}
.btn {
  @apply focus:outline-none border-none bg-blue-600;
}
input {
  @apply border-none focus:outline-none rounded-md;
}
</style>