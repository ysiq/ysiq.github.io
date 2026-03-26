---
layout: default
title: 联系我们
---

<section class="contact">
    <h2>联系方式</h2>
    <div class="contact-info">
        <p>邮箱: contact@example.com</p>
        <p>电话: 123-456-7890</p>
        <p>地址: 北京市朝阳区</p>
    </div>
    <h3>发送消息</h3>
    <form class="contact-form">
        <div class="form-group">
            <label for="name">姓名</label>
            <input type="text" id="name" name="name" required>
        </div>
        <div class="form-group">
            <label for="email">邮箱</label>
            <input type="email" id="email" name="email" required>
        </div>
        <div class="form-group">
            <label for="message">消息</label>
            <textarea id="message" name="message" required></textarea>
        </div>
        <button type="submit">发送</button>
    </form>
</section>