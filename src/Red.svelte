<script>
    function show(node) {
        return {
            duration: 500,
            css: (t) => `opacity: ${t}`,
        }
    }
</script>

<div in:show></div>

<style>
    div {
        width: 100px;
        height: 100px;
        background: red;
    }
</style>
