<script>
   import Main from '../components/Main.svelte';
   import Header from '../components/Header.svelte';
   import Sidebar from '../components/Sidebar.svelte';
   import TimeLine from '../components/TimeLine.svelte';
</script>

<style>
 :global(body) {
     background-color: #676778;
     color: white;
 }
</style>

<Header />
<Main> 
    <TimeLine />
    <Sidebar />
</Main>
