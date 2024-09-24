<script setup>
const loading = ref(false)
</script>

<template>
    <div class="relative">
    <div class="flex lg:hidden">
        <SidebarMenu />
    </div>
    <div class="hidden lg:flex">
        <SidebarMenu />
    </div>
    </div>
</template>