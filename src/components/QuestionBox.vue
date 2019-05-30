<template>
    <div>
        <b-jumbotron>
            <template slot="lead">
              {{Currentquestion.question}}
            </template>

            <hr class="my-4">

            <p>
               List Of Answers
            </p>

            <b-button variant="primary" href="#">Submit</b-button>
            <b-button variant="success" href="#">Next</b-button>
        </b-jumbotron>
    </div>
</template>

<script>
    export default {
        props:{
            Currentquestion: Object
        }
    }
</script>

<style scoped>

</style>