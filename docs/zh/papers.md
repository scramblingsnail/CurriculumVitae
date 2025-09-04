
<style>

/* 论文方框 */
.paper-box {
  background: #f7f7f7;
  padding: 20px;
  margin: 20px auto;
  border-radius: 8px;
  position: relative;
  max-width: 800px;
  box-shadow: 0 8px 16px rgba(0,0,0,0.1);
}

/* 方框内文字 */
.paper-box p {
  margin: 5px 0;
}

/* 图标容器 */
.icon-container {
  position: absolute;
  bottom: 1px;
  right: 2px;
  display: flex;
  gap: 10px;
}

/* 图标链接 */
.icon-link {
  position: relative;
  display: inline-block;
  transition: all 0.3s ease;
}
.icon-link img {
  height: 30px; /* 假设方框高度大约 240px，则 1/4 高度 = 60px */
  transition: all 0.3s ease;
  border-radius: 6px;
}
.icon-link:hover img {
  transform: scale(1.1);
  box-shadow: 0 0 10px rgba(0,0,0,0.4);
}

/* 悬浮文字提示 */
.icon-link .tooltip {
  visibility: hidden;
  opacity: 0;
  width: max-content;
  background: black;
  color: white;
  text-align: center;
  padding: 4px 8px;
  border-radius: 6px;
  position: absolute;
  bottom: 110%;
  left: 50%;
  transform: translateX(-50%);
  transition: opacity 0.3s;
  font-size: 14px;
  white-space: nowrap;
}
.icon-link:hover .tooltip {
  visibility: visible;
  opacity: 1;
}
</style>

---
# **第一作者/共同第一作者论文**
<div class="paper-box">
  <p><strong>论文标题：</strong> Communication-aware in-memory wireless neural networks</p>
  <p><strong>作者：</strong> <strong>Z-Z Yang</strong>, C Wang, Y-C Zhao, et al.</p>
  <p><strong>期刊：</strong> <strong>Nature Electronics</strong> (Major Revision)</p>
  <div class="icon-container">
    <a href="https://github.com/scramblingsnail/Communication-aware-training" class="icon-link" target="_blank">
      <img src="../assets/code_icon.png" alt="代码仓库" width=30px height=5px>
      <span class="tooltip">代码仓库</span>
    </a>
    <a href="https://github.com/scramblingsnail/CurriculumVitae/tree/master/docs/assets/pdf/Communication-aware in-memory wireless neural networks.pdf" class="icon-link" target="_blank">
      <img src="../assets/paper_icon.png" alt="论文地址">
      <span class="tooltip">论文地址</span>
    </a>
  </div>
</div>

<div class="paper-box">
  <p><strong>论文标题：</strong> Self-adaptive embodied neuromorphic intelligence using in-memory computing hardware</p>
  <p><strong>作者：</strong> <strong>Z-Z Yang†</strong>, H Zhao†, Y-C Zhao, et al.</p>
  <p><strong>期刊：</strong> <strong>Science Robotics</strong> (Under Review)</p>
  <div class="icon-container">
    <a href="https://github.com/scramblingsnail/AnalogFNNForRobot" class="icon-link" target="_blank">
      <img src="../assets/code_icon.png" alt="代码仓库" width=30px height=5px>
      <span class="tooltip">代码仓库</span>
    </a>
    <a href="https://github.com/scramblingsnail/CurriculumVitae/tree/master/docs/assets/pdf/Self-adaptive embodied neuromorphic intelligence using in-memory computing hardware.pdf" class="icon-link" target="_blank">
      <img src="../assets/paper_icon.png" alt="论文地址">
      <span class="tooltip">论文地址</span>
    </a>
  </div>
</div>

<div class="paper-box">
  <p><strong>论文标题：</strong> A Braitenberg vehicle based on memristive neuromorphic circuits.</p>
  <p><strong>作者：</strong> C Wang†, <strong>Z-Z Yang†</strong>, S Wang, et al. </p>
  <p><strong>期刊：</strong> Advanced Intelligent Systems, 2020, 2(1): 1900103.</p>
  <div class="icon-container">
    <a href="" class="icon-link" target="_blank">
      <img src="../assets/code_icon.png" alt="代码仓库" width=30px height=5px>
      <span class="tooltip">无相关代码</span>
    </a>
    <a href="https://advanced.onlinelibrary.wiley.com/doi/10.1002/aisy.201900103" class="icon-link" target="_blank">
      <img src="../assets/paper_icon.png" alt="论文地址">
      <span class="tooltip">论文地址</span>
    </a>
  </div>
</div>

<div class="paper-box">
  <p><strong>论文标题：</strong>  Efficient and generalizable memristor programming strategies based on reinforcement learning</p>
  <p><strong>作者：</strong> <strong>Z-Z Yang</strong>, et al.</p>
  <p><strong>期刊：</strong>In preparation</p>
  <div class="icon-container">
    <a href="https://github.com/scramblingsnail/RLReRAMPolicy" class="icon-link" target="_blank">
      <img src="../assets/code_icon.png" alt="代码仓库" width=30px height=5px>
      <span class="tooltip">代码仓库</span>
    </a>
    <a href="" class="icon-link" target="_blank">
      <img src="../assets/paper_icon.png" alt="论文地址">
      <span class="tooltip">写作中</span>
    </a>
  </div>
</div>

