---
layout: home

title: Front-end Notes
titleTemplate: Library

hero:
  name: Front-end Notes
  text: ''
  tagline: 前端笔记文档1112223334444555
  image:
    src: /logo-with-shadow.png
    alt: Front-end Notes
  actions:
    - theme: brand
      text: Get Started
      link: /vue2/note-1
    - theme: alt
      text: View on GitHub
      link: https://github.com/liulihao88/front-end-notes
---

<script setup lang="ts">
import { onMounted } from 'vue'
import { fetchVersion } from './.vitepress/utils/fetchVersion'

onMounted(() => {
  fetchVersion()
})
</script>
