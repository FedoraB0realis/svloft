<script>
  import NavBar from "$lib/components/NavBar.svelte";
</script>

<head>
  <link rel="preload" href="images/LoftImage1.jpg" as="image" />
  <link rel="preload" href="images/LoftImage2.jpg" as="image" />
  <link rel="preload" href="images/LoftImage3.jpg" as="image" />
  <link rel="preload" href="images/LoftImage4.jpg" as="image" />
  <link rel="preload" href="images/LoftImage5.jpg" as="image" />
  <link rel="preload" href="images/LoftImage6.jpg" as="image" />
  <link rel="preload" href="images/LoftImage7.jpg" as="image" />
  <link rel="preload" href="images/LoftImage8.jpg" as="image" />
</head>
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
