# Cordova MiPush Plugin

支持Android、IOS的Cordova小米推送插件

## 集成步骤

- 通过Url安装:
	
		cordova plugin add https://github.com/fengfei153/mipush-cordova-plugin.git --variable MI_PUSH_APP_KEY=your_mipush_appkey --variable MI_PUSH_APP_ID=your_mipush_appid
		
- 或者下载本地安装

		cordova plugin add Your_Plugin_Path --variable MI_PUSH_APP_KEY=your_mipush_appkey --variable MI_PUSH_APP_ID=your_mipush_appid

## API 说明

插件的 API 在 MiPush.js 文件中，该文件的具体位置如下：

### Android
	[Project]/assets/www/plugins/cordova-plugin-mipush/www

### 具体的 API 请参考：

- [API](/doc/api.md)

## 感谢

- [极光推送cordova插件](https://github.com/jpush/jpush-phonegap-plugin)
- [cordova小米推送插件 安卓版实现](https://github.com/ParadiseHell/mipush-cordova-plugin)

## 更多

- 本项目参考极光推送cordova插件编写
