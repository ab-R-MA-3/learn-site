<template>
    <div class="button-line">
        <a v-bind:href={link} class="btn">
           <div id="button">{{title}}</div>
        </a>
    </div>
</template>

<script>
export default {
    props:['title','link'],
}
</script>

<style scoped>

    .button-line {
        border:solid 10px #1f1f1f;
    }    

    #button {
        background-color : #ffffff;
        text-decoration: none;
        text-align: center;
    }

    #button :hover {
        background-color: #afafaf;
    }
</style>