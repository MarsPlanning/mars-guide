# Mars 开发规范

### 环境准备

1.所有 Mars 项目都应该放在同一个目录中
> 例如形成如下的目录结构:
>
> Mars
>
> -- mars-platform
>
> -- internal-api

2.添加环境变量：`MARS_PROJECT_ROOT`
> 例如: export MARS_PROJECT_ROOT=/Users/eRin/Documents/Develop/MultiPlatform/Projects/Mars

### Kotlin 编译器说明
基本所有 Kotlin 项目的 JvmTarget 都需要 1.8 以上，所以在开发前应该调整你的 Intellij-IDEA / Android-Studio 的设置
>  将 `Preferences | Other Settings | Kotlin Compiler | Target JVM version` 设置为 1.8
