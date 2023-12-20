<script>
  import "../app.css";
	import Footer from "../lib/Footer.svelte";
	import Navbar from "../lib/Navbar.svelte";
</script>

<!-- link to google fonts -->
<svelte:head>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400&family=Rokkitt&display=swap" rel="stylesheet">
</svelte:head>

<Navbar />

<slot />

<Footer />