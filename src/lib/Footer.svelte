<script>
    export const footerItems = [
  {name: "Home", href:"/"},
  {name: "About Us", href: "/about"},
  {name: "Menu", href: "/menu"},
  {name: "Contact Us", href: "/contact"},
  {name: "Set List", href: "/set"}
];
</script>

<footer class="flex justify-around bg-darkblue text-white p-4">
  <ul>
    <h6 class= "text-lg font-bold">MAIN MENU</h6>
    {#each footerItems as {name, href}}
      <a href={href}><li class="">{name}</li></a>
      {/each}
  </ul>
  <div>
    <h6 class= "text-lg font-bold">VISIT US</h6>
    <p>1050 4TH ST SW<p>
    <p>CALGARY, AB</p>
    <p>CANADA</p>
  </div>
  <div>
    <h6 class= "text-lg font-bold">STAY IN TOUCH</h6>
    <div class="flex space-around">
      <img class="mr-2 mt-2" src="./assets/facebook.svg" alt="facebook logo">
      <img class="mx-2 mt-2" src="./assets/instagram.svg" alt="instagram logo">
      <img class="mx-2 mt-2" src="./assets/x.svg" alt="x logo">
    </div>
    </div>
</footer>