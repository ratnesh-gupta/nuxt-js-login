<template>
    
    <div class="custom">
        <slot />
    </div>
</template>


<style scoped>
.custom {
    height: 100vh;
}

.custom::before {
    position: absolute;
    color: #583ccb;
    font-family: monospace;
}
</style>