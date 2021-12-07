# Wemory 使用说明



![wemory_logo-removebg-preview](README.assets/wemory_logo-removebg-preview-7487710.png)

[wemory.co](wemory.co)

联系我们：

zhous.vip+wemory@gmail.com



核心功能：

* 备份你的微信聊天记录（文字，图片，视频，音频，文件）
* 在手机和 PC 的浏览器上查看聊天记录
* 一键查看所有聊天记录中的图片，视频和文件，并支持下载
* 一键导出聊天记录为 PDF 



Wemory 帮助你把聊天记录储存在云端，让你随时随地可以查看，从而减少手机的内存占用，给你掌控感。这样，你可以备份你一辈子的记录。我们后面即将开发的一系列功能将让你充分利用你的聊天记录，比如激动人心的「生日自动识别和管理」功能。 

Wemory 目前只支持iPhone 和 iPad。安卓手机用户可以把记录迁移到 iPad 或者iPhone 来使用我们这个功能。后期Wemory 也会支持安卓端纯手机端完成备份。

第一次使用 Wemory 会很折磨你。请你做好心理准备。我的128GB用完了的 iPhone 11 备份用了1小时 14 分钟，备份文件 有72GB，最后生成聊天记录用了 35分钟，然后大小是 30GB。上传时间则取决于你的网速。所以，请你准备三个小时来开始使用 Wemory。

在开始之前，你可能会想要看看 Wemory 保存的聊天记录的效果，请点击：静态展示页

也许你也有个人隐私保护方面的顾虑，请查看我们在保护隐私方面做的努力，点击：[隐私保护页](/privacy.md)

如果你需要技术协助，我们的工程师能够在深圳南山，福田为你提供免费人工服务，你可以带上你的手机及电脑（建议）寻找我们（请致电：17150307075）。



我们的[定价](/pricing.md)。

 

## 开始前你需要准备的东西

1. iPhone 或者 iPad

2.  有足够内存的电脑（Mac或者 Windows 系统皆可），比如你的手机已经使用了 80GB的储存，那么为了使用 Wemory ，你的电脑也应该至少有 80GB 的内存

3. 3 个小时的时间

