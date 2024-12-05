<script setup>
    import { Link } from '@inertiajs/vue3';
</script>

<template>
    Inertiaテストです。<br>
    <a href="/">aタグでWelcomeに移動</a><br>
    <Link href="/">LinkでWelcomeに移動</Link><br>

    <Link :href="route('inertia.index')">名前付きルートの確認です</Link><br>
    <Link :href="route('inertia.show', { id: 51 })">ルートパラメータのテストです</Link>

</template>