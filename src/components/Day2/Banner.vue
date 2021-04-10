<template>
    <section class="first">
      <div
        class="open flex-col md:flex-row flex items-center justify-center text-baslikText md:text-left shadow-2xl rounded"
      >
        <img src="@/assets/day2/image.png" alt="" />
        <div class="info w-full md:w-7/12">
          <p class="new-course font-base text-lg py-2 text-textGreen">
            New Course
          </p>
          <h1 class="text-2xl md:text-6xl py-2 font-extrabold hover:text-hoverGreenText">
            Create a Digital Garden With Rust
          </h1>
          <div class="person flex py-2 items-center">
            <img
              src="@/assets/day2/person.png"
              class="object-fit rounded-full"
              alt=""
            />
            <p class="person-name py-2 px-3 hover:text-hoverGreenText">Chris Biscardi</p>
          </div>
          <p class="detail">
            You'll work through the first command for the CLI, writing files.
            You start by initializing a new Cargo binary crate by creating the
            write command that allows you to create files (and their contents)
            to the folder that you set.
          </p>
        </div>
      </div>
    </section>
</template>

<script>
export default {

}
</script>

<style>

</style>