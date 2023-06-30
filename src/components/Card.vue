<template>
    <div class="card card-style">
        <div>
            <h4>{{model.title}}</h4>
            <p>{{model.desc}}</p>
        </div>
        <div>
            <!-- V-if/else: Checking the status of a task and showing according button -->
            <button v-if="!model.status">Add</button> 
            <button v-else>Delete</button>
        </div>
    </div>
</template>

<script>
export default {
    props: {
        model: { 
            required: true, // Making our model neccessery
            default: {
                id: 0,
                title: `Create`,
                desc: `Create project`,
                status: false // Prop for a button display
            }
        }
    },
    setup () {
        

        return {}
    }
}
</script>

<style lang="scss" scoped>

</style>