<div class="paper-box">
  <p><strong>论文标题：</strong>  Physical dynamic neural networks for efficient temporal information processing</p>
  <p><strong>作者：</strong> C Wang†, <strong>Z-Z Yang†</strong>, Y-M Zhu, et al.</p>
  <p><strong>期刊：</strong> To be submitted</p>
  <div class="icon-container">
    <a href="" class="icon-link" target="_blank">
      <img src="../assets/code_icon.png" alt="代码仓库" width=30px height=5px>
      <span class="tooltip">代码仓库</span>
    </a>
    <a href="" class="icon-link" target="_blank">
      <img src="../assets/paper_icon.png" alt="论文地址">
      <span class="tooltip">待投稿</span>
    </a>
  </div>
</div>

---
# **其它论文**
<div class="paper-box">
  <p><strong>论文标题：</strong> Parallel in-memory wireless computing</p>
  <p><strong>作者：</strong> C Wang†, G-J Ruan†, <strong>Z-Z Yang</strong>, et al. （第二作者）</p>
  <p><strong>期刊：</strong> <strong>Nature Electronics</strong> 6, 381-389 (2023)</p>
  <div class="icon-container">
    <a href="https://www.nature.com/articles/s41928-023-00965-5" class="icon-link" target="_blank">
      <img src="../assets/paper_icon.png" alt="论文地址">
      <span class="tooltip">论文地址</span>
    </a>
  </div>
</div>

<div class="paper-box">
  <p><strong>论文标题：</strong> Selective and quasi-continuous switching of ferroelectric Chern insulator devices for neuromorphic computing</p>
  <p><strong>作者：</strong> M-Y Chen†, Y-Q Xie†, B Cheng, <strong>Z-Z Yang</strong>, et al. （学生第二作者）</p>
  <p><strong>期刊：</strong> <strong>Nature Nanotechnology</strong> 19, 962-969 (2024)</p>
  <div class="icon-container">
    <a href="https://github.com/zhangsan/paper1" class="icon-link" target="_blank">
      <img src="../assets/code_icon.png" alt="代码仓库" width=30px height=5px>
      <span class="tooltip">代码仓库</span>
    </a>
    <a href="https://www.nature.com/articles/s41565-024-01698-y" class="icon-link" target="_blank">
      <img src="../assets/paper_icon.png" alt="论文地址">
      <span class="tooltip">论文地址</span>
    </a>
  </div>
</div>

<div class="paper-box">
  <p><strong>论文标题：</strong> Scalable massively parallel computing using continuous-time data representation in nanoscale crossbar array</p>
  <p><strong>作者：</strong> C Wang†, S-J Liang†, C-Y Wang, <strong>Z-Z Yang</strong>, et al. （第三作者）</p>
  <p><strong>期刊：</strong> <strong>Nature Nanotechnology</strong> 16, 1079-1085 (2021)</p>
  <div class="icon-container">
    <a href="https://www.nature.com/articles/s41565-021-00943-y" class="icon-link" target="_blank">
      <img src="../assets/paper_icon.png" alt="论文地址">
      <span class="tooltip">论文地址</span>
    </a>
  </div>
</div>

<div class="paper-box">
  <p><strong>论文标题：</strong> Ultrahigh-precision analog computing using memory-switching geometric ratio of transistors</p>
  <p><strong>作者：</strong> X-J Yangdong†, C Wang†, Y-C Zhao†, Z-C Wang, <strong>Z-Z Yang</strong>, et al. （第三作者）</p>
  <p><strong>期刊：</strong> <strong>Science Advances</strong> (Accepted)</p>
  <div class="icon-container">
    <a href="" class="icon-link" target="_blank">
      <img src="../assets/paper_icon.png" alt="论文地址">
      <span class="tooltip">已接收</span>
    </a>
  </div>
</div>

<div class="paper-box">
  <p><strong>论文标题：</strong> Training Analogue AI Hardware with Single Forward Propagation </p>
  <p><strong>作者：</strong> Wang C†, Zhao Y C†, Yangdong X J, <strong>Z-Z Yang</strong>, et al. （第三作者）</p>
  <p><strong>期刊：</strong> <strong>Nature</strong> (Under Review)</p>
  <div class="icon-container">
    <a href="" class="icon-link" target="_blank">
      <img src="../assets/paper_icon.png" alt="论文地址">
      <span class="tooltip">Under Review</span>
    </a>
  </div>
</div>

<div class="paper-box">
  <p><strong>论文标题：</strong> Mortise-tenon–shaped memristors for scientific computing</p>
  <p><strong>作者：</strong> W-Q Dang†, Y Shen†, W Wei†, C Pan, F-Q Chen, G-J Ruan, Y Luo, Y Guo, Q-Y Tan, J-W Shi, X-J Yangdong, S-C Chen, C Wang, Y-Q Xie, Z-Z Yang</p>
  <p><strong>期刊：</strong> Science Advances 11, eadu3309 (2025)</p>
  <div class="icon-container">
    <a href="https://www.science.org/doi/10.1126/sciadv.adu3309" class="icon-link" target="_blank">
      <img src="../assets/paper_icon.png" alt="论文地址">
      <span class="tooltip">论文地址</span>
    </a>
  </div>
</div>

<div class="paper-box">
  <p><strong>论文标题：</strong> Skin‐Inspired in‐Sensor Encoding of Strain Vector Using Tunable Quantum Geometry</p>
  <p><strong>作者：</strong> Z-L Liu†, J-W Shi†, J Cao, Z-C Ma, Z-Z Yang, et al. </p>
  <p><strong>期刊：</strong> Advanced Functional Materials 35.9: 2416204 (2025) (Under Review)</p>
  <div class="icon-container">
    <a href="https://advanced.onlinelibrary.wiley.com/doi/10.1002/adfm.202416204" class="icon-link" target="_blank">
      <img src="../assets/paper_icon.png" alt="论文地址">
      <span class="tooltip">论文地址</span>
    </a>
  </div>

</div>
