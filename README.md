# The official ZMK config of Algeboard (V1/V2 before 2024)

## Build firmware with Github Actions

### Preparing

- Fork the repo, or click the "Use this template" button to include all the branches
- After the fork, Make sure the Github Action of your repo is enabled

### Customize keymap

- Open the [keymap editor](https://nickcoutsos.github.io/keymap-editor/), then select the algeboard-config of your own.
- Click the key and change it as you like. Here is the full list of code available (https://zmk.dev/docs/codes)
- Click the "commit change" button at the right bottom of the page to start building. 
- It takes 4 - 7 minutes to build the firmware. Once it is finished, Click the "firmware" button, you'll be redirect to the Github Action page. Click the firmware link to download the firmware.
- Add more layer as you like, remember to take a look at the document of [ZMK layer](https://zmk.dev/docs/behaviors/layers)

# Algeboard ZMK 配置(V1/V2 2024年之的版本)

!!⚠️ 新版本升级了主控，不能使用该仓库构建。

## 使用 Github Actions 构建键盘固件

### 准备工作

- 克隆这个仓库，或者点击“使用该模版” 按钮
- 克隆完成后，确保仓库 Github Action 是开启的。

### 自定义键映射

- 打开[自定义键盘映射网页](https://nickcoutsos.github.io/keymap-editor/), Source 选择 Github，如果是第一次，需要进行 Github 授权，授权成功后选择刚开克隆的仓库。
- 点击任意key，可以更改键位，完整的键位列表可以参考链接 https://zmk.dev/docs/codes. 
- 修改完成后点击 Save 按钮，Github Action 会自动开始构建固件。
- 该过程大概需要几分钟，等打包完成后，点击 fireware 按钮，跳转到 Github Action 的页面，页面下方有一个 fireware 的链接，点击链接即可下载固件。
- 更多高级功能参考 [ZMK 文档](https://zmk.dev/docs/behaviors/layers)

