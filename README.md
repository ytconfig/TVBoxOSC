# TVBoxOSC
云编译TVbox--M
前提条件：有一github账号(比如ABC)
步骤：
fork 项目https://github.com/Wsine/android_builder
fork 项目https://github.com/CatVodTVOfficial/CatVodTVOSC
至此，ABC账号下有上述两项目，
https://github.com/ABC/android_builder
https://github.com/ABC/CatVodTVOSC
以下操作只针对此两项目;
3.1修改android_builder项目下的project-to-build文件里的地址为https://github.com/ABC/CatVodTVOSC
3.2修改CatVodTVOSC项目下app/src/main/java/com/github/tvbox/osc/api/ApiConfig.java此文件的127行，把"http://10.80.8.70:8890/baddychen/baddychen.json"改为你自己的接口JSON文件地址
3.3点击android_builder项目的Action，详细操作可参阅https://github.com/Wsine/android_builder的readme，此处特别感谢Wsine！！！当然更感谢CatVodTVOSC项目组所有人！！！
坐等2分钟，下载安装即可最先使用TVbox
