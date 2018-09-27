<template>
    <main class="button">
        <h3>This is just a quick study of storyBook</h3>
        <button>Test Button</button>
    </main>
</template>
<script>
export default {
    data() {
        return {
            buttonName: 'Test Button'
        }
    }
}
</script>

<style scoped>

.button {
    margin: 16px auto 0;
}

button {
    width: 100%;
    padding: 13px 23px;
    border-radius: 7px;
    background-color: #f7f7f7;
    box-shadow: inset 0 -3px 20px -7px rgba(0, 0, 0, .2), inset 0 -1px 2px 0 rgba(0, 0, 0, .2);
    -webkit-transition: all 200ms ease-in;
    transition: all 200ms ease-in;
    font-family: 'Nunito Sans', sans-serif;
    color: #606266;
    font-size: 16px;
    line-height: 20px;
    font-weight: 700;
    text-align: center;
    letter-spacing: 0.5px;
    text-decoration: none;
    border-color: #7552ff;
    background-color: #7552ff;
    color: #fff;
    cursor: pointer;
}
</style>

