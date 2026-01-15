# DeviceSpoofer-public
改机大师公开版，修改的信息如下图所示，暂时就公开这些功能，注意手机必须ROOT，解锁BL锁，刷入magisk，使用时选择要注入的软件，点击改机写入即可，恢复点击恢复初始ID按钮
## 📱 系统要求 

| 项目 | 要求 |
|------|------|
| **最低 Android 版本** | Android 7.0 (API 24) |
| **最高 Android 版本** | Android 14 (API 34) |
| **Root 框架** | Magisk 25.0+ (Zygisk 模式) |
| **模块框架** | LSPosed (Zygisk 版) |

### 推荐工具
- **Shamiko** - 隐藏 Root 状态
- **Hide My Applist** - 隐藏已安装模块

## 🎯 支持的伪装项目

### 设备标识符
| 字段 | 描述 | 格式 |
|------|------|------|
| IMEI | 国际移动设备识别码 | 15位数字 (Luhn校验) |
| Android ID | 安卓设备 ID | 16位十六进制 |
| 广告 ID (GAID) | Google 广告标识符 | UUID 格式 |
| OAID | 国内设备广告标识符 | 32位十六进制 |
| 序列号 | 设备序列号 | 10-12位字母数字 |
| 蓝牙 MAC | 蓝牙地址 | XX:XX:XX:XX:XX:XX |
| WiFi MAC | WiFi 地址 | XX:XX:XX:XX:XX:XX |
| WiFi SSID | WiFi 名称 | 自定义 |

### 设备指纹 (Build)
| 字段 | Hook 目标 |
|------|-----------|
| 型号 | `Build.MODEL` |
| 制造商 | `Build.MANUFACTURER` |
| 品牌 | `Build.BRAND` |
| 设备代号 | `Build.DEVICE`, `Build.PRODUCT` |
| 主板 | `Build.BOARD`, `Build.HARDWARE` |
| 基带版本 | `Build.getRadioVersion()` |
| 系统版本 | `Build.DISPLAY`, `Build.VERSION.INCREMENTAL` |
| Android 版本 | `Build.VERSION.RELEASE` |
| 指纹 | `Build.FINGERPRINT` |

<img width="300" height="600" alt="image" src="https://github.com/user-attachments/assets/919b95ea-d4c8-444d-abae-f2a92c84d478" />
<img width="300" height="600" alt="image" src="https://github.com/user-attachments/assets/9af4fd51-f568-4f65-bce3-072f51c0f067" />
<img width="300" height="600" alt="image" src="https://github.com/user-attachments/assets/12ecb46a-2e80-43de-b8e3-75a89acfaf55" />
<img width="300" height="600" alt="image" src="https://github.com/user-attachments/assets/ee6ef6ed-5b60-4277-b6b3-1b641bb29b1b" />
<img width="300" height="600" alt="image" src="https://github.com/user-attachments/assets/92ac0ac0-05f7-4932-8871-f30c5a4868d9" />
<img width="300" height="600" alt="image" src="https://github.com/user-attachments/assets/7f188c9c-9eb6-438c-bcd1-0eae07372f18" />
<img width="300" height="600" alt="image" src="https://github.com/user-attachments/assets/3e7340f6-057e-48b8-844b-1b92799b33fa" />
<img width="300" height="600" alt="image" src="https://github.com/user-attachments/assets/c22d2743-cfd4-4786-88cd-f634b66cb01c" />
