﻿# UaoanSharedSqlite
 封装SharedPreferences，数据共享
### 集成
 **1.在 project 的 settings.gradle 文件中找到 allprojects{} 代码块添加以下代码：** 

```
allprojects {
    repositories {
        mavenCentral()
        maven { url 'https://jitpack.io' }      //增加 jitPack Maven 仓库
    }
}
```
 **在 app 的 build.gradle 文件中找到 dependencies{} 代码块，并在其中加入以下语句：** 

```
implementation 'com.github.uaoan:UaoanSharedSqlite:1.0'
```
