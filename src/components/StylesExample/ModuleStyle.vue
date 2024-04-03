<template>
    <h1 :class="myCLASSES['m-class']">Using module CSS with $ syntax (kabak-case)</h1>
    <h1 :class="myCLASSES.anotherClass">Using Module CSS with $ syntax (camelCase)</h1>
</template>

<style module="myCLASSES">
/* kabab-case */
.m-class{
    background-color: darkred;
    color: lightsalmon;
}

.anotherClass{
    background-color: seagreen;
    color: lightgreen;
}
</style>