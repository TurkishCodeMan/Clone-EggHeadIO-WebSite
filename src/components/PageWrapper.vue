<template>
  <div class="page-wrapper"><slot /></div>
</template>

<script>
export const PageWrapper = {
  name: "PageWrapper",
};
export default PageWrapper;
</script>

<style scoped lang="postcss">
.page-wrapper {
  @apply md:container md:mx-auto lg:px-24 flex flex-col w-full min-h-screen;
}
</style>