<template>
  <PageWrapper>
    <Header />
    <Banner />
    <Languages />
    <Content1 />
    <Content2/>

 
  </PageWrapper>
</template>

<script>
import Header from "@/components/Day2/Header";
import Banner from "@/components/Day2/Banner";
import Languages from "@/components/Day2/Languages";
import PageWrapper from "@/components/PageWrapper";
import Content1 from "@/components/Day2/Content1";
import Content2 from "@/components/Day2/Content2";
export default {
  components: { PageWrapper, Header, Banner, Languages, Content1,Content2 },
};
</script>

<style scoped lang="postcss">
.day2 {
  @apply md:container md:mx-auto md:px-4 flex flex-col w-full min-h-screen;
}

</style>