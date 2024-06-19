<script>
  import NavBar from "../components/NavBar.svelte";
  import { Button, Card } from 'flowbite-svelte';
  import { ArrowRightOutline } from 'flowbite-svelte-icons';
</script>

<NavBar />
<h1>Welcome</h1>
<Card href="/cards">
  <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">For first time visitors</h5>
  <p class="font-normal text-gray-700 dark:text-gray-400 leading-tight mb-4">In order to access our library of Board and Video games, an individual 9$ Stay & Play fee is applied</p>
  <Button class="w-fit">
    For more important info <ArrowRightOutline class="w-6 h-6 ms-2 text-white" />
  </Button>
</Card>
