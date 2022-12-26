<script>
    let count = 0;

    function handleClick() {
        count++;
        console.log('the count is :' +count);
		alert(count);
    }
</script>

<button on:click={handleClick}>
    Clicked {count}
</button>
