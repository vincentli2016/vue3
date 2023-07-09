<script setup>
import { useRoute, useRouter } from 'vue-router';
const route = useRoute()
const router = useRouter()

const cardId = parseInt(route.params.id)

</script>
<template>
    <div>
        <h1>Quiz View</h1>
        {{ cardId }}
    </div>
</template>