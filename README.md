# 星穹铁道跃迁 - 原神祈愿记录导出工具

这个项目由[Genshin-Wish-Export](https://github.com/biuuu/genshin-wish-export/)与[Star-Rail-Warp-Export](https://github.com/biuuu/star-rail-warp-export)修改而来，功能基本一致。

一个使用 Electron 制作的小工具，需要在 Windows 64位操作系统上运行。

通过读取游戏日志或者代理模式获取访问游戏跃迁记录 API 所需的 authKey，然后再使用获取到的 authKey 来读取游戏跃迁记录。

## 使用说明

1. 下载工具后解压 - 下载地址: [Github](https://github.com/Dongyifengs/Warp-Export/releases/latest/download/StarRailWarpExport.zip)
2. 打开游戏的 `跃迁/祈愿` 历史记录

3. 点击工具的“加载数据”按钮

   ![加载数据](/docs/load-data.png)

   如果没出什么问题的话，你会看到正在读取数据的提示，最终效果如下图所示

   <details>
    <summary>展开图片</summary>

   ![预览](/docs/preview.png)

   </details>

如果需要导出多个账号的数据，可以点击旁边的加号按钮。

然后游戏切换的新账号，再打开跃迁历史记录，工具再点击“加载数据”按钮。

## Devlopment

```
# 安装模块
yarn install

# 开发模式
yarn dev

# 构建一个可以运行的程序
yarn build
```

## License

[MIT](https://github.com/Dongyifengs/Warp-Export/blob/main/LICENSE)
