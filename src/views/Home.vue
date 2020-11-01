<template>
    <div>
        <Counter
        :year="2020"
        :month="10"
        :date="1"
        :hour="19"
        :minute="0"
        :second="0"
        :millisecond="0"
        />
    </div>
</template>

<script>
import Counter from '@/components/Counter.vue'
    export default {
        components: {
            Counter
        }
    }
    
</script>

<style lang="scss" scoped>

</style>