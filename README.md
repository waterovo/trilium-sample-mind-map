## trilium-simple-mind-map
### 预览
![image](https://github.com/waterovo/trilium-sample-mind-map/assets/61768530/4fa93e38-c9dc-4dd4-993d-9130de09db46)
Powered by [simple-mind-map](https://github.com/wanglin2/mind-map)（Trilium 0.63.5）

如果您觉得这个插件过大，可以选择[trilium-jsmind](https://github.com/waterovo/trilium-jsmind)
### 结构
1. TriliumSmmWidget：将插件渲染到note-detail-pane
2. SmmRender：用于smm功能的调用和页面渲染，与TriliumSmmWidget一起可以改造出其他类型的笔记插件
3. QuickSearchWidget：从trilium源码中获取的插件，并进行一定改造，可以在其他场景下复用，快速搜索笔记并获取选中笔记的链接地址和名称
4. CopyImageReferenceButton：从trilium源码中获取的插件，并进行一定改造，可以在其他场景下复用，可以根据searchString复制图像引用到剪切板
### 安装
1. 导入笔记，取消勾选安全导入选项（如果您不熟悉trilium的小部件，请谨慎操作）
2. 开始使用
### 更新
1. 导入笔记
2. 如果需要保留之前的模板关系，可以保留旧版本的【模板】中的【simple-mind-map】笔记，然后复制新导入的【simple-mind-map】笔记的属性（关系和标签）和内容替换旧版本
3. 旧版本中【simple-mind-map】笔记包含的模板数据可按需保留或修改，其余笔记或数据删除不影响插件，如果确认已经不再需要旧版本，可以进行删除
