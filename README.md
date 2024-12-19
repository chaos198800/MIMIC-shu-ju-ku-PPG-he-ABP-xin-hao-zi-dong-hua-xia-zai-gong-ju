# MIMIC数据库PPG和ABP信号自动化下载工具

本仓库提供了一个用于自动化下载MIMIC在线数据库（PhysioBank ATM）中PPG信号和ABP信号的代码。该代码旨在帮助科研人员快速获取所需数据，避免手动一条一条下载的繁琐过程。

## 功能特点

- **自动化下载**：只需输入需要下载的folder数量，代码即可自动完成下载任务。
- **断点续传**：如果下载过程中因访问过于频繁导致中断，代码会记录已下载的folder位置，下次启动时可继续从断点处下载。
- **日志记录**：代码内置日志功能，记录每次下载的进度和状态，方便用户跟踪下载情况。

## 使用说明

1. **环境准备**：确保你的计算机上已安装Python环境，并安装所需的依赖库。
2. **配置参数**：根据需要修改代码中的配置参数，如下载的folder数量、保存路径等。
3. **运行代码**：运行代码，输入需要下载的folder数量，程序将自动开始下载。
4. **断点续传**：如果下载中断，再次运行程序时，代码会自动从上次中断的位置继续下载。

## 注意事项

- 本代码仅供学习使用，请勿用于商业用途。
- 下载过程中可能会因访问过于频繁导致中断，建议合理设置下载间隔时间。
- 请确保你有合法的权限访问MIMIC数据库，并遵守相关法律法规。

## 贡献

欢迎大家提出改进建议或提交代码优化，共同完善这个工具。

## 许可证

本项目采用MIT许可证，详情请参阅LICENSE文件。

## 下载链接

[MIMIC数据库PPG和ABP信号自动化下载工具](https://pan.quark.cn/s/0d825d7cbfa4)