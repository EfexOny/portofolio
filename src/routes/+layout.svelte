<script>
  import "../app.css";
  import Header from "../components/header.svelte";
  import Footer from "../components/footer.svelte";
</script>

<div class="container relative flex flex-col max-w-[2000px] mx-auto w-full text-sm sm:text-base min-h-screen bg-gray-800 !scroll-smooth">
    <Header/>
    <slot />
    <Footer/>

</div>
