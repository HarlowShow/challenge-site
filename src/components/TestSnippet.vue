<template>
    <div class="container">
    <h3>Welcome to the test snippet!</h3>
    <p>What is the test var? It's {{ testVar }}</p>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
    setup() {
        const testVar: number = 5;
        return {
            testVar
        }
    },
})
</script>
