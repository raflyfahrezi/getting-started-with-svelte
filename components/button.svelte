<script>
    let alertText

    const onClickHandler = () => {
        alert(alertText)
    }

    export { alertText }
</script>

<button on:click={onClickHandler}><slot /></button>
