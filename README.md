opencms-zh
==========

opencms 汉化
这个版本的汉化工作 适用于OC 9.0.x

开始之前的话：

汉化是一个很简单，单调，但非常重要的工作。您的工作，任何一个使用汉化版的人员都能看见， 都会感谢您的工作。为了您的荣耀，请在开始之后不要半途而废。至少要完成一个文件的翻译。开始之前请先申请GITHUB帐号，在QQ群里告诉管理员，添加到项目中去。

opencms 汉化工作步骤
<ol>
<li>先pull org.opencms.locale.zh 文件， 在这个文件夹中有德语文件，以及对应的中文文件，中文文件是8.01版的汉化包</li>
<li>在本地翻译吧，建议采用eclipse， 使用localized properties editor, 可以在eclipse marketplace 中搜索localized properties,然后安装插件，使用这个插件，你就会知道为什么，在一个文件夹中同时有德语文件和中文文件的好处了</li>
<li>汉化完毕了以后，push 上去，就可以了 “git push origin master”，</li>
</ol>
选择了要翻译的文件以后，请立刻先上传文件，这样别人就知道你的选择了。
请在属性文件的开头加注释， 参见https://github.com/js-oss/opencms-zh/blob/master/org.opencms.locale.zh/resources/system/workplace/locales/zh/messages/org/opencms/ade/clientmessages_zh.properties 又可以让别人知道这是你的贡献， 又可以避免别人重复翻译。
<br>
对git 使用不熟悉的同学， 可以在github 上面 在线翻译，修改。
<br>
在线修改步骤方式
<ol>
<li>git pull org.opencms.locale.zh 文件夹</li>
<li>本地翻译，建议采用eclipse， 使用localized properties editor, 可以在eclipse marketplace 中搜索localized properties,然后安装插件，使用这个插件，你就会知道为什么，在一个文件夹中同时有德语文件和中文文件的好处了</li>
<li>在github.com上找到你翻译的文件， 点击 edit， 把你翻译的内容复制进去， commit。就ok了</li>
</ol>
