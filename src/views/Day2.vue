<template>
  <PageWrapper>
    <Header />
    <Banner />
    <Languages />
    <Content1 />

    <section class="content-2 my-4">
      <div class="grid grid-cols-2 lg:grid-cols-3 gap-5">
        <div class="col-span-2">
          <div class="cards w-full grid grid-cols-3 gap-5">
            <div
              class="card-1 text-baslikText bg-backgroundCard px-3 py-4 rounded-md grid place-items-center"
            >
              <img src="@/assets/day2/image1.png" class="w-40" alt="" />
              <small class="text-sm uppercase">FRESH COURSE</small>
              <p class="text-md font-semibold py-1">
                Accessible Cross Browser CSS Form Styling
              </p>
              <small class="text-sm">Stephanie Eckles-1h 52m-Couse</small>
            </div>
            <div
              class="card-2 text-baslikText bg-backgroundCard px-3 py-4 rounded-md grid place-items-center"
            >
              <img src="@/assets/day2/image2.png" class="w-40" alt="" />
              <small class="text-sm uppercase"> LEARN SERVERLESS</small>
              <p class="text-md font-semibold py-1">
                Netlify Serverless Functions and Hasura
              </p>
              <small class="text-sm">Jason Lengstorf・1h 27m・Course</small>
            </div>
            <div
              class="card-3 text-baslikText bg-backgroundCard px-3 py-4 rounded-md grid place-items-center"
            >
              <img src="@/assets/day2/image3.png" class="w-40" alt="" />
              <small class="text-sm uppercase">LAYOUT DESIGN</small>
              <p class="text-md font-semibold py-1">
                Declarative UIs without CSS with elm-ui
              </p>
              <small class="text-sm">Flavio Corpa ・1h 27m・Course</small>
            </div>
          </div>
          <div
            class="detail-card rounded-md my-4 text-left py-14 px-6 flex text-baslikText bg-backgroundCard"
          >
            <img src="@/assets/day2/image4.png" class="w-40" alt="" />
            <div class="detail">
              <small class="text-sm uppercase">Wrıte Modern Css</small>
              <h2 class="text-2xl font-semibold py-1">
                Build Modern Layouts with CSS Grid
              </h2>
              <small class="text-sm text-gray-300">
                Hiroko Nishimura・22m・Course</small
              >
              <p class="text-md py-2">
                CSS Grid is a new technology that allows you to problem solve at
                the page-layout level. Learn how to create two-dimensional
                layouts that adapt content to the available space and
                intelligently size and position items within those bounds.
              </p>
            </div>
          </div>
        </div>
        <div class="w-full col-span-2 lg:col-span-1">
          <div
            class="end-card w-full rounded-md bg-backgroundCard text-baslikText py-6 px-6"
          >
            <div class="head text-left">
              <small class="text-sm">INTRODUCTIONS</small>
              <h2 class="text-2xl font-semibold">Start Learning Here</h2>
              <p class="text-md py-2">
                These courses will get you started building real-world
                applications with these tools. They are all excellent
                introductions if you want to learn something new today.
              </p>
            </div>
            <ul class="py-4 grid">
              <li class="flex text-left py-2">
                <img src="@/assets/day2/endCard1.png" class="w-12" alt="" />
                <div class="content px-5">
                  <h3 class="text-md font-semibold">
                    The Beginner's Guide to React
                  </h3>
                  <small class="text-sm">Kent C. Dodds・2h 27m ・Course</small>
                </div>
              </li>
               <li class="flex text-left py-2">
                <img src="@/assets/day2/endCard2.png" class="w-12" alt="" />
                <div class="content px-5">
                  <h3 class="text-md font-semibold">
                CSS Fundamentals
                  </h3>
                  <small class="text-sm">Tyler Clark・33m・Course</small>
                </div>
              </li>
               <li class="flex text-left py-2">
                <img src="@/assets/day2/endCard3.png" class="w-12" alt="" />
                <div class="content px-5">
                  <h3 class="text-md font-semibold">
                  The Beginner's Guide to Figma
                  </h3>
                  <small class="text-sm">Joe Previte・ Course</small>
                </div>
              </li>
               <li class="flex text-left py-2">
                <img src="@/assets/day2/endCard4.png" class="w-12" alt="" />
                <div class="content px-5">
                  <h3 class="text-md font-semibold">
                   Up and running with Svelte 3
                  </h3>
                  <small class="text-sm">Tomasz Łakomy・26m ・Course</small>
                </div>
              </li>
               <li class="flex text-left py-2">
                <img src="@/assets/day2/endCard6.png" class="w-12" alt="" />
                <div class="content px-5">
                  <h3 class="text-md font-semibold">
                    Develop Basic Web Apps with Vue.js
                  </h3>
                  <small class="text-sm">Greg Thoman・16m ・Course</small>
                </div>
              </li>
                <li class="flex text-left py-2">
                <img src="@/assets/day2/endCard5.png" class="w-12" alt="" />
                <div class="content px-5">
                  <h3 class="text-md font-semibold">
                 Write Your First Program with the Rust Language

                  </h3>
                  <small class="text-sm">Pascal Precht・19m ・Course</small>
                </div>
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
import Content1 from "@/components/Day2/Content1";
export default {
  components: { PageWrapper, Header, Banner, Languages, Content1 },
};
</script>

<style scoped lang="postcss">
.day2 {
  @apply md:container md:mx-auto md:px-4 flex flex-col w-full min-h-screen;
}
</style>