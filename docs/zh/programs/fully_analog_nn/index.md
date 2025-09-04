
# **基于模拟存内计算硬件的全模拟域人工神经网络（FNN,RNN,CNN）**

<style>
.video-section {
  text-align: center;
  padding: 40px 20px;
}
.video-section h2 {
  font-weight: bold;
  margin-bottom: 20px;
}
.video-wrapper video {
  max-width: 80%;
  border-radius: 8px;
  box-shadow: 0 0 15px rgba(0,0,0,0.3);
  transition: all 0.3s ease;
}
.video-wrapper video:hover {
  box-shadow: 0 0 25px rgba(0,0,0,0.6);
}
</style>

---

## **全模拟域全连接神经网络**

### **全模拟域全连接神经网络的实现**

通过模拟存内计算阵列与非线性电路（实现非线性激活函数的左右）构成可级联的硬件全连接神经层。

![](./images/analog_fnn.jpg)

### **全模拟域全连接神经网络的应用--机器人的感知、规划与运动**

<div class="video-section">
  <h3>基于全模拟域全连接神经网络实现感知、规划、完成指定任务</h3>
  <div class="video-wrapper">
    <video controls>
      <source src="./images/fnn_demo.mp4" type="video/mp4">
      您的浏览器不支持 HTML5 视频，请使用现代浏览器。
    </video>
  </div>
</div>

### **对应成果**

Self-adaptive embodied neuromorphic intelligence using in-memory computing hardware

**Z-Z Yang†**, H Zhao†, Y-C Zhao, et al.

**Science Robotics** (Under review)

---

## **全模拟域循环神经网络**

### **全模拟域循环神经网络的实现**

利用微分方程与RNN的联系，基于模拟存内计算阵列与积分电路构建一阶微分方程描述的动力学系统，实现可级联的硬件循环神经层。

![](./images/analog_rnn.jpg)

### **基于全模拟域RNN实现声纹识别**

![](./images/analog_rnn_demo.jpg)

### **全模拟域LSTM的实现**

为积分电路的反馈回路加入可控的”门“，即可实现可级联的硬件LSTM神经层

![](./images/analog_lstm.jpg)

### **基于全模拟域LSTM实现手写轨迹识别**

![](./images/analog_lstm_demo.jpg)

### **对应成果**

**Physical dynamic neural networks for efficient temporal information processing** (To be submitted)

C Wang†, **Z-Z Yang†**, Y-M Zhu, et al. (To be submitted)

---

## **全模拟域卷积神经网络**

### **全模拟域卷积神经网络的实现**

基于模拟存内计算阵列与电压保持电路，经合理的时序控制，可以实现实现可级联的硬件卷积神经层。

![](./images/analog_cnn.jpg)

电压保持电路（analog buffer）

![](./images/sample_hold.jpg)

---
