ucasthesis stable release
==========

(模板下载请点击当前页面右边的：Download Zip)

LaTeX thesis template for The University of Chinese Academy of Sciences 中国科学院大学学位论文模板
 
本模板用于撰写中国科学院大学学位论文，面向对象为国科大学生（本、硕、博及留学生）。

开题报告模版请见[这里](https://github.com/mohuangrui/ucasproposal)。
 
### 使用方式
- 对于Windows用户，推荐使用较新版本的TexLive，不要用CTEX，因为CTEX已经很多年没有出过更新了。我自己用CTEX时编译错误，提示缺少包。直接下载最新版本的[TexLive](https://www.tug.org/texlive/)就行。不要在环境配置上花费过多时间，没有意义。
- 对于Mac用户，直接安装MacTex就可以。

两种方式亲测有效。

下载完成以后，运行compile.bat或者.sh文件进行编译。然后，Thesis.tex是主文件。用pdflatex或者xelatex编译都是可以的。
  
- - -
考虑到大多数用户并无 LaTeX 使用经验，本模板将 LaTeX 的复杂性尽可能地进行了封装，开放出简单的接口，以便于使用者可以轻易地使用。同时，对使用 LaTeX 撰写论文所遇到的一些主要难题，如插入图片、文献索引等，进行了详细的说明，并提供了相应的代码样本，理解了上述问题后，对于初学者而言，使用此模板撰写其学文论文将不存在实质性的困难。所以，如果您是初学者，请不要直接放弃，因为同样作为初学者的我，十分明白让 LaTeX 变得简单易用的重要性，而这正是本模板所体现的。

此中国科学院大学学位论文模板 ucasthesis 基于吴凌云的 CASthesis 模板发展而来，ucasthesis 文档类的基础架构为 ctexbook 文档类。当前 ucasthesis 模板满足最新的中国科学院大学学位论文撰写要求和封面设定。模板兼顾不同操作系统 (Windows, Linux, Mac OS) 并兼容 pdflatex 和 xelatex 编译方式，完美地支持中文书签、中文渲染、中文粗体显示、拷贝 pdf 中的文本到其他文本编辑器等特性，此外，对模板的文档结构进行了精心设计，撰写了编译脚本提高模板的易用性和使用效率。

宏包的目的是简化学位论文的撰写，模板文档的默认设定是十分规范的，从而论文作者可以将精力集中到论文的内容上，而不需要在版面设置上花费精力。 同时，在编写模板的 LaTeX 文档代码过程中，作者对各结构和命令进行了十分详细的注解，并提供了整洁一致的代码结构，对文档的仔细阅读可以为初学的您提供一个学习 LaTeX 的窗口。除此之外，整个模板的架构十分注重通用性，事实上，本模板不仅是中国科学院大学学文论文模板，同时，也是使用 LaTeX 撰写中英文 article 或 book 的通用模板，并为使用者的个性化设定提供了接口和相应的代码。

具体使用细节请见下载附件中的 UCASthesis Documentation "HowToUse.pdf"。

