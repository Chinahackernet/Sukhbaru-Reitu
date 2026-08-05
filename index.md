---
# https://vitepress.dev/reference/default-theme-home-page
layout: home
layoutClass: 'm-home-layout'

hero:
  name:name: "赛伦斯's Blog <sup><Badge type='tip' text='分享技术，感悟人生' class='small'/></sup>"
  tagline: "愿做人间逍遥客，从此江湖无故人 ：）"
  image:
    src: /background.png
    alt: background
  actions:
    - theme: brand
      text: 进入博客
      link: /blog
    - theme: alt
      text: 进入仓库
      link: https://github.com/yqchilde/MyNewBlog

features:
  - icon: 📖
    title: 运维笔记
    details: 整理运维常用知识点<small>  </small><br />
    link: /review
    linkText: 运维常用知识
  - icon: 💡
    title: Workflow
    details: 在运维工作中用到的一切<small>（常用库/工具/奇淫技巧等）</small><br />提高工作效率
    link: /workflow/style-guide
    linkText: 常用工具库
  - icon: 🧰
    title: 提效工具
    details: 工欲善其事，必先利其器<br />记录运维日常使用中所用到的软件、插件、扩展等
    link: /efficiency/mac
    linkText: 提效工具
---

<ClientOnly><Heatmap /></ClientOnly>

<style>
.m-home-layout .image-src:hover {
  transform: translate(-50%, -50%) rotate(666turn);
  transition: transform 59s 1s cubic-bezier(0.3, 0, 0.8, 1);
}

.m-home-layout .details small {
  opacity: 0.8;
}

.m-home-layout .item:last-child .details {
  display: flex;
  justify-content: flex-end;
  align-items: end;
}

@media (min-width: 768px) {
  .VPHome {
    margin-bottom: 50px !important;
  }
}
</style>
