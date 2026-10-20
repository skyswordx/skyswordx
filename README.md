<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg" />
    <img src="assets/banner-light.svg" alt="CircLΣMoon · Embedded · Robotics · Edge AI" width="100%" />
  </picture>
</p>

<p align="center">
  <a href="https://www.circlemoon.top"><img src="https://img.shields.io/badge/Blog-circlemoon.top-3B915D?style=for-the-badge" alt="Blog" /></a>
  <img src="https://img.shields.io/badge/SYSU-SEIT-005826?style=for-the-badge" alt="SYSU SEIT" />
  <img src="https://img.shields.io/badge/Guangzhou-China-111827?style=for-the-badge" alt="Guangzhou, China" />
</p>

I work where firmware meets robots — MCU drivers, RTOS and DSP on one end, robot-arm control, VLA policy deployment and edge NPU inference on the other.

<details>
<summary><b>中文简介</b></summary>
<br>
中山大学电子与信息工程学院（SEIT）学生。关注嵌入式与机器人：一端是 MCU 驱动、RTOS 与信号处理，另一端是机械臂控制、VLA 策略部署与端侧 NPU 推理。
</details>

## Selected projects

<table>
<tr>
<td width="40%" valign="middle">
<a href="https://github.com/skyswordx/STM32-accelerator"><img src="https://raw.githubusercontent.com/skyswordx/STM32-accelerator/HEAD/assets-of-README/wave-reconstruction.gif" alt="Waveform reconstruction demo" width="100%" /></a>
</td>
<td width="60%" valign="top">
<a href="https://github.com/skyswordx/STM32-accelerator"><b>STM32-accelerator · black-box circuit learner</b></a>
<br><sub>2025 NUEDC, signal track, problem G</sub>
<br><br>
STM32H750 system that sweeps an unknown circuit with an AD9954, samples input and output on synchronized dual ADCs, identifies its frequency response via FFT and reconstructs time-domain waveforms in real time.
<br><br>
<img src="https://img.shields.io/github/stars/skyswordx/STM32-accelerator?style=flat-square&color=F1C40F" alt="Stars" />
<img src="https://img.shields.io/badge/STM32H750-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white" alt="STM32H750" />
<img src="https://img.shields.io/badge/FreeRTOS-5C8A3A?style=flat-square" alt="FreeRTOS" />
<img src="https://img.shields.io/badge/CMSIS--DSP-6C63FF?style=flat-square" alt="CMSIS-DSP" />
</td>
</tr>
</table>

<table>
<tr>
<td width="60%" valign="top">
<a href="https://github.com/skyswordx/ESP32-S3-ELECTRONIC-LOAD"><b>ELEVOURER · ESP32-S3 electronic load</b></a>
<br><sub>SYSU SEIT engineering practice course</sub>
<br><br>
Portable smart electronic load with CC / CP / CR modes, real-time power monitoring and a touchscreen GUI.
<br><br>
<img src="https://img.shields.io/github/stars/skyswordx/ESP32-S3-ELECTRONIC-LOAD?style=flat-square&color=F1C40F" alt="Stars" />
<img src="https://img.shields.io/badge/ESP32--S3-E7352C?style=flat-square&logo=espressif&logoColor=white" alt="ESP32-S3" />
<img src="https://img.shields.io/badge/FreeRTOS-5C8A3A?style=flat-square" alt="FreeRTOS" />
<img src="https://img.shields.io/badge/LVGL-343839?style=flat-square" alt="LVGL" />
</td>
<td width="40%" valign="middle">
<a href="https://github.com/skyswordx/ESP32-S3-ELECTRONIC-LOAD"><img src="https://raw.githubusercontent.com/skyswordx/ESP32-S3-ELECTRONIC-LOAD/main/assets-of-README/image-demo.png" alt="ELEVOURER portable electronic load" width="100%" /></a>
</td>
</tr>
</table>

<table>
<tr>
<td width="40%" valign="middle">
<a href="https://github.com/skyswordx/KyLink"><img src="https://raw.githubusercontent.com/skyswordx/KyLink/HEAD/assets-of-README/image-demo.png" alt="KyLink NPU inference demo" width="100%" /></a>
</td>
<td width="60%" valign="top">
<a href="https://github.com/skyswordx/KyLink"><b>KyLink · edge messaging &amp; video on RK3566</b></a>
<br><sub>Embedded Linux · on-device AI</sub>
<br><br>
LAN messaging (FeiQ protocol), GStreamer video streaming and RKNN NPU detection on RK3566 + Ubuntu Kylin, plus a board-level LED driver.
<br><br>
<img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++" />
<img src="https://img.shields.io/badge/Qt5-41CD52?style=flat-square&logo=qt&logoColor=white" alt="Qt5" />
<img src="https://img.shields.io/badge/RKNN-RK3566-3B6EA5?style=flat-square" alt="RKNN" />
<img src="https://img.shields.io/badge/GStreamer-00A98F?style=flat-square" alt="GStreamer" />
</td>
</tr>
</table>

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/skyswordx/armctrl"><b>armctrl</b></a>
<br><sub>Robot arm · control &amp; SysID</sub>
<br><br>
Control and system-identification shell for the ARX5 arm: safety gates around planned motion, bounded agent action recipes and SysID orchestration.
<br><br>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/Pinocchio-555555?style=flat-square" alt="Pinocchio" />
<img src="https://img.shields.io/badge/LeRobot-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="LeRobot" />
</td>
<td width="50%" valign="top">
<a href="https://github.com/skyswordx/embegent"><b>embegent</b></a>
<br><sub>Agent harness · MCU debugging</sub>
<br><br>
Agent-friendly harness for on-target STM32 debugging: structured state, evidence and context layers so a coding agent can run long debug sessions reliably.
<br><br>
<img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black" alt="C" />
<img src="https://img.shields.io/badge/OpenOCD-2F81F7?style=flat-square" alt="OpenOCD" />
<img src="https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white" alt="STM32" />
</td>
</tr>
</table>

