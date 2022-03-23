<script>
    import Header from "../components/Header.svelte";
    import Main from '../components/Main.svelte';
    import Sidebar from '../components/Sidebar.svelte';
    import Timeline from '../components/Timeline.svelte';

</script>

<Header/>
<Main>
    <Sidebar/>
    <Timeline/>
</Main>

<style>
    :global(body){
        background-color: #676778;
        color: white;
    }
</style>