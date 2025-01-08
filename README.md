# UDL-Solution-Manual

本仓库用于维护《Understanding Deep Learning》(UDL)一书的习题解答。

## 仓库结构

- `src/`: 存放LaTeX源文件的目录

## Setup
1. **环境配置**
  安装 Git：确保本地已安装 Git。如果未安装，可以从 Git 官网 下载并安装。
  配置用户名和邮箱（如果尚未设置）：
  ```bash
  git config --global user.name "Your Name"
  git config --global user.email "your.email@example.com"
  ```
2. **克隆仓库** `$ git clone https://github.com/OpenSubmarine-X/UDL-Solution-Manual.git`
   
## 协作流程
1. **创建分支**: 从 `main` 分支创建一个新的分支, 将你的分支推送到远程仓库`git push origin <branch-name>`。
2. **提交题解**: 在新分支上进行你的更改`./src/Chx.tex`，并提交题解。`git add -> commit -> push`
3. **提交 Pull Request**:
   1. Navigate to `Pull request`
   2. create `new pull request`
   3. base: main <- compare `<your branch>`
   4. get feedback (complied pdf file about your change)
4. **开会交流题解**: 通过每周会议大家一起交流题解 
