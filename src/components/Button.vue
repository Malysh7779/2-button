<script setup>
</script>

<template>
    <button class="button">
        <slot></slot>
    </button>
</template>

<style scoped>
.button {
    background-color: var(--color-bg-button);
    color: var(--color-button);
    border: none;
    border-radius: 100px;
    padding: 16px 10px;
    font-size: 24px;
    font-weight: 400;
    width: 335px;
    cursor: pointer;
}
.button:hover {
    color: var(--color-bg-button);
    background: var(--color-button);
}
</style>