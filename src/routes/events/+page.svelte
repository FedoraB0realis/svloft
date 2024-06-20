<script>
  import NavBar from "$lib/components/NavBar.svelte";
</script>

<NavBar />
<div
  style="background-image: url(/src/lib/assets/LoftImage1.jpg)"
  class="w-full h-screen"
>
  <main class="flex flex-col flex-1 p-10 text-black">
    <section
      id="introPage"
      class="grid grid-cols-1 lg:grid-cols-2 gap-10 py-8 sm:py-14"
    >
      <div
        class="flex flex-col lg:justify-center text-center lg:text-center gap-6 md:gap-8 lg:gap-10 bg-gray-200"
      >
        <h2>
          <p>Events</p>
        </h2>
      </div>
    </section>
  </main>
</div>
