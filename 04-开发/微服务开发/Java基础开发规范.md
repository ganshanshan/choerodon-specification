## 规范检查

本地开发开启两种规范检查，一种为sonarQube的规范检查，一种为基于sun和google的checkStyle规范检查。

同时在CI的SonarQube代码检查中也生效了这两种规范检查，控制代码质量。

 1. 本地开启sonarQube规范检查：

    在Idea中安装sonarLint插件：

    ![](./image/pluginInstall1.png)

    ![](./image/pluginInstall2.png)

    指定本地修改的文件或者全项目检查：

    ![](./image/sonarSetting.png)

    查看不符合检查的地方：

    ![](./image/sonarResult.png)

 1. 本地开启checkStyle规范检查,注意更新插件，否则部分规则不适用于旧版本会报错：

    在Idea中安装CheckStyle-IDEA插件，步骤与上面安装插件一样

    生效checkStyle中checkStyle的规范config：

    <a href="choerodon_checkStyle.xm">choerodon_checkStyle.xm</a>

    ![](./image/sonarResult.png)

附:

sonarQube规范检查规则链接：<a href="SonarRules">SonarRules</a>

googleCheck规范检查规则链接：<a href="googleCheck">googleCheck</a>

alibaba p3c代码规范：<a href="aliP3c">aliP3c</a>

## idea设置
 1. 修改import分组、排序规则

    ![](./image/java_import.png)

 1. 换行设置

    ![](./image/warp_setting.png)

 1. tab设置
  
    ![](./image/tab_setting.png)




