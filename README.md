# DensityDesign
px2dp、px2sp
## 资源文件用px转换dp和sp，入设计图给的图片尺寸是 200px X 300px，那么在布局文件中直接写px200_to_dp和px300_to_dp即可

# 如何使用 DensityDesign
###### 1、在项目的根build.gradle文件中，添加仓库地址，就像下面一样
```xml
allprojects {  
	repositories {  
		...  
		maven { url 'https://jitpack.io' }  
	}  
}
```

###### 2、在app的build.gradle中添加如下依赖
```xml
dependencies {  
	implementation 'com.github.duxl:DensityDesign:1.0'  
}
```
