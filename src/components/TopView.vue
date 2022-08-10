<template>
    <div>
        <div class="container-fluid top">
            <div class="info">
                <a href="">Contact Us |</a>
                <a href=""> About Us</a>
            </div>
            <div class=" subs ms-auto">
                <a href="">Subscription |</a>
                <a href="">  Login</a>
            </div>
        </div>
    </div>
</template>



<script>
export default {
    name: 'TopView',
}
</script>

<style scoped>
.top{
    background-color: aquamarine;
    display: flex;
}

.top .info a{
    text-decoration-line: none;
}
.top .subs a{
    text-decoration-line: none;
}
</style>