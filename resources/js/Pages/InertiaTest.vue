<script setup>
import { Link } from '@inertiajs/inertia-vue3';
</script>

<template>
Inertiaテストです。<br>
<a href="/">aタグ経由</a><br>
<Link href="/">Link経由</Link><br>
<!-- 名前付きルートを指定できる -->
<Link :href="route('inertia.index')">名前付きルートの確認</Link><br>
</template>