---
layout: default
title: "网络故障排查指南：从 Wi-Fi、DNS 到延迟和丢包"
description: "网络出现问题时，先判断影响范围，再按 Wi-Fi、网页、DNS、网速、延迟、丢包或路由器现象进入对应排查流程。"
permalink: /
layout_class: home-page
---

<section class="hero">
<div class="hero-inner">
<div>
<p class="eyebrow">先判断，再处理</p>
<h1>网络故障排查指南</h1>
<p class="hero-lead">不要一上来就重置设备。先用另一台设备、另一个网站和一次基础测试，把问题缩小到设备、浏览器、家庭网络或外部服务。</p>
</div>
<div class="signal-panel">
<strong>三步确定方向</strong>
<ol>
<li>确认影响几台设备</li>
<li>更换网站或应用复测</li>
<li>记录错误提示与发生时间</li>
</ol>
</div>
</div>
</section>

<section class="section">
<h2>先回答这三个问题</h2>
<p class="section-intro">这三项测试不会修改任何设置，通常几分钟内就能确定应该查看哪一类指南。</p>
<ol class="triage-list">
<li>
<span class="triage-number">01</span>
<div>
<strong>只有一台设备有问题？</strong>
<p>同一网络下，另一台手机或电脑可以正常联网。</p>
</div>
<a href="{{ '/one-device-no-internet/' | relative_url }}">排查设备</a>
</li>
<li>
<span class="triage-number">02</span>
<div>
<strong>只有一个网页打不开？</strong>
<p>其他网站可以打开，或更换浏览器后结果不同。</p>
</div>
<a href="{{ '/website-not-opening/' | relative_url }}">排查网页</a>
</li>
<li>
<span class="triage-number">03</span>
<div>
<strong>所有设备都断网或变慢？</strong>
<p>重点检查路由器状态、入户线路和运营商服务。</p>
</div>
<a href="{{ '/router-network-troubleshooting/' | relative_url }}">排查家庭网络</a>
</li>
</ol>
</section>

<section class="section">
<h2>按现象进入排查</h2>
<p class="section-intro">每篇指南都从低风险检查开始，并说明测试结果代表什么。涉及删除配置、修改 DNS、网络重置或恢复出厂设置时，会先说明影响和恢复方法。</p>
<div class="guide-grid">
<a class="guide-link" href="{{ '/wifi-connected-no-internet/' | relative_url }}">
<small>连接状态</small>
<strong>Wi-Fi 已连接但无法上网</strong>
<span>判断是假连接、地址异常，还是路由器上游断网。</span>
</a>
<a class="guide-link" href="{{ '/website-not-opening/' | relative_url }}">
<small>浏览器与网站</small>
<strong>网页打不开</strong>
<span>区分网站故障、浏览器问题、公共网络认证和解析异常。</span>
</a>
<a class="guide-link" href="{{ '/dns-troubleshooting/' | relative_url }}">
<small>域名解析</small>
<strong>DNS 异常</strong>
<span>用错误现象、查询结果和设备对照判断解析环节。</span>
</a>
<a class="guide-link" href="{{ '/internet-slow-troubleshooting/' | relative_url }}">
<small>连接速度</small>
<strong>网速突然变慢</strong>
<span>按服务、设备、无线信号和上游线路逐层定位。</span>
</a>
<a class="guide-link" href="{{ '/network-latency-test/' | relative_url }}">
<small>响应质量</small>
<strong>延迟和抖动测试</strong>
<span>比较本地网关和外部目标，判断卡顿与波动来源。</span>
</a>
<a class="guide-link" href="{{ '/packet-loss-test/' | relative_url }}">
<small>连接稳定性</small>
<strong>网络丢包测试</strong>
<span>正确读取连续测试，避免被单次超时误导。</span>
</a>
<a class="guide-link" href="{{ '/one-device-no-internet/' | relative_url }}">
<small>设备范围</small>
<strong>只有一台设备无法上网</strong>
<span>检查地址、代理、DNS、接入限制和网络记录。</span>
</a>
<a class="guide-link" href="{{ '/router-network-troubleshooting/' | relative_url }}">
<small>家庭网络</small>
<strong>路由器网络异常</strong>
<span>从影响范围、指示灯、供电、线路和重启顺序开始。</span>
</a>
</div>
</section>

<section class="section">
<h2>测试值只是线索，不是单独结论</h2>
<p class="section-intro">速度、延迟、抖动和丢包描述的是不同问题。测试时应记录连接方式、设备、测试对象和发生时间，并在相同条件下复测，才能判断变化来自哪里。</p>
<p><a href="{{ '/network-quality/' | relative_url }}">了解速度、延迟、抖动和丢包应该怎样一起看</a></p>
</section>

<section class="section">
<h2>这些情况不要继续自行操作</h2>
<p class="section-intro">设备出现异常高温、焦味、冒烟、进水、外壳变形或反复断电时，应立即断开电源并联系售后。光纤折断、接口损坏或光猫持续显示该型号说明书定义的线路告警时，应联系运营商。</p>
<p>公司、学校和其他受管理的网络应优先联系管理员，不要擅自修改代理、DNS、固定地址、路由器或安全配置。</p>
<p><a href="{{ '/about/' | relative_url }}">查看本站的内容范围与操作安全原则</a></p>
</section>
