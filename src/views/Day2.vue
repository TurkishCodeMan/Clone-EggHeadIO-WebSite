<template>
  <PageWrapper>
    <Header />
    <Banner />
    <Languages />

    <section class="content-1 my-4">
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <div class="col-span-2 text-white bg-backgroundCard grid grid-cols-2">
          <div class="card-1 py-5 px-6 text-baslikText text-left">
            <h2 class="uppercase text-sm">Optimizing Your Learning</h2>
            <h1 class="text-4xl font-bold">
              Learning Tips Every Developer Should Know
            </h1>
            <small>Ceora Ford</small>
            <p class="text-base">
              Learning will be a constant in your career no matter what you
              decide to do, especially if you are breaking into tech. There are
              a number of tried and true methods that will allow you to learn
              more efficiently so that you can keep up with the industry. These
              evergreen methods will serve you well no matter your level of
              expertise.
            </p>
          </div>
          <div class="card-2">
            <iframe
              class="rounded"
              width="100%"
              height="100%"
              src="https://www.youtube.com/embed/pA1qhZEjNog"
              title="YouTube video player"
              frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen
            ></iframe>
          </div>
        </div>
        <div class="text-white col-span-1">
          <div class="card-3 h-full grid place-items-center text-left py-4 px-16 max-w-full bg-blue-500 opacity-80 rounded">
            <ul class="w-full">
              <li class="w-full">
                <small>May 4th @ 1PM PT</small>
                <h6 class="text-md font-semibold">
                  Learn With Jason w/ Shaundai Person
                </h6>
                <small>May 4th @ 1PM PT</small>
              </li>
              <li>
                <h2 class="uppercase text-sm">UpComing Events</h2>
                <h6 class="text-md font-semibold">
                  Intro to Vue 3 w/ Kevin Cunningham
                </h6>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </section>
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