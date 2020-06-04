目的：完成一套完整的框架模板 
  eureka+config+bus+zuul+security+jwt+ouath2+feign+hystric+ribbon
使用高可用的eureka实现服务发现注册,eureka进行集群部署实现高可用，
  相对于zookeeper可用性较强，一个eureka服务挂掉后不影响服务注册发现，
  同时导致eureka不能保持高度一致性，有可能服务注册后不能被及时发现使用，
  zookeeper master节点挂掉后有30多秒的选举时间，大局有高度一致性。
使用config+bus实现配置管理，
  Springcloud后来推出的consul同时具有服务注册发现和配置中心的功能
使用zuul+security+jwt+ouath2实现权限认证，springcloud gateway可替代zuul
使用feign+hystric+ribbon完成服务请求及服务降级和负载均衡
  
