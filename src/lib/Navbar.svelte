<script>
   export const navItems = [
    {name: "Home", href:"/"},
    {name: "About Us", href: "/about"},
    {name: "Menu", href: "/menu"},
    {name: "Contact Us", href: "/contact"},
    {name: "Set List", href: "/set"}
  ];
</script>

<main>
  <nav class="flex justify-between max-w-screen items-center top-0">
    <a href="/">
      <div class="max-w-max p-2 mr-4">
      <img src="./assets/coffee-logo.svg" alt="coffee live logo">
      </div>
    </a>
    <ul class="flex p-2 mx-4 items-center">
    {#each navItems as {name, href}}
      <a href={href}><li class="mx-2 text-lg">{name}</li></a>
      {/each}
      <a href="/signup"><button class="p-2 px-3 mx-6 my-2 bg-brown text-white">SIGN UP</button></a>
    </ul>
  </nav>
</main>

<style>
  nav {
    font-family: 'Roboto', sans-serif;
  }
</style>