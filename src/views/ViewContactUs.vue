<script>
import ComponentContact from '@/components/ComponentContact.vue';
import ComponentFeedback from '@/components/ComponentFeedback.vue';

export default {
    components: {
        ComponentContact,
        ComponentFeedback
    }
}

</script>

<template>
    <div class="container main-container">
        <ComponentContact />
        <ComponentFeedback />
    </div>
</template>

<style scoped>
.main-container {
    display: flex;
    margin-top: 60px;
    padding: 0px;
    background: inherit;
}

@media screen and (max-width: 991px) {

    .main-container {
        display: flex;
        flex-direction: column;
        margin-top: 0;
    }


}
</style>