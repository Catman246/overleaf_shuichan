AquaDiag 论文 LaTeX 项目（Overleaf 用）

编译方式：
- 编译器选择 XeLaTeX（ctex 中文 + fandol 字体需要）
- 主文件：main.tex

目录结构：
- main.tex            主文件
- preamble.tex        导言区（宏包）
- cvpr.sty            CVPR 模板样式
- ieeenat_fullname.bst 参考文献样式
- main.bib            参考文献
- sec/                章节（0摘要/1引言/2相关工作/3方法/4实验/5结论）
- figures/            框架图（figure_aquadiag.png）

注意：
- 标题/作者/学校/邮箱是占位，需替换；
- main.bib 里带 "and others" 的文献作者信息是简化占位，投稿前需补齐完整作者列表；
- 框架图目前是 PNG 预览（draw.io Desktop 未安装，矢量 SVG 在 dp/figures/，可用 draw.io 导成 PDF 替换）。
