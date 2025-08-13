<style>
    .image-container {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
        gap: 10px; /* 添加间距 */
    }

    .image-container img {
        width: calc(49% - 5px); /* 减去gap的一半 */
        height: auto; /* 保持宽高比 */
        margin-bottom: 1em;
    }
    
    .image-container img:nth-child(odd) {
        /* 奇数图片靠左 */
    }
    
    .image-container img:nth-child(even) {
        /* 偶数图片靠右 */
    }
    
    /* 如果某张图片需要占满整行 */
    .image-container img.full-width {
        width: 100%;
    }
    
    summary {
        font-size: 1.2em;
    }
</style>


<h2 style="display: flex;">  你好我是柠檬鱼蛋👋 </h2>
<img src="./picture/20241110_211243.jpg" align="right" width="165">
<p>很高兴你能看到这，鱼蛋是一只萌新，还请多多指教</p>

<li>想成为优秀的前端</li>
<li>ACGN爱好者</li>
<li>音游菜鸟(悲)</li>
<li>很多东西还在学习中</li>

<br>
<span>最后</span><br>
<span>鱼蛋最喜欢大家了！❤️</span>
<br>
<hr>
<details>
    <summary>some my loves</summary>
    <div class="image-container">
        <img src="./picture/124033921_p0.png">
        <img src="./picture/20241110_211358.jpg">
        <img src="./picture/20241124_025731.jpg">
        <img src="./picture/20241124_025911.jpg">
        <img src="./picture/288968f134d355eb.jpg">
        <img src="./picture/FA7JIIuVcAgvFSi.jpg">
        <img src="./picture/7373708108136ac0.jpg">
        <img src="./picture/79072089_p0.png">
        <img src="./picture/698374ffeb2bcb90.jpg" class="full-width">
    </div>
</details>

<!--
**lfegg/lfegg** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
