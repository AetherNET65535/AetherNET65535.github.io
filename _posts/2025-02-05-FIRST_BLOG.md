---
layout:     post
title:      "最小内核开发-00"
subtitle:   " \"TINY KERNEL DEVELOPMENT\""
date:       2025-02-11 00:00:00
author:     "AetherNET"
header-img: "img/post-bg-2015.jpg"
catalog: true
tags:
    - KERNEL
---

# 我的第一个长期项目 (๑•̀ㅂ•́)و✧ 

发表于：2025.02.11
---
### 25.02.11
最近，我开始学习汇编，因为这个项目得用到。汇编有点难，不过先懂得怎么用就行，从输出字符串开始，慢慢到输入，计算什么的，应该能行。<br>
|･ω･｀)<br>

然后还学会了makefile，这玩意儿是真的好用，本来一直要CTRL + SHIFT + B，然后汇编的话还要从o文件转换为可执行文件，都给我干成肌肉记忆了，不过现在有makefile了，所以很方便，创造makefile的人真的是甜菜！<br>
ヽ(✿ﾟ▽ﾟ)ノ<br>
---

### 2025.02.14
## 今天的汇编学习 ٩(｡・ω・｡)و：
主要学了 CMP、BYTE 和一些 JMP 的变体，JMP 的分支指令真的太多了，有点难记，但只要认真看，多敲几遍，应该问题不大。<br>
时间有点晚了，明天再继续折腾～<br>

<button onclick="toggleContent('hidden-content-1')">今日的代码之外</button>

<div id="hidden-content-1" style="display: none;">
  {{ content | markdownify }}
</div>

<script>
function toggleContent(id) {
    var content = document.getElementById(id);
    if (content.style.display === "none") {
        content.style.display = "block";
    } else {
        content.style.display = "none";
    }
}
</script>

{% capture content %}
## 最近在VMware装了Arch，初体验还不错，但有些小问题。 ( ˘•ω•˘ )
比起Ubuntu，Arch有点卡顿，可能KDE本身就比较吃资源，WayLand很卡，30fps左右，X11则是45-60左右，但加载有点慢，能接受。<br>

```
我的虚拟机配置是：
RAM 8GB
CPU 8核 (R5 5600H)
GTX 1650 8GB显存
```

不确定是我装的有问题还是什么，也有可能是CPU本来就差，我对硬件还没那么了解。<br>
(°ー°〃)<br>

## 弄了个《主播少女重度依赖》的主题 (๑•̀ω•́)ノ
有种老WINDOWS的美，我挺喜欢的。<br>
总之，ARCH还挺好用的，KDE PLASMA X11的话，GNOME不确定，没装很久，暂时也不打算。<br>
{% endcapture %}
---

### 2025.02.23
## 最近在汇编里写了计算器（正整数加法器）(・∀・)
有点难，汇编，在学校里用课余时间，写了一些伪代码，回到家里后抄进去，能编译，我还以为就这样结束了。<br>
不过汇编怎么可能那么容易呢，最后给我报了个SEGFAULT，那我肯定是赶紧修了呀，不过最后也没修好。<br>
(・へ・)<br>

最后我把代码丢给CLAUDE，让他生成一个更好的，然后我就阅读一下。截至目前这个时间，我已经读好了（当然，也理解了），还手工做了个小小的栈。<br>

![MYSTACK](/img/in-post/FIRST_BLOG/photo_2025-02-23_02-46-38.jpg)

还挺好看！<br>
(*´艸`*)<br>


<button onclick="toggleContent('hidden-content-1')">今日的代码之外</button>

<div id="hidden-content-1" style="display: none;">
  {{ content | markdownify }}
</div>

<script>
function toggleContent(id) {
    var content = document.getElementById(id);
    if (content.style.display === "none") {
        content.style.display = "block";
    } else {
        content.style.display = "none";
    }
}
</script>

{% capture content %}
## 有点想买THINKPAD X201
这个机子真的，好帅！虽然他本来就是2010的机子，不过...反正就是很帅！<br>
找到了个700的i5版本，明天试试和父母问问，看能不能买，如果可以的话我就去问店家那个键盘和屏幕的情况，如果没有大问题我就直接入手了。<br>
不过我觉得大概是会有问题的，2010的机子嘛，多多少少应该是有问题的，只是希望不要有大问题而已！<br>
{% endcapture %}
---

### 2025.03.05
## 汇编计算器升级了
升级到了整数计算器，是（A O B = C）的类型，比较简单，最难的部分是写防呆代码。<br>

## 战败遣返C语言了
在C语言里做了个显式表达式整数计算器，刚刚写好，一开始还有点不习惯，要写“;”。<br>

<button onclick="toggleContent('hidden-content-1')">今日的代码之外</button>

<div id="hidden-content-1" style="display: none;">
  {{ content | markdownify }}
</div>

<script>
function toggleContent(id) {
    var content = document.getElementById(id);
    if (content.style.display === "none") {
        content.style.display = "block";
    } else {
        content.style.display = "none";
    }
}
</script>

{% capture content %}
## 买了THINKPAD X220，帅！(๑•̀ㅂ•́)و✧ 
不买X201了，买X220，反正也是7行键盘，而且才200，不过加上升级的钱就得700左右了。<br>
( ˘•ω•˘ )
在上面装了个ARCH LINUX，PLASMA WAYLAND的，基本和之前的虚拟机一致吧，除了虚拟机用X11，X220用WAYLAND以外。<br>
{% endcapture %}




