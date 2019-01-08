#外部sig配置程序，本地存储自动配置，管理，清除PV。
#daemonset 每节点自动检测指定node下的目录文件，当本地出现新目录并且挂载到本地系统中，会自动新建pv。
#本地pod只需要引用storageclass 即可
#前提使用helm 本地渲染出部署文件，修改自定义本地目录路径。新建storageclass与pod 内部使用时候对应。
