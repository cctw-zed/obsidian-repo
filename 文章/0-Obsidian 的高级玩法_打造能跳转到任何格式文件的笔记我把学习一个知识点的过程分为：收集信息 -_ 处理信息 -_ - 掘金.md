我把学习一个知识点的过程分为：收集信息 -> 处理信息 -> 应试，这篇文章也会以这个脉络为大纲来写 收集信息分为两步，即 “收” 和“集”。

“收”，即从多个平台获取文章（这里之所以明确是文章，是针对计算机学习。对于摄影或其他领域的学习就不只是文章了，还有图片之类形式的信息，这时候可能就不适用了，请读者自行斟酌使用），电脑端我是用[简悦](https://link.juejin.cn/?target=) (简悦可以把网页文章转成本地 Markdown)，而手机端我是用 [Cubox](https://link.juejin.cn/?target=)(Cubox 可以把手机上收藏的文章在电脑打开)。

“集”，即将信息聚合成自己的笔记，然鹅信息有很多种形式，比如 pdf、网页视频 / 音频、图片、网页文章等等。[Obsidian](https://link.juejin.cn/?target=https%3A%2F%2Fobsidian.md%2F "https://obsidian.md/") 恰好能很好地聚合这些形式，本文也着重讲解我是怎么玩转 Obsidian 的。

处理信息则是在收集信息后，怎么把这些知识变成自己的东西，也可以说是转化吧。

应试很好理解，即各种考试、面试。这一步看情况而定，像如果我学习这些东西只是为了提升自己，应对日常开发的话，是不需要应试的，因为我不记得了就随时可以翻这些笔记，但如果做笔记是为了考试和面试，那么应试这步却是不可或缺的一环，毕竟应试是为了背诵然后去经历考试的筛选，挺无奈的。。。

简单地说，Obsidian 是一款支持双链的本地 Markdown 笔记软件，拥有海量高效的插件增强，并且支持多平台。 详细的介绍就不说了，毕竟这篇不是入门级指南，入门级指南请看：

*   [闲者时间_王掌柜关于 Obsidian 的系列文章](https://link.juejin.cn/?target=https%3A%2F%2Fsspai.com%2Fu%2F5b3wva6y%2Fposts "https://sspai.com/u/5b3wva6y/posts")
*   [Obsidian 优质中文内容合集](https://link.juejin.cn/?target=https%3A%2F%2Fsspai.com%2Fpost%2F68427 "https://sspai.com/post/68427")

笔者以前也用过几款笔记软件，就不点名了，免得有拉踩的嫌疑。最终选择 Obsidian 的原因是因为它解决了我在信息收集处理过程中的以下痛点：

## 痛点

*   在笔记中引用了某本书的一些话，过一段时间想回原文考究时却很难找到出处
*   在根据某本书学习时，想要摘抄原文的一些话却只能自己跟着书手敲一遍到自己的笔记中
*   想对视频做笔记
*   在流程图中想对特定关键字跳转到某篇自己的笔记
*   想把笔记内容导入到 anki 去背诵
*   想把网页文章变成自己本地的一篇笔记
*   笔记之间能想维基百科那样跳转

那么 Obsidian 是怎么解决这些痛点的呢：

## 解决痛点

*   在笔记中快速引用 pdf 原文
    
    (对应痛点：在根据某本书学习时，想要摘抄原文的一些话却只能自己跟着书手敲一遍到自己的笔记中)
    
    ![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/c5f5353689244cadae927f218751c789~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)
    
*   能跳转到 pdf 原文
    
    (对应痛点：在笔记中引用了某本书的一些话，过一段时间想回原文考究时却很难找到出处)
    
    ![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/ae6119ecd824441297f4eaa10325099d~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)
    
*   能跳转到视频的某个时间点
    
    (对应痛点：想对视频做笔记)
    
    ![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/7a8d752548f245dbb496665a76413965~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp?)
    
*   在流程图中跳转到自己的笔记
    
    (对应痛点：在流程图中想对特定关键字跳转到某篇自己的笔记)
    
    ![](https://p6-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/9bef633b0eba457e871cf14457495b08~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp?)
    
*   把笔记内容导入到 anki 去背诵
    
    (对应痛点：想把笔记内容导入到 anki 去背诵）
    
    ![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/4b324f370a6342d09bc6c3bb2b7875d5~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)
    
*   剪藏网页文章到本地
    
    (对应痛点：想把网页文章变成自己本地的一篇笔记）
    
    ![](https://p9-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/141201ac8c5e4a5cba9feb577e5e36a9~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp?)
    
*   笔记之间能跳转
    
    (对应痛点：笔记之间能像维基百科那样跳转）
    
    ![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/fe4ccdbcb14e47d98836f873854eb1ea~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)
    

如果 Obsidian 解决的痛点满足你的需求，可以看 [Obsidian 的安装](https://link.juejin.cn/?target=)、[基础使用](https://link.juejin.cn/?target=)，本篇文章不介绍基础使用 目前我已经使用了此学习流稳定输出了 823 篇笔记，累计使用时间为 6 个月，通过以下笔记的 `关系图谱` 可以看到我写的所有笔记之间的联系，并且可以看出我对不同领域的积累量（看笔记的数量，一个点代表一篇笔记）

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/97ae6733598d4636991c3fa71a48cb5d~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

使用 Obsidian 做笔记时可以在学习过程中做到真正的有迹可循，也可以让知识点之间解耦，使知识点原子化，以强化知识点之间的联系。

## 连接电子书

### 展示

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/ae6119ecd824441297f4eaa10325099d~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

### 配置过程

#### 使用工具

*   [Annotator](https://link.juejin.cn/?target=https%3A%2F%2Fgithub.com%2Felias-sundqvist%2Fobsidian-annotator "https://github.com/elias-sundqvist/obsidian-annotator")
    *   是一个用于给 pdf 做标注和跳转的开源插件
*   [Linter](https://link.juejin.cn/?target=https%3A%2F%2Fgithub.com%2Fplaters%2Fobsidian-linter "https://github.com/platers/obsidian-linter")
    *   是一个用于格式化笔记的开源插件

#### 配置 Linter

目标：修改其源代码，添加将 Annotator 样式修改为 📌

添加规则分类：

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/6f7f3a9ced8947528bd8755d201a935e~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

添加具体的规则处理：

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/6a8b90f1fca14698b267b1fdbbe85f81~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

代码如下：

```
new Rule('Reform Annotation', '修改 Annotation 链接的样式', RuleType.MINE, (text, options = {}) => {  
    const searchRegex = new RegExp(`${options['Find']}`, "gm");  
    text = text.replace(searchRegex, `${options['Replace']}`);  
    return text;  
},[  
], [  
    new TextOption('Find', 'regular expression for finding', "\\[\\[([^@]+)@annote#([^|]+)\\|([^📌\\]]+)\\]\\]"),  
    new TextOption('Replace', 'result of replacement', '[[$1@annote#$2|📌]]$3')  
])


```

保存后退出 ide，并重启 Obsidian，打开 Linter 的设置，并开启新功能的开关

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/4cbca30cc5ce464092295d5f0ef0b271~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

测试一下： （测试前）

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/4b49ab1e0953430bb697017f0425732b~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

（测试后）

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/69b00f2d661347bdb38c31d5a25855a7~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

### 日常工作流

#### OCR 字体识别

如果目标 pdf 文件不能选中文本，那么先用 Acrobat 进行字体识别：

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/88c95574564847f5996e3eda87b05a3a~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

点击 **编辑**

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/de69f2878d0c425d8e3fe59818fad9a6~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

接着就会自动识别文档了

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/92a918001d6c48b881aeec92d0898e81~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

#### 标注 pdf

打开一个 pdf 文件，左键选中要标注的句子，然后会自动弹出 **Hightlight** 按钮并点击，就可以完成一个句子的标注

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/befb5ed0175c4dc8af07d521a25869dc~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

接着按如下操作即可完成链接到 pdf 中的标注

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/8270d4a70baf4b5cbb2c6130669f3f0b~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

## 连接网页

实际是网页剪藏和标注

### 展示

![](https://p6-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/c9be62ece0884c189fb9707084522777~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp?)

#### 实用工具

*   [简悦](https://link.juejin.cn/?target=http%3A%2F%2Fksria.com%2Fsimpread%2F "http://ksria.com/simpread/")（版本为 2.2）
    *   这是一个可以把网页文章保存为本地 markdown 格式笔记的工具
    *   解决问题：[github.com/Kenshin/sim…](https://link.juejin.cn/?target=https%3A%2F%2Fgithub.com%2FKenshin%2Fsimpread%2Fissues "https://github.com/Kenshin/simpread/issues")

### 配置

#### 安装简悦

1.  在 chrome 网上应用店安装简悦的浏览器插件
    
    ![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/8b283cbdfae5462fae313cd1002c9be0~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)
    
2.  安装成功后
    
    ![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/52ebaefcc57e40d480fe19a5c18d0a74~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)
    
3.  安装能在 简悦 内使用的脚本插件
    
    ![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/ce564b19c1da4cfe8458b4990cb4cb14~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)
    
    可以看到在 **插件中心** 有挺多脚本插件的
    
    ![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/3ad63cfafed143c691f785adb10c4971~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)
    
    然后在 **插件中心** 下载以下脚本插件
    
    ![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/eba25acb1ab844d2b73c4996f4badba0~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)
    
    因为很多技术文章的标题都带有特殊符号，这会导致导入 Obsidian 失败，所以还得安装以下插件解决该问题：
    
    ![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/524446f749864d6fbde30373836aea21~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)
    
4.  设置 “导入到 Obsidian”
    
    ![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/8df55959e9674157a1327f627a32e721~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)
    
    ![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/d39aa76975e848b1ba902cfb2309a6eb~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)
    
    ![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/13adc0ac3ff14d7c9648ce01371e77af~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)
    
5.  设置 “Markdown 模板辅助增强插件”
    
    ![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/33c93c3f8ccd42ad81011ad3a9c0b25f~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)
    
    ![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/5c2dbb64c11348aabf059edae0e65f8f~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)
    
6.  设置 “自动化辅助增强”
    
    ![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/143eaa9b62074762a7a71be9e3c3458f~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)
    
7.  设置快捷键 使按 **ob** 时只导出全文
    
    ![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/48aa3bb8eb914a3f8faa791b675cd86e~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)
    

#### 配置 Linter

修改 Linter 源代码，添加可以将图片外链转换成自己图床的链接 ps. 我使用的图床是 [github](https://link.juejin.cn/?target=https%3A%2F%2Fgithub.com%2F "https://github.com/")，并且使用 [PicGo](https://link.juejin.cn/?target=https%3A%2F%2Fpicgo.github.io%2FPicGo-Doc%2Fzh%2Fguide%2F%23%25E5%25BA%2594%25E7%2594%25A8%25E6%25A6%2582%25E8%25BF%25B0 "https://picgo.github.io/PicGo-Doc/zh/guide/#%E5%BA%94%E7%94%A8%E6%A6%82%E8%BF%B0") 快速上传图片到图床。

首先引入 http、https、fs 库

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/855612088f224cdebe0a7dc49a14635b~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

```
var fs = require('fs');  
var http = require('http');  
var https = require('https');


```

添加自定义的方法

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/b1ebda72f9db434984b44d1a70126d6f~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

ps. 我的前端能力很菜很菜，献丑了。大佬们可以自己写这部分的功能。这段代码的逻辑就是先在本地新建一个文件夹 `temp_pic_folder`，然后通过正则表达式匹配到图片链接，然后通过这些链接把图片一个一个下载到文件夹 `temp_pic_folder` 中（没错，就是那么弱智的方法，因为不想在这方面花太多时间，毕竟工作是后端），然后再把下载下来的图片一个一个上传到用户设置的图床中，并修改文章中这些图片链接为最终图床上的图片链接，最后再把文件夹 `temp_pic_folder` 及其内部的图片都从本地删了。 注意！我这段代码只能匹配末尾有图片文件后缀名的链接，如 `https://xxxx/xxx/.../xxx.jpg`，如果是 `https://xxxx/xxx/.../xxx` 就不能识别，别问我为什么不处理这种情况，懒且够用

```
 * 将外链图片链接转换为自己的图床链接  
 *  
 * @param text 文档的文本  
 * @param options 插件在 setting tab 的设置  
 */  
async changeOuterLink (text, options = {}, app) {  
    
    const tempFolder = "temp_pic_folder";  
    const anchorFile = "anchor_file";  
    const parentPath = app.vault.getAbstractFileByPath(app.workspace.getActiveFile().path).parent.path;  
    
    
    const anchorFileRelativeUrl = tempFolderRelativeUrl + "/" + anchorFile;  
    const basePath = app.vault.adapter.getBasePath();  
    const absolutePath = basePath + "\\" + tempFolderRelativePath;  
  
    
    const searchRegex = new RegExp(`${options['Image regex']}`, "gm");  
  
    
    
    let fileList = [];  
    
    let fileExtMap = {};  
    
    
    let tempFileSet = new Set();  
  
    let folderAbstractFile = app.vault.getAbstractFileByPath(tempFolderRelativeUrl);  
    if (folderAbstractFile) {  
        
        let downloadedPicList = app.fileManager.getNewFileParent(anchorFileRelativeUrl).children;  
        for (let i = 0; i < downloadedPicList.length; i++) {  
            tempFileSet.add(downloadedPicList[i].basename);  
        }  
    } else {  
        
        await app.vault.createFolder(tempFolderRelativePath);  
        folderAbstractFile = app.vault.getAbstractFileByPath(tempFolderRelativeUrl);  
        await app.vault.create(anchorFileRelativeUrl, "");  
    }  
  
    text = text.replace(searchRegex, (rs, $1, $2) => {  
        
        if ($1.indexOf(myPicBedUrl) === -1) {  
            
            let picName = $1.slice($1.lastIndexOf('/') + 1).toString();  
            if (!tempFileSet.has(picName)) {  
                let perPromise = new Promise((resolve, reject) => {  
                    let request;  
                    if ($1[4] === "s") {  
                        request = https.get($1 + $2, (res) => {  
                            if (res.statusCode !== 200) {  
                                console.log("download image error!");  
                                return;                            }  
                            let ext = res.headers['content-type'].split('/')[1];  
                            let dest = absolutePath + "\\" + picName + "." + ext;  
                            let file = fs.createWriteStream(dest);  
  
                            res.on('end', () => {  
                                console.log("图片下载完毕");  
                            });  
  
                            
                            file.on('finish', () => {  
                                file.close();  
                                fileList.push(dest);  
                                fileExtMap[picName] = ext;  
                                resolve();  
                            }).on('error', (err) => {  
                                fs.unlink(dest);  
                            });  
                            res.pipe(file);  
                        });  
                    } else {  
                        
                        
                    }  
                    request.on('error', reject);  
                    request.end();  
                });  
                promiseList.push(perPromise);  
            } else {  
                console.log("图片已存在");  
            }  
        } else {  
            console.log("自己的地址");  
        }  
        return rs;  
    });  
  
    return Promise.allSettled(promiseList)  
        .then((results) => {  
            console.log("文件列表 " + fileList);  
            if (fileList.length > 0) {  
                return new Promise((resolve, reject) => {  
                    const postOptions = {  
                        hostname: `${options['PicGoUrl']}`,  
                        port: `${options['PicGoPort']}`,  
                        path: `${options['PicGoPath']}`,  
                        method: 'POST',  
                        headers: {  
                            'Content-Type': 'application/json'  
                        }  
                    }  
  
                    const req = http.request(postOptions, async res => {  
                        if (res.statusCode === 200) {  
                            console.log("删除图片文件夹 " + folderAbstractFile.path);  
                            await app.vault.delete(folderAbstractFile, true);  
                            
                            text = text.replace(searchRegex, (rs, $1) => {  
                                console.log("替换链接名");  
                                
                                let picName = $1.slice($1.lastIndexOf('/') + 1);  
                                let ext = fileExtMap[picName];  
                                return "![](" + myPicBedUrl + picName + "." + ext;  
                            });  
                        } else {  
                            console.log("上传失败");  
                        }  
                        resolve(text);  
                    });  
  
                    req.on('error', error => {  
                        console.error(error);  
                        reject(error);  
                    });  
  
                    req.write(JSON.stringify({list: fileList}));  
                    req.end();  
                });  
            } else {  
                return new Promise((resolve, reject) => {  
                    resolve(text);  
                });  
            }  
        });  
}


```

该方法调用处也要做修改：

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/4d822bd05f394dfeb65e3c392080a7c4~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

因为 `changeOuterLink` 方法是异步的，所以调用该方法的地方要加上 `await`

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/de5910305c1840a1a670670f331c4527~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/02419669d0434d57ae965ac4b6fe65a9~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/80d1f67a6a274198933e2f8babd560b6~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

然后在 rules 上添加新的规则

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/abe9c12f1e754ed4a824adae057a8ee8~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

```
new Rule('Upload Image', 'Switch', RuleType.MINE, (text, options = {}, app, changeOuterLink) => {  
    return changeOuterLink(text, options, app);  
},[  
], [  
    new TextOption('PicGoUrl', '', "127.0.0.1"), 
    
    new TextOption('PicGoPort', '', "36677"),  
    new TextOption('PicGoPath', '', "/upload"),  
    new TextOption('Host', 'target host', "https://raw.githubusercontent.com"),  
    
    new TextOption('Repository', '', "/xxx/xx/"),  
    new TextOption('Image regex', '', '\\!\\[[^\\[\\]]*\\]\\(([a-zA-z]+://[^/]+/[^.?)]+)([^)?]*)')  
])


```

### 日常工作流

#### 导出全文

在网页内按 `ob`，会看到如下画面

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/a747b43bfc5e4c30b015c898af1e4749~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

可以看到已经添加成功了 👇

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/0c4343edc7bc403bbda38317b1d7fcf2~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

根据我个人制定的信息可信度标准（一般是根据文章末尾写的参考文献数量，如果是没写参考，除非是自己的一些经验总结，不然我都认为是抄袭，并且认为其参考价值极低，之所以会剪藏这篇低参考价值的文章仅仅是因为其他文章写得更烂），给文章添加可信等级标识

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/969acd18a9824fbe9b510ef5346f0ff1~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

#### 导出标注

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/39482461d91542868ab047231712c3ed~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

当做了第一个标注后，文章信息框会出现 👇

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/e8eb04cb1c574fdd80a551d01bd12946~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

修改文章信息框内的内容 👇

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/bf463608f1974f148ace1cb5e2da3446~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

其中，如果文章不是很可信，那么一定要设置对应的参考价值的标签：

![](https://p6-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/3e57c90cb4fb42b8ae8028e6332a946d~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp?)

#### 信息处理完后给文件做标记

每个网页的信息处理过程如下图的复选框，三个选项都完成后就要给该文件添加一个图标，标识该文件已经处理完成 在阅读文章的过程中，不是很重要的句子就用 `加粗`，特别重要的句子就用 `高亮`， 把文章阅读完成后写一个 `总结`，完成这三步才算真正看完一篇文章

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/b66e0b50ed55483d9c40ae2be15babf4~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

## 连接视频

### 展示

![](https://p1-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/ac1cc8768d3445abacb44a4747113c2d~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp?)

### 配置

#### 使用工具

*   [Media Extended](https://link.juejin.cn/?target=https%3A%2F%2Fgithub.com%2Faidenlx%2Fmedia-extended "https://github.com/aidenlx/media-extended")
    *   使用这个插件能够播放网络视频并能跳转进度条（我已测试能行的网站有 youtube，其他没试过）
*   [Media Extended BiliBili Plugin](https://link.juejin.cn/?target=https%3A%2F%2Fgithub.com%2Faidenlx%2Fmx-bili-plugin "https://github.com/aidenlx/mx-bili-plugin")
    *   这个插件是支持播放 bilibili 视频并能跳转进度条的插件
*   [Regex Find and Replace](https://link.juejin.cn/?target=https%3A%2F%2Fgithub.com%2FGru80%2Fobsidian-regex-replace "https://github.com/Gru80/obsidian-regex-replace")
    *   该插件可用于正则表达式查找和替换
*   [Language Reactor](https://link.juejin.cn/?target=https%3A%2F%2Fwww.languagereactor.com%2F "https://www.languagereactor.com/")
    *   这是个 chrome 插件，可以在看 youtube 的时候把英文字幕翻译成中文（或其他语言），并且能选中字幕中的单词查看释义甚至可以把单词加入生词库，在生词库可以使用类似 anki 的复习方式背诵单词

#### 安装 Obsidian 插件

直接在 Obsidian 里搜 Media Extended、Media Extended BiliBili Plugin 和 Regex Find and Replace 就可以下载了

#### 安装 chrome 插件

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/99893452290645fc85cadbdf08c24ded~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

#### 设置 Regex Find and Replace

修改该插件的源代码

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/d9136ac789a34628afdb2ac64dd944cd~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

```
let regDocumentText = documentText.replace(/(^[0-5]?[0-9])s$/gm, (rs, $1) => {  
    return ">👇[" + $1 + "s](" + replaceString + "#t=" + $1 + ")";  
});  
  

    return ">👇[" + $1 + ":" + $2 + "](" + replaceString + "#t=" + ($1 * 60 + $2 * 1) + ")";  
});  
  

    return ">👇[" + $1 + ":" + $2 + ":" + $3 + "](" + replaceString + "#t=" + ($1 * 60 * 60 + $2 * 60 + $3 * 1) + ")";  
});  
  
editor.setValue(regDocumentText);


```

第一个正则表达式 `([0-5]?[0-9])s$` 是转换 `xxs\n` 格式的字符串 第二个正则表达式 `([0-5]?[0-9]):([0-5][0-9])` 是转换 `m:ss` 或 `mm:ss` 格式的字符串 第三个正则表达式 `(([0-1]?[0-9]|2[0-3]):([0-5][0-9]):([0-5][0-9]))$` 是转换 `hh:mm:ss` 格式的字符串 以上统一最终转换为 `>👇[$1s](网址#t=$1)`

之所以要设置以上正则，是为了匹配 Language Reactor 生成的字幕文件，下面工作流会介绍到

然后设置一下该插件的快捷键：

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/be58d30d2a144338b39ac6c7c43f710a~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

### 日常工作流

#### 导出视频的中英字幕

先打开 Language Reactor

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/3628fda4ef794cd4aa4b193bed892aa5~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp?)

一开始打开某个视频可能默认是中文字幕，要改成英文的：

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/9d1e9ded153042559ba49bdde52d8c63~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

点击 **设置** 查看字幕情况：

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/9eca3064f3e94754952f86b524e358d8~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/ee6cf48473504280b3ba4b21f7b0571c~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

（一般没有人类翻译的话相应的单选框是选择不了的） 因为根据上图可以知道这个视频是有人类翻译的，所以导出字幕时可以仅仅导出英文字幕和人类翻译：

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/c2190891948d44599d90aff37e06d0de~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/8b042d26cd6f4a118ab4c57a71bc5cbc~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

接着按 **导出** 就会弹出字幕的 html：

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/a028ff6afcf246038febd491358fe5cf~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

接着 `ctrl + a` 全选整个 html 并且 `ctrl + c` 复制：

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/cd115b43083e41999b06b4bef6dcad34~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

新建新的关于这个视频笔记的 markdown 并插入自己设置好的视频模板（其实就只是一些元数据）：

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/46fc2cc0b2fe41a49c4c1e18bebc3d25~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/007287a09ce247b8a21d3701be6493d9~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

接着在这个 markdown 里 `ctrl + v` 一下，可以看到复制进来了，并且把选中的这三行没用的信息删了：

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/677e2b9f13e143d1bc4a9154e76e87b6~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

#### 使用正则替换修改字幕笔记的格式

复制一下视频的地址：

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/689527c00fa041bc8d6375300cc4ad65~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

回到刚刚新建的笔记，按 `ctrl + alt + f` 进行正则替换：

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/cc948d71105548209a411c18aca4b10e~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

可以看到替换成功了 👇

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/47cd39370e17430ea0b336f81fc80265~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

注意：想跳转视频一定要切换到 `查看视图`

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/971bbdbccf7d4d53aa2eac562360a9c6~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp?)

接着你就可以给这个视频的 markdwon 上做笔记了

## 连接图片

### 展示

![](https://p6-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/58dc500d7db1466694d951b780ed3e8e~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp?)

### 配置

#### 使用工具

*   [Excalidraw](https://link.juejin.cn/?target=https%3A%2F%2Fgithub.com%2Fzsviczian%2Fobsidian-excalidraw-plugin "https://github.com/zsviczian/obsidian-excalidraw-plugin")
    *   该插件可以在 obsidian 中画各种图（有点像 visio）
    *   可以去 [这里](https://link.juejin.cn/?target=https%3A%2F%2Fexcalidraw.com%2F "https://excalidraw.com/") 大概试用一下

#### 安装 Obsidian 插件

直接在 Obsidian 里搜

### 日常工作流

在需要跳转到某个笔记时，使用文字工具输入笔记链接就行了（语法和 Obsidian 的一样），如下图：

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/68d3a73b3da64f13991bd1ae4008fbe2~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

处理信息的方式可以模仿维基百科，毕竟是运转了那么多年的平台，肯定有可取之处 我认为处理信息有几个比较重要的点：

*   知识点原子化
*   知识点之间的链接跳转
*   可信度标识
*   知识点的转化
*   知识点的归类

## 知识点原子化和知识点之间的链接跳转

`知识点原子化` 和 `知识点之间的链接跳转` 之间是相辅相成的 比如知识点——红黑树，红黑树是一种自平衡二叉树，红黑树和自平衡二叉树是独立的两篇文章，红黑树这篇文章使用链接的方式跳转到自平衡二叉树，而不要因为红黑树和自平衡二叉树有关就把两者写在一篇文章内

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/a409f24a5c6f422186c68ea6b62aaed1~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

实际应用：

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/e5a25f48be384591ad0f52c59fb2461f~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

## 可信度标识

一般我对剪藏进笔记的文章都会添加上如下的可信度标识：（高参考价值的不需要标识）

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/cc412e75f6fc434590ddfb5b52ea268b~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

我简单列一下自己制定的 == 可信度标准 ==：

*   有标明可靠的信息源
    *   直接引用一手信息源
    *   其被引用的信息源有引用一手信息源
*   文章内容
    *   条理是否清晰
    *   是否有自己的思考，有自己对于一个知识的转化（图、费曼学习法式描述等等）

接着依托于以上的标准，我设置了以下 == 可信等级 ==：

为什么要设置可信度标准？ 因为网络上的信息良莠不齐，当你引用了这篇文章最好做一个标记，标记这个文章可不可信，如果不标记，等过一段时间回头看就不知道这篇文章靠不靠谱，如果不靠谱还信了里面的内容，那真的是害了自己

## 知识点的转化

每个网页的信息处理过程如下图的复选框，三个选项都完成后就要给该文件添加一个图标，标识该文件已经处理完成 在阅读文章的过程中，不是很重要的句子就用 `加粗`，特别重要的句子就用 `高亮`， 把文章阅读完成后写一个 `总结`，完成这三步才算真正看完一篇文章 `总结` 是可以是简单的知识导图，也可以是用自己的话去描述一遍（即费曼学习法）

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/3396b241ee004bd3920b0acb0cca6366~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

## 知识点的归类

在刚新建笔记时，给笔记添加标签，标签的作用就是分类

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/38015c389721495bb8f4968f3f8433e0~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

## 连接 anki

### 展示

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/6d93c3a0886e4912a83c421bf86a42d3~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp?)

### 配置

#### 使用工具

*   [Obsidian_to_Anki](https://link.juejin.cn/?target=https%3A%2F%2Fgithub.com%2FPseudonium%2FObsidian_to_Anki "https://github.com/Pseudonium/Obsidian_to_Anki")
    *   该插件可以将笔记内的一段文字导入到 anki，并且导入后成为一个卡片后还能跳转回 obsidian
    *   [安装流程](https://link.juejin.cn/?target=https%3A%2F%2Fgithub.com%2FPseudonium%2FObsidian_to_Anki "https://github.com/Pseudonium/Obsidian_to_Anki")

### 日常工作流

#### 初始创建

在笔记顶部添加：

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/52db005bc3554bbc9a94e7f722ddd606~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

`ctrl + alt + l` 格式化整篇笔记（可以同时将图片保存到自己的图床）

`alt + s` 删除笔记的多余空行

#### 添加卡片

卡片类型有两种：

*   Neuracache flashcard style
    *   即简单的正反面卡片
*   Cloze Paragraph style
    *   即挖空原文的卡片

**Neuracache flashcard style**

在问题后空格添加标签 #flashcard，在问题下紧接着的一行必须跟上回答

确保问题的顶部和答案的底部都有空行

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/69bbbb93ac1d4d8d817e8084570da9da~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

`alt + a` 同步到 anki

**Cloze Paragraph style**

这是完形填空式的笔记，两个空行之间的内容会被放进卡片中

用 `{}` 包围住需要挖空的文本，如果文本中有多个需要被挖空的对象，则全体一致使用 `{1:文本}`（冒号前的数字表示所属的分组，数字相同则属于同一组，同组的会同时被挖空）

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/615920b69a8a49bebe1d766ffa71cb48~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

出来的效果：

![](https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/92a8159aa45f4799b0f1ed9cfe9347ee~tplv-k3u1fbpfcp-zoom-in-crop-mark:1512:0:0:0.awebp)

`alt + a` 同步到 anki

#### 删除卡片

在生成的 id 上一行添加 `DELETE`

`alt + a` 同步到 anki

这篇文章末尾就不写参考了，因为纯纯是我的经验分享，如有雷同是他抄我的。 该给的链接都给了，希望大家不要忘了给那些开源插件点个 star 哦~

本博客所有文章除特别声明外，均采用 [CC BY-SA 4.0 协议](https://link.juejin.cn/?target=https%3A%2F%2Fcreativecommons.org%2Flicenses%2Fby-sa%2F4.0%2Fdeed.zh "https://creativecommons.org/licenses/by-sa/4.0/deed.zh") ，转载请注明出处！