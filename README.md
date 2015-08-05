#ExMobi Lite
ExMobi Lite框架是用于UIXML中的类似于jQuery的JS框架。用法类似于$(selector)。<br>
使用时需引用core.js（核心类）和template.js（artTemplate的简洁语法，用于数据注入，如需使用原生语法请引用template-native，使用方法不变，请参考https://github.com/aui/artTemplate）。<br>
ExMobi Lite默认会占用$作为操作符，如有其它框架也使用了$作为操作符，请最后引用ExMobi Lite，这时候ExMobi Lite将出让$的使用权。可以使用ExMobiLite(selector)代替原$操作。<br>
当ExMobi Lite出让$使用权的时候，可以通过ExMobiLite.noConflict()挂靠新的操作符，比如：var $a = ExMobiLite.noConflict();后续则可通过$a(selector)进行操作。<br>
<br><br>


#参考文档
ExMobi Lite框架的使用文档可以通过访问<http://bbs.exmobi.cn/thread-4453-1-1.html>查看其使用方法。
#使用建议
ExMobi Lite是基于ExMobi移动应用平台封装的框架，所以需要对ExMobi有所了解，可以通过访问<http://www.exmobi.cn/>获得更多帮助
#License
The MIT license.
<br>
