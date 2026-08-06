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
      text: 用技术解决问题，用分享创造价值
      link: /blog
    - theme: alt
      text: 作战系统
      link: https://donhackernet.pages.dev

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
    title: 攻防对抗
    details: 那些年我们踩过的坑<br />威胁狩猎大合集
    link: /reverse-engineering/js
    linkText: JS逆向从入门到放弃。
  - icon: 💯
    title: 吾志所向，一往无前。
    details: '<small class="bottom-small">一个想躺平的运维</small>'
    link: /about
---

<div class="affiliation">

  <img src="/logo.png" alt="Logo" class="affiliation-logo" />

  <div class="affiliation-content">

      本站隶属于中国黑客联盟、中国鹰眼网络安全技术组织联盟成员；
	  坚持合法、合规、负责任的网络安全研究与技术交流；  
      网络的路不止一条，所有的信息都应是免费的，打破权限，创造生活更美好，有信念、有梦想；   
      坚信只有今天付出了，才有机会看到明天的太阳；
      极客是一种精神，它代表着热爱祖国、坚持正义、开拓进取；
	  凡是热爱计算机技术、勇于探索的人，都可以称之为极客；
      倡导绿色文明健康网络，守护国民信息安全。
	  
  </div>

</div>

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

/* ===============================
   首页底部：技术理念
================================= */

.affiliation {
  display: flex;
  align-items: center;
  gap: 24px;
  max-width: 900px;
  margin: 60px auto;
  padding: 28px;
  border: 1px solid var(--vp-c-divider);
  border-radius: 16px;
  background: var(--vp-c-bg-soft);
  box-shadow: var(--vp-shadow-1);
}

.affiliation-logo {
  width: 120px;
  height: 120px;
  object-fit: contain;
  border-radius: 12px;
  flex-shrink: 0;
}

.affiliation-content {
  flex: 1;
  color: #d32f2f; /* 红色文字 */
}

.affiliation-content h3 {
  margin: 0 0 18px;
  color: #d32f2f;
  font-size: 24px;
  font-weight: 700;
}

.affiliation-content p {
  margin: 10px 0;
  line-height: 1.9;
  color: #d32f2f;
  font-size: 15px;
}

.affiliation-content strong {
  color: #ff0000;
}

.affiliation-content a {
  color: #ff4d4f;
  text-decoration: none;
}

.affiliation-content a:hover {
  text-decoration: underline;
}

/* 暗色模式 */
.dark .affiliation {
  background: rgba(255, 255, 255, 0.03);
  border-color: rgba(255, 255, 255, 0.08);
}

/* 手机端 */
@media (max-width: 768px) {
  .affiliation {
    flex-direction: column;
    text-align: center;
    padding: 20px;
    margin: 40px 16px;
  }

  .affiliation-logo {
    width: 90px;
    height: 90px;
  }

  .affiliation-content h3 {
    font-size: 20px;
  }

  .affiliation-content p {
    font-size: 14px;
    line-height: 1.8;
  }
}
</style>