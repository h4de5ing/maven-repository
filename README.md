# 基础框架依赖仓库

- 业务无关代码依赖库
- 重复代码块
- 常用UI组件
- 实用功能封装

# 使用方法

```
allprojects {
    repositories {
        google()
        jcenter()
        maven { url 'https://gitee.com/lex1992/repository/raw/master/repository' }
        maven { url 'F://repository/repository/repository' }
    }
}
```

项目依赖

- 基础库

```
dependencies {
    implementation 'com.github.h4de5ing.base:base:1.0-20210125'//基础工具
    implementation 'com.github.h4de5ing.gsoncommon:gsoncommon:1.0-20210122'//json解析工具
    implementation 'com.github.h4de5ing.netlib:netlib:1.0-20210126'//网络工具
}
```

