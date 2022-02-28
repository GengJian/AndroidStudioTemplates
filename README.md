# AndroidStudioTemplates
整理AndroidStudio使用上一些小技巧

# Live Templates
> 便于快速且格式化创建文件，如Activity,layout_xml等，Android Studio提供了模版化配置。


### 设置目录
Preference - Editor - File and Code Templates
![avatar](/Templates/as-settings-templates.png)

### 将自动创建的XML文件包裹layout标签，默认开启viewbinding
修改 layoutResourceFile.xml 和layoutResourceFile_vertical.xml 

``` xml
<?xml version="1.0" encoding="utf-8"?>
<layout>
    <!-- 创建默认带layout标签的xml布局文件 -->
    <${ROOT_TAG} xmlns:android="http://schemas.android.com/apk/res/android"
        android:layout_width="match_parent"
        android:layout_height="match_parent">

    </${ROOT_TAG}>
</layout>

```