<script>
  import NavBar from "../components/NavBar.svelte";
</script>

<!-- <NavBar /> -->
<!-- <h1>Welcome</h1> -->
<!-- <Card href="/cards"> -->
<!--   <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">For first time visitors</h5> -->
<!--   <p class="font-normal text-gray-700 dark:text-gray-400 leading-tight mb-4">In order to access our library of Board and Video games, an individual 9$ Stay & Play fee is applied</p> -->
<!--   <Button class="w-fit"> -->
<!--     For more important info <ArrowRightOutline class="w-6 h-6 ms-2 text-white" /> -->
<!--   </Button> -->
<!-- </Card> -->
<NavBar />
<div
  style="background-image: url(images/LoftImage1.jpg)"
  class="w-full h-screen"
>
  <main class="flex flex-col flex-1 text-black pt-10">
    <!-- this was originally gap-10 py-8 sm:py-14 -->
    <section id="introPage" class="p-24">
      <div
        class="flex flex-col lg:justify-center text-center lg:text-center gap-6 md:gap-8 lg:gap-10 bg-gray-200"
      >
        <h2>
          <p>Welcome to Level One!</p>
        </h2>
      </div>
    </section>
  </main>
</div>
