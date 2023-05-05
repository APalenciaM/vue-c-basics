<template>
    <div>
        <ul>
            <li v-for="item in myObject" ref="objects">
            {{ item }}
            </li>
        </ul>
    </div>
</template>

<script>
export default {
    data(){
        return {
            name: 'Bucle',
            myObject: {
                title: "I'm a title",
                desciption: "I'm a description",
                content: "I'm the content"
            }
                
        }
    },
    mounted() {
        console.log(this.$refs.objects)
    }
}
</script>

<style scoped>

</style>