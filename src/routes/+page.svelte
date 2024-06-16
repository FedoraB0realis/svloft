<script>
  import {
    Navbar,
    NavBrand,
    NavLi,
    NavUl,
    NavHamburger,
  } from "flowbite-svelte";
</script>

<Navbar>
  <NavBrand href="/">
    <img
      src="/src/assets/loft-logo.png"
      class="me-3 h-6 sm:h-9"
      alt="Loft Logo"
    />
    <span
      class="self-center whitespace-nowrap text-xl font-semibold dark:text-white"
    ></span>
  </NavBrand>
  <NavHamburger />
  <NavUl>
    <NavLi href="/about">About</NavLi>
    <NavLi href="/menu">Pricing</NavLi>
    <NavLi href="/games">Games</NavLi>
    <NavLi href="/events">Events</NavLi>
    <NavLi href="/trivia">Trivia</NavLi>
  </NavUl>
</Navbar>
