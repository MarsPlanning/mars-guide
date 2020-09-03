# Mars 开发规范

### 环境准备

1.将此目录克隆到本地，然后将文件夹改名为 Mars，后续的所有相关项目都应该放在此目录中（方便开发时的项目联动）
> 例如形成如下的目录结构:
>
> Mars/
>
> -- source-app/
>
> -- internal/
>
> -- version.properties

2.添加环境变量：`MARS_PROJECT_ROOT`
> 例如: export MARS_PROJECT_ROOT=/Users/Rin/Documents/Develop/MultiPlatform/Projects/Mars

### Kotlin 编译器说明
Mars 所有项目都基于 Kotlin 1.4 开发，所以 JvmTarget 都需要 1.8 以上，在开发前应该调整你的 Intellij-IDEA / Android-Studio 的设置
>  `Preferences | Other Settings | Kotlin Compiler`
> 1. Language version 设置为 1.4
> 2. API version 设置为 1.4
> 3. Target JVM version 设置为 1.8


### 代码规范
建议优先使用二格缩进的代码风格 [参考](https://github.com/square/kotlinpoet/issues/659#issue-427238344) （真实性未知，但二格缩进在 Mars 项目开发上可能会更加适合与美观，特别是使用 Kotlin 编写 [UIKit](https://github.com/MarsPlanning/uikit) 时）
