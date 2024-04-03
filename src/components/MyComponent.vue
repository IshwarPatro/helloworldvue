<!--Components-->


<!--Nested Components-->
<!--JS-->
<!-- <script setup>
// console.log('Hello World');
import NestedComponent from './NestedComponent.vue';
</script> -->


<!-- HTML
<template>
    <h1>This is a parent component</h1>
    <NestedComponent/>
</template> -->


<!-- CSS
<style>
h1{
    color: purple;
}
</style> -->


<!---------------------------------------------------------->
<!---------------------------------------------------------->
<!---------------------------------------------------------->


<!--Text Interpolation-->
<!--JS-->
<!-- <script setup>
const myMessage = 'Yellow Worls';
const myNumber = 100;
function calculator(x,y,z){
    if(z=='ADD'){return x + y}
    if(z=='SUB'){return x - y}
    if(z=='DIV'){return x / y}
    if(z=='MUL'){return x * y}
}
</script> -->


<!-- HTML
<template>
    <h1>This is Text Interpolation.{{ myMessage }}</h1>
    <h1>This is Text Interpolation.{{ myNumber }}</h1>
    <h1> 2 + 2 = {{ 2+2 }}</h1>
    <h1>This is Text Interpolation(Calculator Function) (2+2): {{ calculator(2,2,'ADD') }}</h1>
    <h1>This is Text Interpolation(Calculator Function) (2-2): {{ calculator(2,2,'SUB') }}</h1>
    <h1>This is Text Interpolation(Calculator Function) (2/2): {{ calculator(2,2,'DIV') }}</h1>
    <h1>This is Text Interpolation(Calculator Function) (2*2): {{ calculator(2,2,'MUL') }}</h1>

</template> -->


<!-- CSS
<style>
h1{
    color: purple;
    font-size: 20px;
}
</style> -->


<!---------------------------------------------------------->
<!---------------------------------------------------------->
<!---------------------------------------------------------->


<!--Attribute Binding-->
<!--JS-->
<!-- <script setup>
const mySite = 'https://www.youtube.com/watch?v=xvFZjo5PgG0';
const myImage = 'https://images.unsplash.com/photo-1712011465435-e91cdad132ae?q=80&w=326&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D';
const imageheight = 800;
const imagewidth = 400;
const alimage = 'just s image';
</script> -->


<!--HTML-->
<!-- <template>
    <h1>This is Attribute Binding:  <a v-bind:href="mySite">My Site Link</a></h1>
    <img :src="myImage" :alt="alimage"  :width="imagewidth" :height="imageheight">
</template> -->


<!--CSS-->
<!-- <style>
h1{
    color: purple;
    font-size: 20px;
}
</style> -->


<!---------------------------------------------------------->
<!---------------------------------------------------------->
<!---------------------------------------------------------->



<!--Dynamic Binding-->
<!--JS-->
<!-- <script setup>
const imageinfo = {
    src:'https://images.unsplash.com/photo-1712011465435-e91cdad132ae?q=80&w=326&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D',
    alt:'just a image',
    width: 400,
    height: 800,
}
</script> -->


<!--HTML-->
<!-- <template>
    <img :="imageinfo" />
</template> -->


<!--CSS-->
<!-- <style>
h1{
    color: purple;
    font-size: 20px;
}
</style> -->


<!---------------------------------------------------------->
<!---------------------------------------------------------->
<!---------------------------------------------------------->

<!--Styling in Depth-->
<!--JS-->
<script setup>
const imageinfo = {
    src:'https://images.unsplash.com/photo-1712011465435-e91cdad132ae?q=80&w=326&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D',
    alt:'just a image',
    width: 400,
    height: 800,
}
</script>


<!--HTML-->
<template>
    <img :="imageinfo" />
</template>


<!--CSS-->
<style>
h1{
    color: purple;
    font-size: 20px;
}
</style>


<!---------------------------------------------------------->
<!---------------------------------------------------------->
<!---------------------------------------------------------->