4.  使用 Wemory需要的软件

   * Wechat Exporter (GitHub开源软件，5MB，credit@BlueMatthew) [Mac OS](https://github.com/BlueMatthew/WechatExporter/releases/download/v1.9.0.2/v1.9.0.2_x64_macos.zip),[Windows](https://github.com/BlueMatthew/WechatExporter/releases/download/v1.9.0.2/v1.9.0.2_x64_win.zip)
   
   * iTunes（Windows 用户需要下载）

   - * [下载 Windows 10（64 位）版 iTunes](https://secure-appldnld.apple.com/itunes12/001-97787-20210421-F0E5A3C2-A2C9-11EB-A40B-A128318AD179/iTunes64Setup.exe)
   - * [下载 Windows 10（32位）版 iTunes](https://secure-appldnld.apple.com/itunes12/001-97791-20210421-F0E1AA9C-A2C9-11EB-8059-A028318AD179/iTunesSetup.exe)
   - * [下载 Windows 8（64位）版 iTunes](https://secure-appldnld.apple.com/itunes12/001-80053-20210422-E8A3B28C-A3B2-11EB-BE07-CE1B67FC6302/iTunes64Setup.exe)
   - * [下载 Windows 8（32位）版 iTunes](https://secure-appldnld.apple.com/itunes12/001-80042-20210422-E8A351F2-A3B2-11EB-9A8F-CF1B67FC6302/iTunesSetup.exe)
   
   * 压缩软件（推荐免费的 [Bandizip](https://cn.bandisoft.com/bandizip/) 或者 [7Z](https://sparanoid.com/lab/7z/)，实际上，任何大众压缩软件皆可）

 

## 都准备好了吗？我们开始吧。

 

### 第一步：创建一个手机全备份

备份你的iPhone到电脑上。 这一步我就不重复造轮子了，引用苹果官网的备份教程：

 

**使用 Mac 备份 iPhone**

1. 使用线缆连接 iPhone 和电脑。

2. 在 Mac 上的“访达”边栏中，选择您的 iPhone。

若要使用“访达”备份 iPhone，您需要使用 macOS 10.15 或更高版本。如果运行的是 macOS 的较早版本，请[使用 iTunes](https://support.apple.com/zh-cn/guide/itunes/back-up-your-ios-device-itns3280/12.9/mac/10.14) 来备份 iPhone。

3. 在“访达”窗口顶部，点按“通用”。

4. 选择“将 iPhone 上所有的数据备份到此 Mac”。

5. 请不要加密备份。

6. 点按“立即备份”。

 

**使用 Windows PC 备份 iPhone**

1. 使用线缆连接 iPhone 和电脑。

2. 在 PC 上的 iTunes App 中，单击 iTunes 窗口左上方附近的 iPhone 按钮。

3. 单击“摘要”。

4. 单击“立即备份”（“备份”下方）。

5. 请不要加密备份。



### 第二步：用 WeChat Exporter 将所有聊天记录导出

 

下载的软件解压之后，打开对应的 .exe 或者 .app 文件，可以看到如下画面（截图全部来自该 GitHub depository）：

Windows：

![img](README.assets/68747470733a2f2f7372632e77616b696e2e6f72672f6769746875622f77786578702f73637265656e73686f74732f77696e2e706e67.png)

 

macOS：

![img](README.assets/68747470733a2f2f7372632e77616b696e2e6f72672f6769746875622f77786578702f73637265656e73686f74732f6d61632e706e67232323.png) 



Wechat Exporter （以下简称 WE）能够自动识别iPhone 备份。如果你的电脑里面有旧的备份，请确保你选择的是最新的备份。

软件界面的右下角有一个导出按钮，默认导出的是所有的微信账号的所有聊天记录，你也可以只选择一个微信账号的聊天记录来导出。

导出后，找到对应的导出路径（即导出的记录的保存文件夹），你会看到一个index.html文件，和你的微信昵称命名的文件夹。（如果你的手机里面有多个微信，那么会有多个这样的文件夹。）

 

![image-20211121174504679](README.assets/image-20211121174504679.png)



将导出后的HTML 文件和文件夹打包成一个压缩包（ .zip格式）备用。

下一步就是将这个压缩包上传到 wemory 服务器。

 

### **第三步：上传聊天记录到 wemory，等待奇迹发生**

上传到 wemory 服务器这一步稍微有点复杂。因为我们的服务器带宽比较慢，且接收文件的功能并不完善，所以如果你直接上传几个 G 的文件过来，很可能会失败。因此，我们决定使用更好的工具来实现这个功能：百度云。

具体是这样的：

1. 你上传打包好的文件到百度云

2. 获得文件分享的链接和提取码
3. 在注册 wemory 时，填写你的链接和提取码
4. wemory 后台服务器从百度云下载你的文件



百度云获得分享链接和提取码的方式如图：

![image-20211207163733808](README.assets/image-20211207163733808.png)



如果你不希望通过百度云上传，那么你也可以在 wemory.co 注册你的账号。进入账户之后，将打包好的压缩包拖到网页的上传处。如果你使用这个方式，那么可能会出现多次上传失败，以及上传速度慢的问题。



注册完成后（或者上传完成后），请静待大约 12 个小时，你就可以在网页上看到你的聊天记录啦！（我们的服务器速度比较慢，见谅！）

 

**附注**

你可能会经历很多困难，尤其是当你的手机里面的东西很多（上百个 G的时候）。不要气馁，多试几次！想想如果手机丢了，里面的记录都没有了，会多么遗憾啊！不要等到失去后才去珍惜！

多次尝试后，如果还是不行，欢迎你致电我们，17150307075，我们乐意为你解答问题，也可以线下约在咖啡店为你解决！



**Q&A** 

Wemory 怎么保护我的隐私？

请查看我们专门的隐私页：

我们主要做了如下步骤：

1. 设立专门的 CPO（Chief Privacy Officer），首席隐私官，来负责监督数据安全。
2. Wemory 的域名和服务器均从阿里云注册，已经实名登记，如果有数据泄露问题，相关部门可以第一时间找到责任主体。
3. 所有的公司技术员工都使用该产品，和所有用户一起承担风险。
4. 后面我们会联合相关部门、保险或银行，为用户提供购买数据安全保险的选择，一旦出现数据安全问题，用户可以申请理赔。



Wemory 的幕后黑手是谁？

周北辰 CEO

曾留学英国和瑞士。热爱哲学，喜欢创业的掌控感，不喜欢公司上班。创业想法方面受 YC 影响很大，希望做出一款人们需要的产品。



和 Wemory 团队在一起工作是什么样的感觉？

没什么感觉，一起干大事就完了。



如何加入 Wemory 团队？

想办法联系我们就行。

