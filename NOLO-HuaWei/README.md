# NOLO-HuaWei
## 使用说明  
* 新建一个Unity工程，将NOLO_for_HUAWEI.unitypackage导入工程中。
* 新建一个场景，将NVR/Prefabs/NoloManager放入场景中，并保存。
* 填写正确的Appkey到NoloVR_AppInfo.cs脚本中。
* Player Settings中转换到安卓平台，修改Package Name之后，打包即可。
 

## NOLO SDK 2.0.17更新说明 
* 新增NoloVR_Playform.GetInstance().IsInstallServer()方法，返回设备是否安装了NOLO服务，取消了未安装NOLO服务时弹出的2D窗口，开发者可以自行设计窗口，仅对安卓设备有效。
* 新增NoloVR_Playform.GetInstance().IsStartUpServer()方法，返回设备的NOLO服务是否已经启动，取消了NOLO服务未启动时弹出的2D窗口，开发者可以自行设计窗口，仅对安卓设备有效。
