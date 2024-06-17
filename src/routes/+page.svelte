<script>
  import NavBar from "$lib/components/NavBar.svelte";
  import { Button, Card } from 'flowbite-svelte';
  import { ArrowRightOutline } from 'flowbite-svelte-icons';
</script>

<NavBar />
<h1>Welcome</h1>
<Card href="/cards">
  <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">For first time visitors</h5>
  <p class="font-normal text-gray-700 dark:text-gray-400 leading-tight">In order to acces our library of Board games and Video games, an individual charge of 9$ is applied</p>
  <Button class="w-fit">
    For more important info <ArrowRightOutline class="w-6 h-6 ms-2 text-white" />
  </Button>
</Card>
