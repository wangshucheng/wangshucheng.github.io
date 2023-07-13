---
layout:     post
title:      GameFramwork
date:       2020-06-29
summary:    Unity通用游戏框架
categories: unity
---

https://github.com/wangshucheng/ZYSGameFramwork

Unity游戏框架

```
│─Framework\
│  │─ActionSystem\
│  │  │─ActionManager.cs
│  │─Application\
│  │  │─ApplicationManager.cs
│  │  │─ApplicationStatusManager.cs
│  │  │─IApplicationStatus.cs
│  │─ConfigSystem\
│  │  │─Language\
│  │  │  │─LanguageManager.cs
│  │  │─LocalConfigManager.cs
│  │  │─WebConfigManager.cs
│  │─DebugSystem\
│  │  │─MemoryManager.cs
│  │─Develop\
│  │  │─Attribute\
│  │  │  │─ResourcesFieldAttribute.cs
│  │  │─FPSCounter.cs
│  │  │─GUIConsole.cs
│  │  │─GUIUtil.cs
│  │  │─Log.cs
│  │  │─LogOutPutThread.cs
│  │  │─MemoryDetector.cs
│  │  │─SystemInfo\
│  │  │  │─Plugins\
│  │  │  │  │─DeviceUniqueIdentifier\
│  │  │  │  │  │─DeviceUniqueIdentifierHandle.cs
│  │  │  │  │─MemoryInfo\
│  │  │  │  │  │─iOS\
│  │  │  │  │  │  │─igetRam.mm
│  │  │  │  │  │─MemoryInfo.cs
│  │  │  │─SystemInfoManager.cs
│  │─Effect\
│  │  │─CameraFade.cs
│  │  │─CameraShoke.cs
│  │  │─Editor\
│  │  │  │─GameViewSizeAdder.cs
│  │  │  │─GameViewSizeHelper.cs
│  │  │─LiuHaiFade.cs
│  │─EventSystem\
│  │  │─EventEnum.cs
│  │  │─EventManager.cs
│  │─HotUpdate\
│  │  │─HotUpdateManager.cs
│  │─ModelSystem\
│  │  │─BaseModel.cs
│  │  │─GlobalModel.cs
│  │  │─IModel.cs
│  │  │─ModelManager.cs
│  │─NetworkSystem\
│  │  │─HttpRequestManager.cs
│  │  │─IHttpRequest.cs
│  │  │─ISocketClient.cs
│  │  │─ISocketServer.cs
│  │  │─SampleSocket\
│  │  │  │─Doc\
│  │  │  │  │─Socket框架流程图.png
│  │  │  │─ProtoGen\
│  │  │  │  │─BuildCS.bat
│  │  │  │  │─common.xslt
│  │  │  │  │─csharp.xslt
│  │  │  │  │─Licence.txt
│  │  │  │  │─protobuf-net.dll
│  │  │  │  │─protobuf-net.xml
│  │  │  │  │─protoc-license.txt
│  │  │  │  │─protocal_loginserver.cs
│  │  │  │  │─protocal_loginserver.proto
│  │  │  │  │─protogen.exe
│  │  │  │  │─protogen.exe.config
│  │  │  │  │─vb.xslt
│  │  │  │  │─xml.xslt
│  │  │  │  │─说明文档.txt
│  │  │  │─README.md
│  │  │  │─Socket\
│  │  │  │  │─Assets\
│  │  │  │  │  │─Scripts\
│  │  │  │  │  │  │─Client.cs
│  │  │  │  │  │  │─GameConst.cs
│  │  │  │  │  │  │─Server.cs
│  │  │  │  │  │  │─Socket\
│  │  │  │  │  │  │  │─ByteStreamBuff.cs
│  │  │  │  │  │  │  │─DataBuff.cs
│  │  │  │  │  │  │  │─EventDefinition.cs
│  │  │  │  │  │  │  │─MessageCenter.cs
│  │  │  │  │  │  │  │─protobuf\
│  │  │  │  │  │  │  │  │─BclHelpers.cs
│  │  │  │  │  │  │  │  │─BufferExtension.cs
│  │  │  │  │  │  │  │  │─BufferPool.cs
│  │  │  │  │  │  │  │  │─CallbackAttributes.cs
│  │  │  │  │  │  │  │  │─Compiler\
│  │  │  │  │  │  │  │  │  │─CompilerContext.cs
│  │  │  │  │  │  │  │  │  │─CompilerDelegates.cs
│  │  │  │  │  │  │  │  │  │─Local.cs
│  │  │  │  │  │  │  │  │─DataFormat.cs
│  │  │  │  │  │  │  │  │─Extensible.cs
│  │  │  │  │  │  │  │  │─ExtensibleUtil.cs
│  │  │  │  │  │  │  │  │─GlobalSuppressions.cs
│  │  │  │  │  │  │  │  │─Helpers.cs
│  │  │  │  │  │  │  │  │─IExtensible.cs
│  │  │  │  │  │  │  │  │─IExtension.cs
│  │  │  │  │  │  │  │  │─ImplicitFields.cs
│  │  │  │  │  │  │  │  │─KeyValuePairProxy.cs
│  │  │  │  │  │  │  │  │─Meta\
│  │  │  │  │  │  │  │  │  │─AttributeMap.cs
│  │  │  │  │  │  │  │  │  │─BasicList.cs
│  │  │  │  │  │  │  │  │  │─CallbackSet.cs
│  │  │  │  │  │  │  │  │  │─MetaType.cs
│  │  │  │  │  │  │  │  │  │─RuntimeTypeModel.cs
│  │  │  │  │  │  │  │  │  │─SubType.cs
│  │  │  │  │  │  │  │  │  │─TypeFormatEventArgs.cs
│  │  │  │  │  │  │  │  │  │─TypeModel.cs
│  │  │  │  │  │  │  │  │  │─ValueMember.cs
│  │  │  │  │  │  │  │  │─NetObjectCache.cs
│  │  │  │  │  │  │  │  │─PrefixStyle.cs
│  │  │  │  │  │  │  │  │─ProtoContractAttribute.cs
│  │  │  │  │  │  │  │  │─ProtoEnumAttribute.cs
│  │  │  │  │  │  │  │  │─ProtoException.cs
│  │  │  │  │  │  │  │  │─ProtoIgnoreAttribute.cs
│  │  │  │  │  │  │  │  │─ProtoIncludeAttribute.cs
│  │  │  │  │  │  │  │  │─ProtoMemberAttribute.cs
│  │  │  │  │  │  │  │  │─ProtoReader.cs
│  │  │  │  │  │  │  │  │─ProtoWriter.cs
│  │  │  │  │  │  │  │  │─SerializationContext.cs
│  │  │  │  │  │  │  │  │─Serializer.cs
│  │  │  │  │  │  │  │  │─Serializers\
│  │  │  │  │  │  │  │  │  │─ArrayDecorator.cs
│  │  │  │  │  │  │  │  │  │─BlobSerializer.cs
│  │  │  │  │  │  │  │  │  │─BooleanSerializer.cs
│  │  │  │  │  │  │  │  │  │─ByteSerializer.cs
│  │  │  │  │  │  │  │  │  │─CharSerializer.cs
│  │  │  │  │  │  │  │  │  │─CompiledSerializer.cs
│  │  │  │  │  │  │  │  │  │─DateTimeSerializer.cs
│  │  │  │  │  │  │  │  │  │─DecimalSerializer.cs
│  │  │  │  │  │  │  │  │  │─DefaultValueDecorator.cs
│  │  │  │  │  │  │  │  │  │─DoubleSerializer.cs
│  │  │  │  │  │  │  │  │  │─EnumSerializer.cs
│  │  │  │  │  │  │  │  │  │─FieldDecorator.cs
│  │  │  │  │  │  │  │  │  │─GuidSerializer.cs
│  │  │  │  │  │  │  │  │  │─Int16Serializer.cs
│  │  │  │  │  │  │  │  │  │─Int32Serializer.cs
│  │  │  │  │  │  │  │  │  │─Int64Serializer.cs
│  │  │  │  │  │  │  │  │  │─IProtoSerializer.cs
│  │  │  │  │  │  │  │  │  │─IProtoTypeSerializer.cs
│  │  │  │  │  │  │  │  │  │─ISerializerProxy.cs
│  │  │  │  │  │  │  │  │  │─KeyValuePairDecorator.cs
│  │  │  │  │  │  │  │  │  │─ListDecorator.cs
│  │  │  │  │  │  │  │  │  │─MemberSpecifiedDecorator.cs
│  │  │  │  │  │  │  │  │  │─NetObjectSerializer.cs
│  │  │  │  │  │  │  │  │  │─NullDecorator.cs
│  │  │  │  │  │  │  │  │  │─ParseableSerializer.cs
│  │  │  │  │  │  │  │  │  │─PropertyDecorator.cs
│  │  │  │  │  │  │  │  │  │─ProtoDecoratorBase.cs
│  │  │  │  │  │  │  │  │  │─SByteSerializer.cs
│  │  │  │  │  │  │  │  │  │─SingleSerializer.cs
│  │  │  │  │  │  │  │  │  │─StringSerializer.cs
│  │  │  │  │  │  │  │  │  │─SubItemSerializer.cs
│  │  │  │  │  │  │  │  │  │─SurrogateSerializer.cs
│  │  │  │  │  │  │  │  │  │─SystemTypeSerializer.cs
│  │  │  │  │  │  │  │  │  │─TagDecorator.cs
│  │  │  │  │  │  │  │  │  │─TimeSpanSerializer.cs
│  │  │  │  │  │  │  │  │  │─TupleSerializer.cs
│  │  │  │  │  │  │  │  │  │─TypeSerializer.cs
│  │  │  │  │  │  │  │  │  │─UInt16Serializer.cs
│  │  │  │  │  │  │  │  │  │─UInt32Serializer.cs
│  │  │  │  │  │  │  │  │  │─UInt64Serializer.cs
│  │  │  │  │  │  │  │  │  │─UriDecorator.cs
│  │  │  │  │  │  │  │  │─ServiceModel\
│  │  │  │  │  │  │  │  │  │─ProtoBehaviorAttribute.cs
│  │  │  │  │  │  │  │  │  │─ProtoBehaviorExtensionElement.cs
│  │  │  │  │  │  │  │  │  │─ProtoEndpointBehavior.cs
│  │  │  │  │  │  │  │  │  │─ProtoOperationBehavior.cs
│  │  │  │  │  │  │  │  │  │─XmlProtoSerializer.cs
│  │  │  │  │  │  │  │  │─SubItemToken.cs
│  │  │  │  │  │  │  │  │─WireType.cs
│  │  │  │  │  │  │  │─ProtocalData\
│  │  │  │  │  │  │  │  │─protocal_loginserver.cs
│  │  │  │  │  │  │  │─ProtocalDefinition.cs
│  │  │  │  │  │  │  │─SocketManager.cs
│  │  │  │  │  │─Singleton.cs
│  │  │  │  │  │─SocketTest.unity
│  │  │  │  │─ProjectSettings\
│  │  │  │  │  │─AudioManager.asset
│  │  │  │  │  │─ClusterInputManager.asset
│  │  │  │  │  │─DynamicsManager.asset
│  │  │  │  │  │─EditorBuildSettings.asset
│  │  │  │  │  │─EditorSettings.asset
│  │  │  │  │  │─GraphicsSettings.asset
│  │  │  │  │  │─InputManager.asset
│  │  │  │  │  │─NavMeshAreas.asset
│  │  │  │  │  │─NetworkManager.asset
│  │  │  │  │  │─Physics2DSettings.asset
│  │  │  │  │  │─ProjectSettings.asset
│  │  │  │  │  │─ProjectVersion.txt
│  │  │  │  │  │─QualitySettings.asset
│  │  │  │  │  │─TagManager.asset
│  │  │  │  │  │─TimeManager.asset
│  │  │  │  │  │─UnityAdsSettings.asset
│  │  │  │  │  │─UnityConnectSettings.asset
│  │  │  │  │─说明文档.txt
│  │  │─SocketBase.cs
│  │  │─SocketManager.cs
│  │  │─UnityHttpRequest.cs
│  │  │─ZYSNetwork.cs
│  │─ObjectPoolSystem\
│  │  │─GameObjectPool.cs
│  │  │─ObjectPool.cs
│  │  │─ObjectPoolManager.cs
│  │─PlatFormSystem\
│  │  │─AndroidManager.cs
│  │  │─IPhoneManager.cs
│  │  │─PlatFormManager.cs
│  │─ResourceSystem\
│  │  │─AssetBundleLoader.cs
│  │  │─AssetBundleSystem\
│  │  │  │─AssetBundleInfo.cs
│  │  │  │─AssetBundleLoadOperation.cs
│  │  │  │─AssetBundleManager.cs
│  │  │  │─Utility.cs
│  │  │─AssetsData.cs
│  │  │─AssetsLoadType.cs
│  │  │─AssetsUnloadHandler.cs
│  │  │─IResourceLoader.cs
│  │  │─ResLoadLocation.cs
│  │  │─ResourceCacheLoader.cs
│  │  │─ResourceLoader.cs
│  │  │─ResourceManager.cs
│  │─SceneSystem\
│  │  │─SceneManager.cs
│  │─SettingSystem\
│  │  │─SettingManager.cs
│  │─ShaderSystem\
│  │  │─ShaderManager.cs
│  │─SoundSystem\
│  │  │─SoundManager.cs
│  │─StateSystem\
│  │  │─FSM\
│  │  │  │─Base\
│  │  │  │  │─BaseFSM.cs
│  │  │  │  │─BaseState.cs
│  │  │  │  │─FsmVariable.cs
│  │  │  │─FSM\
│  │  │  │  │─BattleFSM.cs
│  │  │  │  │─FreeBattleState\
│  │  │  │  │  │─FAttackState.cs
│  │  │  │  │  │─FDeathState.cs
│  │  │  │  │  │─FDispatchState.cs
│  │  │  │  │  │─FIdleState.cs
│  │  │  │  │  │─FSearchState.cs
│  │  │  │  │─FsmState.cs
│  │  │  │  │─GameFSM.cs
│  │  │  │  │─NpcFSM.cs
│  │  │  │  │─TestFSM.cs
│  │  │  │  │─TurnBaseState\
│  │  │  │  │  │─TAttackState.cs
│  │  │  │  │  │─TDeathState.cs
│  │  │  │  │  │─TDispatchState.cs
│  │  │  │  │  │─TIdleState.cs
│  │  │  │  │  │─TSearchState.cs
│  │  │  │─Interface\
│  │  │  │  │─IFSM.cs
│  │  │  │  │─IState.cs
│  │  │─FSM.cs
│  │  │─IState.cs
│  │─ThreadSystem\
│  │  │─Frankfort\
│  │  │  │─Threading\
│  │  │  │  │─Internal\
│  │  │  │  │  │─ASyncThreadWorkData.cs
│  │  │  │  │  │─DelayedQueueItem.cs
│  │  │  │  │  │─DispatchAction.cs
│  │  │  │  │  │─MainThreadDispatcher.cs
│  │  │  │  │  │─MainThreadDispatchHelper.cs
│  │  │  │  │  │─MainThreadWatchdog.cs
│  │  │  │  │  │─MultithreadedWorkloadHelper.cs
│  │  │  │  │  │─SingleThreadHelper.cs
│  │  │  │  │  │─SingleThreadStarter.cs
│  │  │  │  │  │─ThreadDispatchAction.cs
│  │  │  │  │  │─ThreadWaitForNextFrame.cs
│  │  │  │  │  │─ThreadWaitForSeconds.cs
│  │  │  │  │  │─ThreadWorkDistribution.cs
│  │  │  │  │  │─ThreadWorkDistributionSession.cs
│  │  │  │  │  │─ThreadWorkloadExecutor.cs
│  │  │  │  │  │─ThreadWorkloadExecutorArg.cs
│  │  │  │  │  │─ThreadWorkloadExecutorArgIndexed.cs
│  │  │  │  │  │─ThreadWorkloadExecutorIndexed.cs
│  │  │  │  │  │─ThreadWorkStatePackage.cs
│  │  │  │  │  │─UnityActivityWatchdog.cs
│  │  │  │  │─IThreadWorkerObject.cs
│  │  │  │  │─MultithreadedWorkloadComplete.cs
│  │  │  │  │─MultithreadedWorkloadPackageComplete.cs
│  │  │  │  │─ThreadDispatchDelegate.cs
│  │  │  │  │─ThreadDispatchDelegateArg.cs
│  │  │  │  │─ThreadDispatchDelegateArgReturn.cs
│  │  │  │  │─ThreadDispatchDelegateReturn.cs
│  │  │  │  │─ThreadedWorkCompleteEvent.cs
│  │  │  │  │─ThreadPoolScheduler.cs
│  │  │  │  │─ThreadPoolSchedulerEvent.cs
│  │  │─Loom.cs
│  │  │─LoomManager.cs
│  │─TimerSystem\
│  │  │─Timer.cs
│  │  │─TimerEvent.cs
│  │  │─TimerManager.cs
│  │─tree.py
│  │─UI\
│  │  │─Components\
│  │  │  │─DragAcceptor\
│  │  │  │  │─DragAcceptor.cs
│  │  │  │─DragUI\
│  │  │  │  │─DragUIInput.cs
│  │  │  │─EmptyUI\
│  │  │  │  │─Empty4Raycast.cs
│  │  │  │─GuideHeightLightComponent.cs
│  │  │  │─IlifeCycleComponent.cs
│  │  │  │─ImageLoadComponent.cs
│  │  │  │─JoyStick\
│  │  │  │  │─UGUIJoyStick.cs
│  │  │  │  │─UGUIJoyStickBase.cs
│  │  │  │  │─UGUIJoyStick_BgMove.cs
│  │  │  │  │─UGUIJoyStick_hide.cs
│  │  │  │  │─UGUIJoyStick_Ro.cs
│  │  │  │─LanguageComponent\
│  │  │  │  │─FontChooserComponent.cs
│  │  │  │  │─LanguageComponent.cs
│  │  │  │─LongPressAcceptor\
│  │  │  │  │─LongPressAcceptor.cs
│  │  │  │─MouseDownUp\
│  │  │  │  │─MouseDownUp.cs
│  │  │  │─ReusingScrollRect\
│  │  │  │  │─ReusingScrollItemBase.cs
│  │  │  │  │─ReusingScrollItemData.cs
│  │  │  │  │─ReusingScrollRect.cs
│  │  │  │  │─ScrollRectInput.cs
│  │  │  │─TextTool\
│  │  │  │  │─CurvedText.cs
│  │  │  │  │─MaskWord.cs
│  │  │  │  │─RandomString.cs
│  │  │─Control\
│  │  │  │─UIAnimManager.cs
│  │  │  │─UILayerManager.cs
│  │  │  │─UIManager.cs
│  │  │  │─UIStackManager.cs
│  │  │  │─UISystemEvent.cs
│  │  │─Extensions\
│  │  │  │─Gradient.cs
│  │  │  │─HoleImage.cs
│  │  │  │─TextPro.cs
│  │  │  │─TextVirtical.cs
│  │  │─Model\
│  │  │  │─UIBase.cs
│  │  │  │─UIStyleComponent.cs
│  │  │  │─UIWindowBase.cs
│  │  │─UITextStyleManager\
│  │  │  │─Editor\
│  │  │  │  │─UITextStyleComponentEditor.cs
│  │  │  │  │─UITextStyleManagerWindow.cs
│  │  │  │─UITextStyleComponent.cs
│  │  │  │─UITextStyleManager.cs
│  │  │─Utils\
│  │  │  │─LayerSort.cs
│  │  │  │─ModelRotate.cs
│  │  │  │─UIModelShowTool.cs
│  │─UISystem\
│  │  │─FontManager.cs
│  │  │─IUIWindow.cs
│  │  │─UIEnum.cs
│  │  │─UILive.cs
│  │  │─UIManager.cs
│  │  │─UIResourceDefine.cs
│  │─VersionSystem\
│  │  │─UpdateManager.cs
```