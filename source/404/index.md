---
title: 404
date: 2020-12-30 18:41:45
toc: false
comments: false
permalink: /404.html
---

<!-- markdownlint-disable MD039 MD033 -->

## OOPS! 404, page not found...

很抱歉，您目前存取的頁面並不存在。

本頁面將於 <span id="timeout">5</span> 秒後返回首頁。

或點選 **[HOME](https://heidiliu2020.github.io/)** 直接返回。

<script>
let countTime = 5;

function count() {
  
  document.getElementById('timeout').textContent = countTime;
  countTime -= 1;
  if(countTime === 0){
    location.href = 'https://heidiliu2020.github.io/'; 
  }
  setTimeout(() => {
    count();
  }, 1000);
}

count();
</script>
