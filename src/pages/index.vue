<template>
    <div class="page">
        Index페이지
        <BasicLayout>
            <div class="page__container">
                <section class="page__container__navigation"></section>
                <section class="page__container__notice"></section>
            </div>
        </BasicLayout>
    </div>
</template>

<script setup lang="ts">
import BasicLayout from '@components/atoms/layout/BasicLayout.vue';
</script>

<style lang="scss" scoped>
    
.page {
    display: flex;
    align-items: center;
    justify-content: center;

    width: 100%;
    height: 100%;

    background-color: $color-black-900;
}

</style>