# NOLO-HuaWei
## 使用说明  
* 新建一个Unity工程，将NOLO_for_HUAWEI.unitypackage导入工程中。
* 新建一个场景，将NVR/Prefabs/NoloManager放入场景中，并保存。
* 填写正确的Appkey到NoloVR_AppInfo.cs脚本中。
* Player Settings中转换到安卓平台，修改Package Name之后，打包即可。
 

## NOLO SDK 2.0.16更新说明 
* 新增NoloClientSo.cs脚本，替换原来NoloVR_Plugins.API下的方法。
* 废弃移动端SetHmdType方法，NoloVR_Appinfo不再需要勾选平台
* 更新androidsdkclient-normal-release.aar文件，解决安卓8.0系统下server无法被调起导致的崩溃问题，需要将server更新到1.0.56版本以上