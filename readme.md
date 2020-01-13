# 开始使用Github创作您的UCloud Doc


## 【新功能发布日志】

| 发布日期   | 发布内容                   | 使用说明                                              | 发布人 |
| ---------- | -------------------------- | ----------------------------------------------------- | ------ |
| 2019-12-03 | 左边栏支持添加产品icon     | [前往查看](https://leaishere.github.io/docs_new/icon) | 李安   |
| 2020-01-13 | 功能更新：支持自由发布     | [前往查看](#step4自由发布)                            | 李安   |
| 2020-01-13 | 功能更新：支持更多语言高亮 | [前往查看](https://leaishere.github.io/docs_new/icon) | 李安   |
| 2020-01-13 | 功能更新：支持tabs样式     | [前往查看](https://leaishere.github.io/docs_new/icon) | 李安   |

---



## 快速阅读

> - ### 写作新人？无从下手？
>
>   - [【推荐阅读】《助你5步创建技术文档》](https://plan.io/blog/technical-documentation/)
>
> - ### 主要内容
>
>   - [4步上手文档中心！](#step1注册账号申请仓库)
>
> - ### 常见问题
>
>   - [合理使用Tips样式](faq)
>   - [更多语法支持高亮](faq)
>   - [平台支持Tabs](faq)
>   - [左侧导航目录缺失？](faq)
>   - [如何自定义文章排序](faq)
>
> - ### 完全新手？我第一次用github/第一次写文档
>
>   - [PD如何管理仓库？](duty)
>   - [第一次用github写文档？](create)
>   - [有没有推荐的md编辑器？](typora_github)
>
> - ### 意见收集：若您对指南的内容有更好的意见和建议，欢迎告诉我们
>
>   - [点击此处提交反馈](https://github.com/leaishere/docs_new/issues/1)



---





## 《4步上手文档中心》

### Step1:注册账号、申请仓库

#### 	1-1.使用**ucloud邮箱**注册github账号

#### 	1-2.联系主仓库的管理者冯业浩新建仓库

#### 	1-3.查收邀请邮件，前往仓库

​	[详细内容>>](before_work)

### Step2:开始写文档

#### 	2-1 **UCloudDocs的官方github账号** [点击查看>>](https://github.com/UCloudDocs)

#### 	2-2 **产品文档仓库/API文档仓库** [仓库列表>>](https://github.com/UCloudDocs?tab=repositories)

#### 	2-3 **仓库内容**

![画板](images/画板.jpg)

#### 	1. _sidebar.md控制左边栏--------用于生成页面左侧导航

- 文件名是“\_sidebar.md”,下划线不能丢，	[查看范例>>](sidebar)

- **【新功能】在规定class内写入产品icon名称，可在左边栏渲染出图标**
在_sidebar.md内首行新增class用于添加产品icon（如下图）。只需在[图标库](https://console-font.pre.ucloudadmin.com/www/preview)找到所需产品icon，并去您所管辖的**产品文档和api文档的sidebar文件下**，在图中圈中区域填入icon名称即可生效（样式类似“icon_ulb”）。 [以ulb产品文档为例，详细说明>>](icon)

  ![屏幕快照 2019-12-03 上午11.22.04](images/class.png)

  > **【温馨提示】** 现存仓库内_sidebar.md已批量添加好class。由于icon命名规则与仓库不一致，无法批量添加。
  > 请各位PD**自行**前往[图标库](https://console-font.pre.ucloudadmin.com/www/preview)查找，并在**_sidebar.md**内进行添加。

#### 2.  overview.md控制概览页--------章节目录页   [查看范例>>](overview)

#### 3.  文档文件夹--------章节

> 文件名夹名称仅支持**英文字母、英文下划线、英文连字符**

#### 4.  Markdown文档（xxx.md）--------文档	

* **规范命名文件夹及文件**：文件夹及文件名仅支持**英文字母、英文下划线、英文连字符**；_同层级下文件（夹）之间不得重名；文件名不得缺少“.md”后缀

* **文章标题请用H1**：当前文档标题需用一级标题样式，且文案应与sidebar.md内该文档的目录标题一致

* **使用Markdown语法写文档**：文档正文写作需遵从github侧md要求，并及时前往[cms预览](cms.docs.ucloudadmin.com)

>  预览样式不争取？**掌握自检技能，小问题快速解！**
>
> ![屏幕快照 2019-11-15 上午11.54.55](images/屏幕快照 2019-11-15 上午11.54.55.png)

* **文档内添加文章跳链**

  * 地址写法1:【推荐】使用绝对链接，如下图所示，直接目标文档的线上URL

  * 地址写法2：相对地址，如下图所示的“链接写法”

    ![屏幕快照 2019-11-01 下午12.27.19](images/屏幕快照 2019-11-01 下午12.27.19.png)

* **对外分享或引用文档**

  * **整篇文档？**：请直接使用线上目标文档的URL

  * **段落章节？**：请点击目标段落所在文档中该段落标题，然后直接使用带段落锚点的URL（如下图）

    ![屏幕快照 2019-11-15 下午2.09.07](images/屏幕快照 2019-11-15 下午2.09.07-3798714.png)

> **【为啥不能使用#来指向段落了？】**由于新平台技术方案变更为“单页面应用”，“#”无法再作为段落锚点的引用符号。此外，新引用方式也避免了手写段落标题可能出现的错误。
>
> **【温馨提示】** 不用担心，控制台的引用链接我们已清查、修正过。下次写作，请使用我们的新方法哦。

#### 5. **给文档插入图片--------图库/仓库根目录下images文件夹**

* 绝对地址引用：[使用图床>>](http://docs.ucloudadmin.com/5b10f62667ded1519074449f/edit)

- 相对地址引用（规则不变）

![](images/images.png)



## Step3:实时预览文档前往 

我们支持实时预览。仓库内的变更都可以实时在[cms预览](cms.docs.ucloudadmin.com)上预览样式。



## Step4:自由发布

发布地址：[点击这里](https://cms.docs.ucloudadmin.com/ucpublishnew.html)![image-20200113184021386](../docs_new/images/image-20200113184021386.png)

## 常见问题：

### Q：为什么我没有发布权限？

### A：请确认以下几点：

- 是否对仓库具有**master权限**。没有？联系**平台PD**
- 是否**公开**注册邮箱？
- 账号的**Primary邮箱**是否是**UCloud注册邮箱**？
-  是否完成一次 **commit**

------

### 【参考资料】

[Md语法说明](https://www.jianshu.com/p/40ba812dd973)  

[范例_ULB文档](https://github.com/UCloudDocs/UCloud-document/tree/master/network/ulb)

[Github简明教程](https://github.com/UCloudDocs/UCloud-document/tree/master/network/ulb)



### 【 联系人】

文档中心产品经理：李安

github主仓库管理人、文档发布人：冯业浩

