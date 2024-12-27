<script>
    let {data} = $props()
</script>

<div class="flex flex-col items-center gap-y-4 mt-8">
    <h1 class="text-orange-500 text-2xl">hello world</h1>
    <p>my name is {data.name}</p>
    <p>time is {data.seconds}</p>
</div>