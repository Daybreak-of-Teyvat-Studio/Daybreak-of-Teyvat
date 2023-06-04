# 提瓦特黎明（Daybreak of Teyvat）

## 介绍
TODO

## 第一次进入开发请看这里
- 如何克隆（下载）仓库到本地
  - （**推荐方式**）安装GitHub Desktop后，在网页仓库的右上角“Code”处，选择“Open with GitHub Desktop”，然后选择要存放的本地路径。
    - 或者直接在本地打开GitHub Desktop，克隆仓库`https://github.com/Daybreak-of-Teyvat-Studio/Daybreak-of-Teyvat.git`。
  - （**不推荐**）喜欢用命令行的开发者可选择：先确保已安装Git，然后在要存放的本地路径打开命令行，输入：
    ```shell
    git clone https://github.com/Daybreak-of-Teyvat-Studio/Daybreak-of-Teyvat.git
    ```
- 一些推荐配置
  - 打开.git/config文件（.git是隐藏文件夹，看不到的话可以百度如何查看隐藏文件夹），在末尾添加：
    ```
    [pull]
        rebase = true
    ```
## 开发流程
可参考群内的演示录屏
1. 本地修改开发
2. 在GitHub Desktop左下角填写提交注释，并点击commit按钮提交
    - 建议在每个提交中写清楚修改内容，以方便自己或其他开发者查看
3. 点击右上角Push，推送到github上
    - 如不显示Push，说明此时github已有其他人提交修改。需要你先点击右上角的pull，把别人的最新修改拉取到你的本地，再进行Push
4. Push完成，就可以在github上看到你的修改了

## 发布流程
可参考群内的演示录屏
1. 点击右上角Fetch（或者有时候显示是Pull），拉取github上的最新代码到本地，确保自己本地的代码与github上的代码相同
2. 对**src**文件夹下的文件进行打包，并上传到steam

## 工作计划
TODO
