<template>
    <h2 class="g-1">Another Global Style (Combined Styles)</h2>
    <h2 class="l-1">Another Local Style (Combined Styles)</h2>
</template>

<!--Global Styling-->
<style>
.g-1{
    background-color: cornflowerblue;
    color: aqua;
}
</style>
<!--Local Styling-->
<style scoped>
.l-1{
    background-color: darkgoldenrod;
    color: beige;
}
</style>