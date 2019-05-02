	安装使用说明
适用范围：针对visual studio 2017/2019
1.执行注册表脚本添加必须项: add_vs2017-2019.reg
2.复制WTL到\Enterprise\Common7\IDE\VC\vcprojects目录下
3.复制Include下所有文件到C:\Program Files (x86)\Microsoft Visual Studio 14.0\VC\include和\Enterprise\VC\Auxiliary\VS\include目录下
4.执行\Enterprise\Common7\IDE\VC\vcprojects\WTL\Templates下的Setup.js文件安装
5.安装成功后
  删除\Enterprise\Common7\IDE\VC\vcprojects\WTL\Templates目录下的Setup.js文件
  删除\Enterprise\Common7\IDE\VC\vcprojects\WTL\Templates\Items目录下的WTL10AppWiz.ico、WTL10AppWiz.vsdir、WTL10AppWiz.vsz文件