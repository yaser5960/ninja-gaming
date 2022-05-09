<!-- <script>  
    const updateTitle = () => {
        title = "something for write"
    }
    import Title from '$lib/title.svelte';
</script> -->

<div class="index">
    <!-- <h1>{title}</h1> -->
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusantium pariatur explicabo dolores autem vel molestias hic consequuntur ipsum facere unde dolore voluptates officiis porro, ea libero velit obcaecati est quod.</p>
    <!-- <button on:click={updateTitle}>change title</button> -->
    <!-- <input type="text" bind:value={title}> -->
    <div class="anchor">
        <a href="/guides">View Guides</a>
        <a href="/about">About</a>
    </div>    
</div>

<style>
    .index{
        text-align: center;
        display: block;
        margin: 20px auto; 
    }
    .anchor{
        display: block;
        margin: 20px auto;
    }
</style>