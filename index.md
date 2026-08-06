---
# https://vitepress.dev/reference/default-theme-home-page
layout: home
layoutClass: 'm-home-layout'

hero:
  name: "赛伦斯's Blog <sup><Badge type='tip' text='分享技术，感悟人生' class='small'/></sup>"
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
    title: 运维工具
    details: 在运维工作中用到的一切<small>（常用库/工具/奇淫技巧等）</small><br />提高工作效率
    link: /workflow/style-guide
    linkText: 太好了，有时间更新
  - icon: 🧰
    title: 提效工具
    details: 工欲善其事，必先利其器<br />记录运维日常使用中所用到的软件、插件、扩展等
    link: /efficiency/mac
    linkText: 提效工具
  - icon: 📘
    title: OpenAI
    details: 批量获取<br />刷新sess，refresh_token，及账号测活
    link: /softs/openai
    linkText: Obsidian账号注册机
  - icon: 🐞
    title: Js逆向
    details: 那些年我们踩过的坑<br />总有一些让你意想不到的问题
    link: /reverse-engineering/js
    linkText:JS逆向从入门到放弃。
  - icon: 💯
    title: 吾志所向，一往无前。
    details: '<small class="bottom-small">一个想躺平的运维</small>'
    link: /about
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
