<template>
    <div>
        news
    </div>
</template>

<script>
import axios from 'axios';

export default {
    created() {
        axios.get('users')
            .then()
            .catch()
    }
}
</script>

<style>

</style>
