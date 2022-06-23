# BJTU-thesis-templete
BJTU学硕博士双页模板

主要是将学校官方的单页模板优点与之前大佬发的双页模板相结合，并且修改了亿点细节。

1. 个人比较强迫症，封面及致谢部分调整：
封面数字为宋体，并且间距调不到完全与word模板一致，因此直接用word编辑生成pdf后插入文中。
2. 封面博/硕修改demo.tex文件中：
\documentclass[Doctor]{BJTU-thesis} % 博士

\documentclass[AcMaster]{BJTU-thesis} % 硕士
3. 编译链接：xelatex——bibtex——xelatex——xelatex
4. 页边距、页脚距离等又调整了一下，现在已经基本上和word模板一致。
5. 页眉字号改为五号、页脚改为小五号，调整页眉字间距。
6. 目录字体调整。
7. 图表标题改1.1为1-1 8. 参考文献行距调为16pt。

官方模板地址：https://gs.bjtu.edu.cn/cms/item/195.html

大佬模板地址：https://github.com/xfdywy/bjtu-thesis-templete
