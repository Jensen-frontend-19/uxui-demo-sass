<template>
    <div class="home">
        <Upcoming />
    </div>
</template>

<script>
// @ is an alias to /src
import Upcoming from '@/components/upcoming/Upcoming.vue'

export default {
    name: 'Home',
    components: {
        Upcoming
    }
}
</script>
