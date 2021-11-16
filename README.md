# AutoJD

京东自动签到领京豆脚本<br>

## ！！！需要nodejs运行环境！！！<br>

## 参考了多位大佬的开源配置，但是实在是找不到原作者是谁。。所以就不挂了，如您认为此项目侵犯了您的权益请通知我将其移除<br>

# 使用先决条件：<br>
1.一台部署了nodejs运行环境的设备<br>
2.京东账号登录的cookie<br>

# 使用说明：<br>
1、将JD这个目录整个上传到您的设备上，并确保其拥有执行权限<br>
2、修改jdCookie.js文件，按照注释填写即可（仅需填写你获取到的cookie，其他保持默认，支持多账号同时挂）<br>
2.5、修改sendNotify.js文件，依旧是按照注释填写，这个文件是用来做推送的，支持server酱、企业微信、bark之类的，按照需求修改（Bark不太好使，目前正在解决，解决了之后会放更新）<br>
3.在JD目录内执行以下操作：<br>
  npm init -f #初始化项目
  npm install formidable --save #安装依赖
  npm i download #安装依赖
  npm i formidable #安装依赖
  npm i request #安装依赖
  npm i tough-cookie #安装依赖
  node jd_bean_sign.js #运行签到脚本
4.将node jd_bean_sign.js这条指令添加到您系统的计划任务中，每天执行一次即可，因为大家用的系统可能都不一样，所以这里就不详细写了，如果不会搞自行百度。
