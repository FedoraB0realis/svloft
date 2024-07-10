<script>
  import {
    Navbar,
    NavBrand,
    NavLi,
    NavUl,
    NavHamburger,
    Button,
  } from "flowbite-svelte";
</script>

<div class="relative px-8">
  <Navbar class="px-2 sm:px-4 py-2.5 fixed w-full z-20 top-0 start-0 border-b">
    <NavBrand href="/">
      <img
        src="src/static/images/logo-text.png"
        class="me-3 h-6 sm:h-9"
        alt="Loft Logo"
      />
    </NavBrand>
    <div class="flex md:order-2">
      <Button size="sm" href="/reservations">Reserve Now</Button>
      <NavHamburger />
    </div>
    <NavUl class="order-1">
      <NavLi class="text-3xl" href="/about">About</NavLi>
      <NavLi class="text-3xl" href="/menu">Menu</NavLi>
      <NavLi class="text-3xl" href="/games">Games</NavLi>
      <!-- <NavLi href="/reservations">Reservations</NavLi> -->
      <NavLi class="text-3xl" href="/events">Events</NavLi>
      <NavLi class="text-3xl" href="/trivia">Trivia</NavLi>
      <NavLi class="text-3xl" href="/giftcards">Gift Cards</NavLi>
      <NavLi class="text-3xl" href="/contact">Contact</NavLi>
    </NavUl>
  </Navbar>
</div>
