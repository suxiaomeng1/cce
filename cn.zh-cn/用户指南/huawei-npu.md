# huawei-npu<a name="cce_01_0239"></a>

## 插件简介<a name="section173631312185614"></a>

huawei-npu是支持容器里使用huawei NPU设备的管理插件。

## 使用约束<a name="section11172124718374"></a>

此插件支持[混合集群](购买混合集群.md)、[裸金属集群](购买裸金属集群.md)和[鲲鹏集群](购买鲲鹏集群.md)，集群版本需在1.13以上版本。

## 安装插件<a name="section189463341114"></a>

安装本插件后，可在“资源管理 \> 集群管理“中通过购买集群选用“AI加速型“节点，实现快速高效地处理推理和图像识别等工作。具体请参见[购买混合集群](购买混合集群.md)-[AI加速型](购买混合集群.md#li2017145914913)。

1.  在[CCE控制台](https://console.huaweicloud.com/cce2.0/?utm_source=helpcenter)中，单击左侧导航栏的“插件管理“，在“插件市场“页签中，单击**huawei-npu**下的“安装插件“按钮。
2.  在安装插件页面，选择安装的集群和插件版本，单击“下一步：规格配置“。
3.  该插件暂未开放可配置参数，直接单击“安装“。

    待插件安装完成后，单击“返回插件管理“，在“插件实例“页签中，选择对应的集群，可查看到运行中的实例，这表明该插件已在当前集群的各节点中安装。


## 卸载插件<a name="section1395073191112"></a>

1.  在[CCE控制台](https://console.huaweicloud.com/cce2.0/?utm_source=helpcenter)中，单击左侧导航栏的“插件管理“，在“插件实例“页签中，选择对应的集群，单击**huawei-npu**下的“卸载“。
2.  在弹出的窗口中，单击“确认“，可卸载该插件。

