<script>
    const onClickHandler = () => {
        alert('You clicked the button')
    }
</script>

<button on:click={onClickHandler}><slot /></button>
