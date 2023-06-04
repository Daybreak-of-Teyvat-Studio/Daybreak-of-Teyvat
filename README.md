# 提瓦特黎明（Daybreak of Teyvat）

## 介绍
TODO

## 第一次进入开发请看这里
- 如何克隆（下载）仓库到本地
  - （**推荐方式**）安装GitHub Desktop后，在网页仓库的右上角“Code”处，选择“Open with GitHub Desktop”，然后选择要存放的本地路径。
    - 或者直接在本地打开GitHub Desktop，克隆仓库`https://github.com/Daybreak-of-Teyvat-Studio/Daybreak-of-Teyvat.git`。
    - 喜欢用命令行的开发者可选择：先确保已安装Git，然后在要存放的本地路径打开命令行，输入：
      ```shell
      git clone https://github.com/Daybreak-of-Teyvat-Studio/Daybreak-of-Teyvat.git
      ```
- 一些推荐配置
  - 打开.git/config文件（.git是隐藏文件夹，看不到的话可以百度如何查看隐藏文件夹），在末尾添加：
    ```
    [pull]
        rebase = true
    ```
    - 也可采用命令行：
      ```shell
      git config pull.rebase true
      ```
- 更好地编辑（适用于桌面端）
  1. 前往[VSCode官网](https://code.visualstudio.com/)下载并安装Visual Studio Code。
  2. 前往[Git官网](https://git-scm.com/download/win)下载并安装Git。
  3. 重启计算机以应用对Path的更改（这步很重要，不要问我怎么知道的）。
  4. 启动终端，输入：
    ```shell
    git config --global user.name <你的GitHub账户名>
    git config --global user.email <你注册GitHub用的邮箱>
    ```
  5. 参照上文克隆repo后，启动VSCode，按指示设置主题，安装简中语言包。
  6. VSCode重启后，选择文件->打开文件夹，选取本地克隆的仓库。
  7. 文件->将工作区另存为->保存。
  8. 侧边栏选择“扩展”，搜索并安装"GitLens"（Git可视化）与"CWTools"（P社语言支持）。
  9. TODO
## 开发流程
TODO

## 发布流程
TODO

## 工作计划
TODO
