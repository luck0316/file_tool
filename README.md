# 文件处理工具说明

## 简介
这是一个文件处理工具集合，提供了多个功能函数来处理文件，包括查找特定类型的文件、搜索敏感词等功能。

## 功能说明
### 根据用户的选择进行不同的处理，主要包括以下几种功能：

- **PE文件:** 递归查找指定目录下的所有PE文件。
- **加密PE文件:** 查找指定目录下的所有加密的PE文件。
- **查询敏感信息:** 在日志文件中搜索敏感词并保存到输出文件。
- **UE4资源文件和Unity资源文件：** 搜索并统计目录中的UE4 pak文件或者Unity AB资源文件。
- **APK文件:** 解包APK文件并将结果以JSON格式输出。


## 使用示例
> 请根据实际需求，选择合适的选择按照界面操作。

## 注意事项
- 在使用功能`查询敏感信息`时，需要提供敏感词列表和输出文件夹路径。
- `APK文件解包`，结果以JSON格式输出。
- 请确保已安装所有依赖项。
    - 解包APK文件时，请确保已安装zipfile模块
    - 确保已安装mmgui模块。地址：https://github.com/sandin/mmgui
