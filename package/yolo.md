${AnsiColor.MAGENTA}
_ __ ___  _ __   __ _  __ _ ___
| '_ ` _ \| '_ \ / _` |/ _` / __|
| | | | | | |_) | (_| | (_| \__ \
|_| |_| |_| .__/ \__,_|\__,_|___/
          | |
          |_|
:: Java         :: ${java.version}
:: Spring Boot  :: ${spring-boot.version}
Application ${application.title}: ${application.version}
${AnsiStyle.NORMAL}

yolo-token: pv1zbxeyTEyezeGH4SCv

1. method-name
       clazz.method();
       clazz.method0(); //inner invoke method
2. DBUtil.groovy
3. @Slf4j
4. org.apache.commons.fileupload
5. Music-plugin 
6. Thread#interrupt() 通知作用，没有直接唤起
7. FileOutputStream 没有文件会自动创建
8. 简单的http服务器
    1. python2: python -m SimpleHTTPServer 10086
    2. python3: python -m http.server 10086
9. File.separator
10. wsl crontab -l
11. -threads 5 -preset ultrafast 
12. ObjectMapper#readValue
13. torque
14. Files.readAllBytes(file.toPath())
15. jar打包 https://blog.csdn.net/tian830937/article/details/119580796
16. Runtime.getRuntime(exec(cmd, null, workPath))
17. Go To Test 快速创建Test类

+------+----------------------+--------------------------+-----------------+
|序号  |服务名                |镜像tag                   |镜像ID        |
+------+----------------------+--------------------------+-----------------+
|1     |proxyv2               |6.2.9                     |3d81a3fd0c05  |
|14    |suse12sp5x86          |ITInfra1.1.1.20210927     |67997472df5b  |
+------+----------------------+--------------------------+-----------------+

ToDo Project

- 类Apollo 配置中心
- 消息推送
- 任务调度
- Jenkins 
    - TESTNG: https://www.cnblogs.com/jinjiezhilu/p/6856742.html
- 组件 https://lew.kamtao.com/#/BackTop
- jmockit hsqldb junit5
- blog-docker https://vanblog.mereith.com/intro.html
- simple spring https://solon.noear.org/
- simple db https://competition.huaweicloud.com/information/1000041405/circumstance
- axios request封装
- vue-cli
- https://stackoverflow.com/questions/309424/how-do-i-read-convert-an-inputstream-into-a-string-in-java
- http://c.biancheng.net/spring_boot/overview.html
- https://panjiachen.github.io/awesome-bookmarks/
- vue3 组件 https://fighting.tianyuhao.cn/
- anytxt-tool https://github.com/echohw/anytxt-tool
- ruoyi-vue https://github.com/YunaiV/ruoyi-vue-pro

视频
- https://youtu.be/6Zt33FoCQ_A?t=1279
- https://oschina.gitee.io/learn-git-branching/
- https://github.com/erwanjun/weixin_tuisong


软件：
- 录像 faststone
- 剪切板 ditto
- 


bat
- 赋值时，等号两侧不能加空格
- 取变量值 %val%
- 输入 %0-%9


其他
- ffmpeg： 奇乐
```
FFMPEG_PATH("FFMPEG System Environment Path", "ffmpeg "), SIMPLE_CLIP("IN-START-END-OUT", " -ss %s -i \"%s\" -to %s -c copy \"%s\""), CREATE_COVER("TIME-IN-OUT", " -ss %s -i \"%s\" -vframes 1 -q:v 1 \"%s\""), REPLACE_COVER("IN-PIC-OUT", " -i \"%s\" -i \"%s\" -map 1 -map 0 -c copy -disposition:0 attached_pic -y \"%s\"");  
```
- 



💍 test: Adding missing tests
🎸 feat: A new feature
🐛 fix: A bug fix
🤖 chore: Build process or auxiliary tool changes
✏️ docs: Documentation only changes
💡 refactor: A code change that neither fixes a bug or adds a feature
💄 style: Markup, white-space, formatting, missing semi-colons...
