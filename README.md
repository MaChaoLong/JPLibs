# JPLibs

**开发了这么多项目，每一次都是复制粘贴，代码复用性根本没有得到提升，所以整合了经常使用的Github上各路大神的框架，进行了简单的封装，对于一般的功能和效果都可以得到实现，只是希望自己在开发新项目时，不用再一个一个找了......**

## 依赖
```Java
allprojects {
    repositories {
	...
	maven { url 'https://jitpack.io' }
    }
}

dependencies {
	...
	api 'com.github.JiaoPengJob:JPLibs:1.0.0'
}
```
## 使用
