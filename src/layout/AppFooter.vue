<script setup>
import { computed } from 'vue';

const logoUrl = computed(() => {
    return `layout/images/logo.png`;
});
</script>

<template>
    <div class="layout-footer">
        <img :src="logoUrl" alt="Logo" height="20" class="mr-2" />
        <!-- by -->
        <span class="font-medium ml-2">© {{ new Date().getFullYear() }} ChatRPG</span>
        <span class="font-light ml-2">This page uses third-party software.</span>
    </div>
</template>
<style lang="scss" scoped></style>
