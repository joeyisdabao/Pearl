📖 Pearl4CVF 使用教程：以 CVPR 2025 为例

本教程将引导你如何使用 Pearl4CVF插件，在 1 分钟内从 CVF 官网筛选并批量下载你感兴趣的论文。

⚠️ 第 0 步：浏览器设置（非常重要！）

在开始之前，请务必关闭浏览器的“下载前询问”功能，否则每下载一篇论文，浏览器都会弹出一个保存对话框，无法实现全自动批量下载。

---
🚀 详细操作步骤
第一步：进入论文列表页
1. 访问 CVF 官方 Open Access 页面：https://openaccess.thecvf.com/menu
   
2. 在 "Main Conference" 列表中，找到并点击 CVPR 2025（或你关注的其他年份）。
   
3. 关键点：进入会议页面后，请点击顶部的 "All papers" 链接。
   
 💡 提示：Pearl 需要在包含所有论文标题的列表页运行，确保页面上列出了成百上千篇论文。
 
第二步：唤起插件

4.等待页面加载完毕后，点击浏览器右上角插件栏的  Pearl 图标，打开操作面板。

<img width="1003" height="646" alt="image" src="https://github.com/user-attachments/assets/e146a1c0-a08e-427a-8824-95dea9983262" />

第三步：配置筛选规则
在插件面板中，根据你的需求输入筛选条件：

5. 输入关键词
   
在输入框中填入感兴趣的词（支持模糊匹配，不区分大小写），多个关键词用逗号分隔（注意是逗号）。

<img width="996" height="805" alt="image" src="https://github.com/user-attachments/assets/9a4aa8d9-5cba-41a9-8197-4c59565abeff" />
<img width="1006" height="798" alt="image" src="https://github.com/user-attachments/assets/a6aed0bc-e519-4212-ad00-3939c145debf" />

6. 选择逻辑模式（核心功能）
- 🔴 OR 模式 (包含任意一个)
  - 含义：只要论文标题中包含你输入的任意一个关键词，就会被选中。
  - 场景：适合广度搜索。例如输入 nerf, gaussian，则标题里有 NeRF 或者 有 Gaussian 的都会被下载。
- 🔵 AND 模式 (同时包含所有)
  - 含义：论文标题必须同时包含你输入的所有关键词，才会被选中。
  - 场景：适合精准定位细分领域。例如输入 3d, diffusion，只有既包含 3D 又 包含 Diffusion 的论文才会被下载。
    
7. 设置保存文件夹（可选）
   
在“文件夹名”输入框中输入名称（例如 CVPR25_Diffusion），下载的文件将自动归类到该子文件夹中。

第四步：开始筛选与下载
1. 点击 "🔍 开始筛选" 按钮。
  - 插件会迅速遍历页面，你可以看到底部的统计数据（如：共扫描 2350，已命中 45）。
2. 确认筛选结果无误后，点击 "📥 下载选中文章"。
3. 大功告成！ 所有 PDF 将自动重命名为“论文标题.pdf”并保存到你的默认下载地址/CVPR25_Diffusion文件夹下（如果“文件夹名”输入框中输入名称（CVPR25_Diffusion））。

---
常见问题 (Q&A)
- Q: 为什么点击下载后，浏览器疯狂弹窗？
  - A: 请参考“第 0 步”，你忘记关闭浏览器的“下载前询问”选项了。
- Q: 搜索 clip 能搜到 clipping 吗？
  - A: 可以！Pearl 支持智能模糊匹配，输入词根即可匹配所有变体。
- Q: 支持 ICCV 或 ECCV 吗？
  - A: 支持。只要是 openaccess.thecvf.com 下的会议页面均可使用。
  - --
🚀 如何拥有它？
  由于还在持续更新中，代码后续将开源在 GitHub，完全免费，并还将会有支持其他数据库的Pearl系列助手。
  
  第1步：在本项目内，下载Pearl4CVF.ZIP到本地，并解压，需要记得下载地址。
  
  第2步：安装如果你是 Chrome 用户：在网页内打开 chrome://extensions/，开启开发者模式，选择加载未打包的扩展程序，选择解压好的项目文件。
  
  <img width="1323" height="1315" alt="image" src="https://github.com/user-attachments/assets/2c63b406-0332-4683-85c3-3356105f418f" />
<img width="2026" height="1191" alt="image" src="https://github.com/user-attachments/assets/1fac60c9-5685-4280-9122-769482dca6a6" />
  如果你是 Edge 用户：在网页内打开 edge://extensions/，找到开发者模式，其他操作与上述相似。
  
  第3步：直接使用！

  打开 CVPR 2025 页面，选择扩展插件，按照开头示范的那样，开始你的“丰收”之旅吧！
<img width="2026" height="1191" alt="image" src="https://github.com/user-attachments/assets/a772a86c-dd44-4aa7-b8e2-861388487106" />
<img width="2037" height="1147" alt="image" src="https://github.com/user-attachments/assets/9b5b7b1a-fcfb-4efb-9cad-510d959e9881" />

