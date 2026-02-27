<script setup>
import { Layout } from 'vuepress-theme-plume/client'
</script>

<template>
    <Layout>
        <template #posts-post-list-pagination-after>
            <div class="custom-content">自定义内容</div>
        </template>
        <template #posts-aside-bottom>
            <div class="custom-content">自定义内容</div>
        </template>
    </Layout>
</template>

<style>
.custom-content {
    width: 100%;
}
</style>
