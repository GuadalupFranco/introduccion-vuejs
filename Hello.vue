<template>
    <div>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Odit magnam voluptatem sunt debitis dolorem officia obcaecati accusantium sapiente? Rem alias quo illo eum, repellat numquam itaque delectus aperiam magnam quod?</p>
        <div> {{ Hi }} </div>
    </div>
</template>

<script>
export default {
    data(){
        return{
            text: "Hi"
        };
    },
    setup() {
        
    },
}
</script>

<style>
p {
    color: red;
}
</style>