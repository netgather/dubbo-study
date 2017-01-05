#API配置参考手册
* Dubbo中除这里声明以外的接口或类，都是内部接口或扩展接口，普通用户请不要直接依赖，否则升级版本可能出现不兼容
##用于配置的API
使用方法可以参考：配置->API配置
* com.alibaba.dubbo.config.ServiceConfig
* com.alibaba.dubbo.config.ReferenceConfig
* com.alibaba.dubbo.config.ProtocolConfig
* com.alibaba.dubbo.config.RegistryConfig
* com.alibaba.dubbo.config.MonitorConfig
* com.alibaba.dubbo.config.ApplicationConfig
* com.alibaba.dubbo.config.ModuleConfig
* com.alibaba.dubbo.config.ProviderConfig
* com.alibaba.dubbo.config.ConsumerConfig
* com.alibaba.dubbo.config.MethodConfig
* com.alibaba.dubbo.config.ArgumentConfig

##用于注解的API
使用方法可以参考 ： 配置->注解配置
* com.alibaba.dubbo.config.annotation.Service
* com.alibaba.dubbo.config.annotation.Reference

##用于模型的API

* com.alibaba.dubbo.common.URL
* com.alibaba.dubbo.rpc.RpcException

##用于上下文的API

* com.alibaba.dubbo.rpc.RpcContext

##用于服务的API

* com.alibaba.dubbo.rpc.service.GenericService
* com.alibaba.dubbo.rpc.service.GenericException
* com.alibaba.dubbo.rpc.service.EchoService