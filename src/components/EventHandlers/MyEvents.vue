<!--<script setup>
import {ref} from 'vue'
let count =ref(0);

const incrementCounter = () => count.value++
const decrementCounter = () => count.value--

</script>

<template>
    <h1>
        Count: {{ count }}
    </h1>
    <button @:click="incrementCounter">Increment</button>
    <button @:click="decrementCounter">Decrement</button>
</template>
-->
 

<!--Submit Handler-->
<!--<script setup>
const submitHandler = (e)=>{
    e.preventDefault()
    alert('Valid Credentials')
}

</script>

<template >
    <form @:submit="submitHandler">
    <input type="text" placeholder="Please enter your name">
    <input type="email" placeholder="Please enter your email">
    <button type="submit">Submit</button>
    </form>
</template>
-->

<!--Show mwssage Handler-->
<script setup>
    const showMessage =(message)=>alert(message)
</script>

<template>
    <button @click="showMessage('This is my message.')">
        Show Message
    </button>
</template>