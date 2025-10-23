# 宝藏科研工具 | Zotero × 科大云盘：轻松读论文，高效管文献
---

## 1. 科研中的常见痛点

做科研时，你是否也遇到过这些问题？

- 📂 论文越下越多，文件夹越来越乱？  
- 🔍 找论文要“翻箱倒柜”半天？  
- 💻 换电脑后引用与同步全要重来？  
- 💸 好用的论文管理工具要么收费，要么空间太小？  

---

## 2. 解决方案：Zotero × 科大云盘

!!! tip "优雅又给力的组合"
    我们为你找到一个“优雅”又“给力”的解决方案：  
    **Zotero + 科大云盘** —— 轻松搞定论文管理、笔记同步与多端阅读，让科研更高效！

### 📘 Zotero 是什么？

Zotero 是一款开源的文献管理工具，可以帮助你：

- 收集、整理、引用与分享论文  
- 自带 PDF 阅读与批注功能  
- 支持插件扩展与多端同步  
- 官方提供 **300 MB 免费空间**

<img width="1080" height="504" alt="image" src="https://github.com/user-attachments/assets/6e9d03e5-fe1d-4311-9063-7788616e4920" />

### ☁️ 科大云盘的加持

科大云盘是中国科学技术大学提供的校园云存储服务：

- 在校师生拥有 **1 TB 超大空间**  
- 支持网页、Windows、macOS、Linux 客户端  
- 可通过 **WebDAV 协议连接 Zotero** 实现同步  

!!! success "无缝科研体验"
    现在，Zotero + 科大云盘 的强强联合  
    让科大人真正实现 **“无缝同步”** 的论文阅读与管理！

<img width="1080" height="527" alt="image" src="https://github.com/user-attachments/assets/6a235be5-249d-484c-b9a5-5539cfd2e1ce" />

---

## 3. Zotero 使用入门

!!! note "环境说明"
    以下以 **Windows 平台** 为例，其他系统操作类似。

### 🪄 步骤 1：下载安装

前往官网 [Zotero.org](https://www.zotero.org)  
下载 **Zotero 客户端** 与 **Zotero Connector** 浏览器插件。

> **Zotero Connector** 可一键导入网页论文。
<img width="944" height="849" alt="image" src="https://github.com/user-attachments/assets/193f2017-a53f-4379-a1d8-39453cddd635" />

---

### 🧭 步骤 2：注册与登录

打开客户端，进入  
`设置 → 同步`  
点击“创建用户”跳转官网注册账号。

登录后即可同步数据条目与笔记。
<img width="804" height="645" alt="image" src="https://github.com/user-attachments/assets/4ef9a6cf-c9b3-4211-bcc4-cef682f0e320" />
<img width="979" height="709" alt="image" src="https://github.com/user-attachments/assets/91c62f99-5ce1-4608-a8b1-1d5637692791" />

---

### 📥 步骤 3：导入论文

在浏览器中打开论文主页，  
点击浏览器右上角的 **Zotero Connector** 图标，即可将论文导入客户端。

<img width="1080" height="614" alt="image" src="https://github.com/user-attachments/assets/eab27333-9a03-4002-9a4f-638397054444" />

---

### 📖 步骤 4：查看与批注

在 Zotero 客户端中点击条目即可阅读 PDF，  
右侧会显示详细信息（如作者、会议、时间等）。

<img width="1080" height="610" alt="image" src="https://github.com/user-attachments/assets/dc14ae9b-825d-4627-b2ef-2cbdb82ba57d" />


---

## 4. 连接科大云盘 WebDAV

!!! question "空间不足怎么办？"
    Zotero 官方空间仅 300 MB？别慌！  
    **科大云盘 WebDAV** 来帮你彻底解决“空间焦虑”，科研再无后顾之忧！

---

### ⚙️ Step 1：登录科大云盘

访问 [科大云盘个人中心](https://pan.ustc.edu.cn)，使用统一身份认证登录。每位在校师生均享有 **1 TB 超大空间**。

---

### 📂 Step 2：新建资料库

在云盘中新建一个资料库，建议命名为zotero，此目录将用于同步你的论文与附件文件。

<img width="982" height="442" alt="image" src="https://github.com/user-attachments/assets/fe26194f-bcf7-4842-9b15-164a285b528a" />

---

### 🔐 Step 3：获取 WebDAV 账户

进入云盘 **设置 → WebDAV 账户**，  

<img width="632" height="630" alt="image" src="https://github.com/user-attachments/assets/77f0a30f-03a3-4e5f-8d45-a33164da842e" />

记录你的 **账户名与密码**。

<img width="853" height="360" alt="image" src="https://github.com/user-attachments/assets/d558e7e9-2f2e-40b8-a9ba-02b8ecefa557" />

---

### 🧩 Step 4：配置 Zotero 同步

在 Zotero 客户端中，打开：编辑 → 设置 → 同步 → 文件同步，选择 **WebDAV** 方式，并填写：

- **服务器地址**：`https://pan.ustc.edu.cn/dav/zotero`  
- **用户名 / 密码**：你的 WebDAV 账户信息  

点击“验证服务器”，提示成功即可。

<img width="810" height="643" alt="image" src="https://github.com/user-attachments/assets/31fd05cc-c46f-40cf-a943-f3dfaec1bb7e" />

---

## 5. 大功告成！

!!! success "连接完成"
    现在，你已经完成 **Zotero × 科大云盘** 的连接！  
    尽情享受真正“云端无界”的论文管理体验吧！

<img width="1080" height="618" alt="image" src="https://github.com/user-attachments/assets/8c457316-3630-4759-9fc0-2c0f4711b36b" />

---

### 🔁 从此你的科研生活更高效：

- 浏览器 **Zotero Connector**：保存网页上的论文与引用信息  
- 科大云盘 **WebDAV 同步**：自动保持文件一致  
- Zotero 桌面端 / 移动端：随时查阅与批注科研资料  

> 无论你在办公室、实验室还是家中，  
> 论文阅读、笔记记录与文献整理都能实时同步。  
>  
> 实现真正意义上的 ——  
> **“一份文献，全端可用”！**

---

## 6. 敬请期待：群组云盘 WebDAV

!!! info "功能开发中"
    群组云盘 WebDAV 正在开发中。  
    上线后将支持课题组与实验室共享文献、协作管理，  
    让团队科研协作更高效！

---

供稿：张烨，网络空间安全学院、网络信息中心在读博士生

> 🧭 *“让科研更高效，从 Zotero × 科大云盘 开始。”*






