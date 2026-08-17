<!-- 顶部动态打字机：模拟 adb shell 登录 -->
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=20&duration=2500&pause=800&color=00FFC8&background=0D1117&center=true&vCenter=true&width=600&lines=%24+adb+shell+%7C+su+%7C+whoami;root%40starlifezzz%3A~%23+cat+/proc/version;Linux+version+6.1.0-KernelSU+(starlifezzz%40GuiYang);%24+echo+'Welcome+to+the+machine'" alt="Terminal Typing" />
</p>

<!-- 主标题：不用 Hi，用系统启动日志 -->
<h1 align="center">
  <code>[BOOT]</code> starlifezzz's System Initialized
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/STATUS-ROOTED-success?style=flat-square&logo=android&logoColor=white" />
  <img src="https://img.shields.io/badge/LOCATION-GuiYang%2C%20CN-informational?style=flat-square&logo=mapbox&logoColor=white" />
  <img src="https://img.shields.io/badge/UPTIME-437%20commits%2Fyear-critical?style=flat-square&logo=git&logoColor=white" />
  <img src="https://komarev.com/ghpvc/?username=starlifezzz&label=PROFILE+VIEWS&color=00FFC8&style=flat-square" />
</p>

<!-- 分割线：模拟 dmesg 输出 -->
<p align="center">
  <code>[    0.000000] Initializing personality: 挖掘机 (Excavator Mode)</code><br>
  <code>[    0.000001] Loading modules: ColorOS16_Optimize | Nix_Config | Link_NN6000V2_Firmware</code><br>
  <code>[    0.000002] Mounting filesystems: /dev/sda1 → /mnt/github_profile</code>
</p>

---

## 🔧 Active Processes (Pinned Repos)

<table align="center">
<tr>
<td width="50%">

### 📱 `Logd_Disabler_ColorOS16`
> 干掉 ColorOS16 冗余日志守护进程，释放 RAM 与 I/O 性能  
> ![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white)
> ![Stars](https://img.shields.io/github/stars/starlifezzz/Logd_Disabler_ColorOS16?style=flat-square&color=00FFC8)

```bash
# 一键部署
magisk --install-module Logd_Disabler_v1.5.1.zip
setprop persist.sys.logd.disable 1
