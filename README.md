# 联想 昭阳 E40-80 OpenCore 黑苹果引导文件
### 硬件配置

| 项目 | 型号 |
| ------------ | ------------ |
| 配置 | 联想 昭阳 E40-80 |
| 处理器 | Intel Core i5-5300U |
| 内存 | 4GB+4GB DDR3 1600MHz |
| 显卡0 | Intel HD Graphics 5500 2048 MB |
| 有线网卡 | Realtek GBE Controller |
| 无线网卡 | Intel Dual-Band Wireless AC 3160 |
| 内置读卡器 | Realtek RTS5229 |
| 摄像头 | Lenovo EasyCamera |
| 使用的引导程序 | OpenCore 0.6.6 |

# 正常工作的硬件：
- 核显硬件加速
- ACPI盖子
- CPU & 风扇
- Wi-Fi
- USB 3.0/2.0接口
- 键盘
- 触摸板、手势
- 声卡
- 亮度控制
- 电池信息
- 内置摄像头
- 内置读卡器
- VGA 视频输出
- HiDPI
- 睡眠 / 唤醒

# 以下硬件工作不正常：

| 硬件 | 故障 |
| ------------ | ------------ |
| 蓝牙 | 能够开启但配对和连接有问题  |
| HDMI | 完全没驱动起来，插屏无信号 |
| 指纹 | 不支持  |
| 独立显卡 | 不支持 |

本机使用Macos 须在BIOS中做如下操作
1. 需要切换到UEFI ONLY
2. 开启VT-x，关闭VT-d
3. 关闭安全启动
4. 如果在macos下续航较差，请切换至仅核显模式
5. 序列号请在macos下自行修改（**重要**），否则无法使用Apple服务，甚至导致AppleID封禁

### 推荐安装 Monterey.12.6.3 
