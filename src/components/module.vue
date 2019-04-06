<template>
<div class="hello">
    <div class="holder">
        <form @submit.prevent="addSkill"></form>
        <input type="text" placeholder="Enter Some words..." v-model="skill">
        {{skill}}
    </div>
</div>
</template>

<script>

export default {
    name: 'Module',
    data(){
        return {
           skill: ''
        }
    },
}
</script>
<style lang="scss" scoped>
    ul{
        margin: 0;
        padding: 0;
        list-style: none;
        li{
            padding: 20px;
            font-size: 1.3em;
            background-color: #E0EDF4;
            margin-bottom: 2px;
            color: #3E5252;
        }
        p{
            text-align: center;
            padding: 30px 0;
            color: gray;
        }
    }
    .container{
        box-shadow: 0px 0px 40px lightgray;
    }
    .holder{
        width: 50%;
        display: flex;
        justify-content: center;
        flex-direction: column;
        margin: 0 auto;
    }
    input{
        width: calc(100%-10%);
        border: 0;
        padding: 20px;
        font-size: 1.3em;
        background-color: #323333;
        color: #687f7f;
    }
</style>


