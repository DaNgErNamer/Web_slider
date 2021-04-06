<template>
    <div class="picture">
        <img class="picture" :src="Paths[count-1]">
    </div>
    <controlPanel>
        <button v-if="count===1" class=" btn btn-success mt-5 mr-2 disabled">Previous Slide
        </button>
        <button v-if="count>1" class=" btn btn-success mt-5 mr-2" v-on:click="count>1?count--:count=1">Previous Slide
        </button>
        <label class="btn btn-info disabled mt-5 mr-2">Slide {{count}}</label>
        <button v-if="count<Paths.length" class=" btn btn-success mt-5 mr-2" v-on:click="count++">Next
            Slide</button>
        <button v-if="count===Paths.length" class="disabled btn btn-success mt-5 mr-2"
            v-on:click="count>=Paths.length?count=Paths.length:count++">Next
            Slide</button>
    </controlPanel>
</template>

<script>
    export default {
        data() {
            return {
                count: 1,
                Paths: [
                    require("../assets/pic1.jpg"),
                    require("../assets/pic2.jpg"),
                    require("../assets/pic3.jpg"),
                    require("../assets/pic4.jpg"),
                    require("../assets/pic5.jpg"),
                ]
            }
        }
    }
</script>

<style>
    .picture {
        width: 1600px;
        height: 900px;
        margin: auto;
    }
    .root
    {
        background-color: #1e1e1e;
    }
    .div
    {
        background-color: #1e1e1e;
    }
     body {
    margin: 0;
    font-family: -apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial,"Noto Sans","Liberation Sans",sans-serif,"Apple Color Emoji","Segoe UI Emoji","Segoe UI Symbol","Noto Color Emoji";
    font-size: 1rem;
    font-weight: 400;
    line-height: 1.5;
    color: #212529;
    text-align: left;
    background-color: #1e1e1e !important ;
}
</style>