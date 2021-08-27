# mirai-devicejs-analyze

转换 `Mirai` 运行时需要的 `device.json` 信息

**将 device.json 中的 Byte 数组转为 string**

在线使用：<https://pbk-b.github.io/mirai-devicejs-analyze/>

该工具参考 [ryoii/mirai-devicejs-generator](https://github.com/ryoii/mirai-devicejs-generator) 设计，mirai-devicejs-generator 可以直接生成 `device.json` 文件。

### 说明

`device.json` 数据来着于登录设备，请在了解生成 `device.json` 的作用再进行操作，否则可能危害账号安全

### 作用

为首次使用 `Mirai bot` 的账号提供高信任度的 `device.json` 数据。

请将 Bot 在正常环境下登录一段时间后，获取登录设备的信息，填写到生成器中生成 `device.json` 信息。

当 Bot 发生设备迁移时，一并携带 `device.json` 迁移，可以提高 Bot 登录的成功率。
