# **🛠️Twitter 媒体下载 更新日志**

### **📅 2026.10.3.1（zaoe fork）**

- **修复**：单文件和多文件分别下载改为先获取媒体内容，再通过 Blob URL 保存，避免 IDM 接管后丢失自定义文件名。
- **保留**：普通版引用推文选择、原有命名规则、ZIP 打包及 Firefox 保存处理。
- **修复**：Markdown 历史导出的特殊字符变量缺失；批量失败后恢复任务计数，全部文件成功后才标记推文完成。
- **更新**：脚本命名为「Twitter 媒体下载 (兼容IDM)」，可保留原版查看上游更新；兼容版更新与下载地址指向 zaoe/UserScripts。
- **参考**：[IDM 兼容版](https://greasyfork.org/scripts/578809-twitter-x-media-downloader-idm-compatible)。

---

### **📅 2025.04.28.1719**

**新增**: 导出下载历史为 `MarkDown`,代码来自 GreasyFork 用户[SteveSun](https://greasyfork.org/users/1462808)发布于[#296680](https://greasyfork.org/scripts/495368/discussions/296680#comment-589869)<br>
**截图**: ![2025.04.28](https://s2.loli.net/2025/04/28/qZDoaHuUF7gK1XI.png)

---

### **📅 2025.04.28.1503**

**修复**: 2025.04.28,修复了`Api`在失效后后无法正常下载媒体的问题<br>
**修复**: 修复代码来自 GreasyFork 用户[goemon2017](https://greasyfork.org/users/1462596)发布的[#296626-589742](https://greasyfork.org/scripts/423001/discussions/296626#comment-589742)<br>

---

### **📅 2025.03.13.0544**

**新增**: • 启用自定义打包为`zip`功能,允许手动设置 [#292483](https://greasyfork.org/scripts/529453/discussions/292483)<br>
**截图**: ![zip.png](https://s2.loli.net/2025/03/13/ue7V5Hg31SBfv2I.png) <br>
**修复**: • 使原脚本的下载进度能被显示.

---

### **📅 2025.03.13.0246**

**新增**: • 支持对转发的推文视频和图片进行下载<br>
**测试地址**: [Elon Musk](https://x.com/elonmusk/status/1899865564773859555) <br>
**测试截图**: ![el.png](https://s2.loli.net/2025/03/13/L5gcNm7XvAGxsnw.png) <br>
**新增**: 对于含有链接的帖子中显示的预览截图不予下载,并添加提示 <br> ![link.png](https://s2.loli.net/2025/03/13/e4EsrYtjHXRzMTh.png) <br>
**新增**: 对于媒体文件提取为空时,直接报错.<br>

---

### **📅 2025.03.11.0811**

**新增**: • 批量下载时,打包为一个 zip 文件

---

### **📅 2025.12.01.01**

**新增**: • 当检测到推文包含引用推文且引用推文含有媒体时，弹出对话框让用户选择下载原始推文还是引用推文的媒体 [#235](https://github.com/ChinaGodMan/UserScripts/pull/235)  

---
