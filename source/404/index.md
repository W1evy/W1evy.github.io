---
title: '404 - 好巧，竟然在这里遇到你！'
date: 2022-01-22 20:02:00
comments: false

permalink: /404.html

---



<!-- markdownlint-disable MD039 MD033 -->

## 这是一个不存在的页面

对不起，您所访问的页面不存在或者已删除。

预计将在约 <span id="timeout">3</span> 秒后返回首页。

你可以 [点这里](https://w1evy.github.io/) 直接返回首页。

<script>

let countTime = 3;



function count() {

  document.getElementById('timeout').textContent = countTime;
  countTime -= 1;
  if(countTime === 0){
    location.href = "https://w1evy.github.io/";
  }
  setTimeout(() => {
    count();
  }, 1000);
}

count();
</script>