<details>
<summary><b>More projects</b></summary>
<br>
<table>
<tr>
<td width="30%"><a href="https://github.com/skyswordx/armodel"><b>armodel</b></a><br><sub>Python · VLA · NPU</sub></td>
<td>Model-side workspace for the arm stack: smoVLA post-training, export and NPU inference runtime</td>
</tr>
<tr>
<td><a href="https://github.com/skyswordx/Linky"><b>Linky</b></a><br><sub>C · Linux</sub></td>
<td>Lab for low-latency buffer ownership: buffer pools, memfd and DMA-BUF with descriptor rings, measuring tail latency</td>
</tr>
<tr>
<td><a href="https://github.com/skyswordx/final-tracker"><b>final-tracker</b></a><br><sub>C++ · ROS1 · MuJoCo</sub></td>
<td>Target-tracking UAV workspace: MuJoCo quadrotor bridge, UAM controller, perception, mapping and planning</td>
</tr>
<tr>
<td><a href="https://github.com/skyswordx/Gesture-DetectionRecognition"><b>Gesture-DetectionRecognition</b></a><br><sub>Python</sub></td>
<td>Camera-based gesture detection and recognition</td>
</tr>
<tr>
<td><a href="https://github.com/skyswordx/PID-Lambda-param-tuning"><b>PID-Lambda-param-tuning</b></a><br><sub>MATLAB</sub></td>
<td>PID tuning with the Lambda method</td>
</tr>
</table>
</details>

<details>
<summary><b>Learning notes</b></summary>
<br>
<a href="https://github.com/skyswordx/MYMCU">MYMCU</a> ·
<a href="https://github.com/skyswordx/MYFOC">MYFOC</a> ·
<a href="https://github.com/skyswordx/MYPCB-LAYOUT">MYPCB-LAYOUT</a> ·
<a href="https://github.com/skyswordx/PID-learning-record">PID-learning-record</a> ·
<a href="https://github.com/skyswordx/MY-DATA-STRUCTURE">MY-DATA-STRUCTURE</a> ·
<a href="https://github.com/skyswordx/rl-notes">rl-notes</a>
</details>

<!--
## Upstream contributions

| Project | Contribution | Status |
| --- | --- | --- |
| <img src="https://github.com/OWNER.png?size=40" width="20" align="center" /> [OWNER/REPO](https://github.com/OWNER/REPO) | [PR title](https://github.com/OWNER/REPO/pull/NUMBER) | ![Merged](https://img.shields.io/badge/merged-8957E5?style=flat-square) |
-->

## Toolbox

<table>
<tr>
<td width="22%"><b>Languages</b></td>
<td><img src="https://skillicons.dev/icons?i=c,cpp,python,matlab,ts" alt="C, C++, Python, MATLAB, TypeScript" /></td>
</tr>
<tr>
<td><b>Embedded</b></td>
<td><img src="https://skillicons.dev/icons?i=arduino,raspberrypi,linux,cmake" alt="Arduino, Raspberry Pi, Linux, CMake" /><br><code>STM32</code> <code>ESP-IDF</code> <code>FreeRTOS</code> <code>LVGL</code> <code>CMSIS-DSP</code> <code>FOC</code> <code>Modbus</code></td>
</tr>
<tr>
<td><b>Robotics &amp; AI</b></td>
<td><img src="https://skillicons.dev/icons?i=ros,pytorch" alt="ROS, PyTorch" /><br><code>MuJoCo</code> <code>LeRobot</code> <code>Pinocchio</code> <code>RKNN</code> <code>ONNX</code></td>
</tr>
<tr>
<td><b>Tools</b></td>
<td><img src="https://skillicons.dev/icons?i=git,githubactions,docker,vscode,latex" alt="Git, GitHub Actions, Docker, VS Code, LaTeX" /></td>
</tr>
</table>

## Activity

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=skyswordx&theme=transparent" alt="Contribution history" width="100%" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=skyswordx&theme=transparent&hide_border=true&ring=3B915D&fire=F78166&currStreakLabel=3B915D" alt="Contribution streak" />
</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/skyswordx/skyswordx/output/github-snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/skyswordx/skyswordx/output/github-snake.svg" alt="Contribution snake" width="100%" />
</picture>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/footer-dark.svg" />
    <img src="assets/footer-light.svg" alt="" width="100%" />
  </picture>
</p>
