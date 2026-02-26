<script setup lang="ts">
import { ref } from 'vue'

const message = ref('Hello World!')
</script>

<template>
    <div class="my-custom-content">
        <CardMasonry>
            <img
                src="https://www.freedidi.com/wp-content/uploads/2026/02/1%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE-2026-02-23-202254-520x292.webp"
                alt="..."
            />
            <img
                src="https://www.freedidi.com/wp-content/uploads/2026/02/1%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE-2026-02-23-202254-520x292.webp"
                alt="..."
            />
            <img
                src="https://www.freedidi.com/wp-content/uploads/2026/02/1%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE-2026-02-23-202254-520x292.webp"
                alt="..."
            />
            <img
                src="https://www.freedidi.com/wp-content/uploads/2026/02/1%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE-2026-02-23-202254-520x292.webp"
                alt="..."
            />
            <img
                src="https://www.freedidi.com/wp-content/uploads/2026/02/1%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE-2026-02-23-202254-520x292.webp"
                alt="..."
            />

            <!-- 更多内容 -->
        </CardMasonry>
        <LinkCard title="卡片标题" href="/">
            - 这里是卡片内容 - 这里是卡片内容
        </LinkCard>

        <LinkCard href="/">
            <template #title>
                <span style="color: red">卡片标题</span>
            </template>

            - 这里是卡片内容 - 这里是卡片内容
        </LinkCard>
        <VPPosts />
        {{ message }}
    </div>
</template>
