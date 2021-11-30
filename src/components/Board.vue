<template>
    <div class="board-container">
        <div v-for="(item,index) in boardItem" 
        v-bind:key="item.id"
        v-bind:item ="item"
        v-bind:index = "index"
        class="boardItem">
        </div>
    </div>
</template>

<script>
export default {
    name:'Board',
    data: ()=> {
        return{
            name: 'angelo lapus',
            boardItem:[
                {id: 0, value: ''},
                {id: 1, value: ''},
                {id: 2, value: ''},
                {id: 3, value: ''},
                {id: 4, value: ''},
                {id: 5, value: ''},
                {id: 6, value: ''},
                {id: 7, value: ''}
            ]
        }
    }
}
</script>

<style lang="scss">
    @import '../styles/variable.scss';
    .board-container{
        .boardItem{
            width: 68px;
            height: 68px;
            border: 2px solid $color-black;
        }
    }
</style>