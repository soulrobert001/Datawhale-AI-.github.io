# Datawhale AI 冬令营学习笔记

## 学习主题：动手定制专属大模型

### 🏷️ Slogan：动手学，人人都能学的 AI  
本次学习通过 **讯飞星辰Maas平台** 和相关数据集，实践微调 GPT-3.5 等大模型的全过程，打造一个专属的 AI 模型。  
目标：探索大模型微调的技术和价值，并定制属于自己的个性化聊天助手——**AI 嬛嬛**。

---

## 学习步骤

### Step 1：注册讯飞星辰Maas平台  
- 访问 [官网链接](https://training.xfyun.cn/?ch=maas-dw-mxb)。
- 手机号快捷登录，熟悉平台界面和功能。

### Step 2：下载嬛嬛数据集  
- **数据集来源**：GitHub 开源项目  
  [嬛嬛数据集](https://github.com/datawhalechina/self-llm/blob/master/dataset/huanhuan.json)  
- 数据结构：采用 Alpaca 格式，包含 `instruction`（任务指令）、`input`（输入内容）和 `output`（期望输出）。

### Step 3：定制大模型  
- **流程**：
  1. 在讯飞星辰Maas平台点击 **创建模型**。
  2. 配置模型基础信息，注意选择正确的模型类型。
  3. 创建并导入嬛嬛数据集，上传后提交微调任务。
  4. 排队等待任务完成，数据集越大等待时间越长。
- **效果**：
  微调后，模型模仿《甄嬛传》中嬛嬛的语气和风格，适用于特定场景聊天。

### Step 4：创建应用  
- 在 [应用管理页面](https://console.xfyun.cn/app/myapp) 创建新的应用，用于部署微调完成的模型。  
- 填写基础信息，完成配置后发布服务。

### Step 5：体验 AI 嬛嬛  
- 点击 **体验** 按钮，选择微调好的模型开始使用。  
- 模型可模拟角色对话、展现人物性格特点，验证微调效果。

---

## 学习心得

### 🌟 收获
1. 掌握了从平台注册到模型微调的完整流程。
2. 了解 Alpaca 格式数据集的结构与特点。
3. 实现了个性化模型定制，提高对大模型能力的理解。

### 🔍 遇到的问题
1. **数据集格式校验失败**  
   - 原因：字段命名不符合要求。  
   - 解决：通过 JSON 格式校验工具检查语法。  
2. **模型微调任务长时间未完成**  
   - 原因：平台任务排队过多。  
   - 解决：选择数据量较小的数据集测试，或调整时间提交任务。

### 🚀 改进方向
- 探索更多高级功能，如优化参数配置、扩展模型的任务范围。
- 尝试其他领域的模型微调任务（如法律知识模型、内容创作助手）。

---

## 进阶作业
1. **内容创作模型**  
   - 数据集：自定义网文素材，打造高效创作助手。
   - 微调效果：支持节奏把握、创意输出。
2. **行业知识模型**  
   - 数据集：[法律领域数据集](https://github.com/AndrewZhe/lawyer-llama)。  
   - 微调效果：增强法律条文解析能力，为专业咨询服务。

---

## 相关资源
- **平台链接**：[讯飞星辰Maas官网](https://training.xfyun.cn/?ch=maas-dw-mxb)
- **项目代码**：[Chat-嬛嬛 GitHub仓](https://github.com/KMnO4-zx/huanhuan-chat)
- **学习交流群**：共享经验与反馈

感谢 Datawhale 提供学习机会！更多信息请访问 [Datawhale 活动页面](https://www.datawhale.cn/activity/110/21/76?rankingPage=1)。

![微信图片_20241208220131](C:\Users\Jason\OneDrive\Desktop\datawhale note\微信图片_20241208220131.png)

![微信图片_20241208230526](C:\Users\Jason\OneDrive\Desktop\datawhale note\微信图片_20241208230526.png)

![613a6d558fb7977d575450ed0f9f95f](D:\wechat data\WeChat Files\wxid_cnkadat9tz0322\FileStorage\Temp\613a6d558fb7977d575450ed0f9f95f.png)

![微信图片_20241209000139](C:\Users\Jason\OneDrive\Desktop\datawhale note\微信图片_20241209000139.png)

![微信图片_20241209000144](C:\Users\Jason\OneDrive\Desktop\datawhale note\微信图片_20241209000144.png)

![微信图片_20241209000601](C:\Users\Jason\OneDrive\Desktop\datawhale note\微信图片_20241209000601.png)

![微信图片_20241209000606](C:\Users\Jason\OneDrive\Desktop\datawhale note\微信图片_20241209000606.png)