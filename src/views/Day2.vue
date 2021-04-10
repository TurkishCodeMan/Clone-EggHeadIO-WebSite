<template>
  <PageWrapper>
    <Header />
    <Banner />
    <Languages />

    <section class="cards"></section>
  </PageWrapper>
</template>

<script>
import Header from "@/components/Day2/Header";
import Banner from "@/components/Day2/Banner";
import Languages from "@/components/Day2/Languages";
import PageWrapper from "@/components/PageWrapper";

export default {
  components: { PageWrapper, Header, Banner, Languages },
};
</script>

<style scoped lang="postcss">
.day2 {
  @apply md:container md:mx-auto md:px-4 flex flex-col w-full min-h-screen;
}
</style>