<template>
    <div class="card mb-3">
        <div class="card-body">
            {{name}}
        </div>
    </div>
    <div>
        <button type="button" class="btn btn-primary btn-lg" @click="generate()">Generate</button>
    </div>
</template>

<script>
export default {
    name: "NameGenerator",
    data: function() {
        return {
            name: "Click on Generate",
            animals: ["Bear", "Giraffe", "Penguin", "Dog", "Shark"],
            adjectives: ["bald", "goofy", "prepared", "dangerous", "serious", "honorful"]
        }
    },
    methods: {
        generate() {
            // Implement Random logic here
            // Finish function by setting the name property to the generated name
            this.name = "This should be a variable with the generated name";
        }
    }
}
</script>

<style scoped>
.card {
    background-color: #313340;
    color: #eaeaeb;
}
</style>