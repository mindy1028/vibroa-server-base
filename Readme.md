| 集群名称       | 微服务名称            | 技术栈/组件                     | 服务说明         |
|--------------|------------------|--------------------------------|------------------|
| | TopGateWay       | SpringCloud, Zuul, Eureka | 顶级网关                       |
| TopGateWay   | WorkGateWay      | SpringCloud, Zuul, Eureka       | 日常办公用网关     |
| TopGateWay   | BussinessGateWay | SpringCloud, Zuul, Eureka       | 业务系统用网关     |
| TopGateWay   | OrderGateWay     | SpringCloud, Zuul, Eureka       | 订单系统用网关     |
| TopGateWay   | CommonGateWay    | SpringCloud, Zuul, Eureka       | 通用工具库网关     |
| WorkGateWay  | Auth             | SpringBoot                      | 用户认证服务       |
| WorkGateWay  | Admin            | SpringBoot                      | 管理员服务         |
| WorkGateWay  | Hrm              | SpringBoot                      | 人力资源管理系统服务 |
| WorkGateWay  | Crm              | SpringBoot                      | 客户管理系统服务   |
| WorkGateWay  | ERP              | SpringBoot                      | 工单管理系统服务   |
| WorkGateWay  | OA               | SpringBoot                      | 办公系统服务       |
| WorkGateWay  | IM               | SpringBoot                      | 即时通讯服务       |
| BussinessGateWay | Auth             | SpringBoot                      | 用户认证服务       |
| BussinessGateWay | T2V              | SpringBoot                      | 文生视频服务       |
| BussinessGateWay | T2V_Pro          | SpringBoot                      | 文生视频专业版服务  |
| BussinessGateWay | T2V_Sea          | SpringBoot                      | 文生视频海外版服务  |
| BussinessGateWay | I2V              | SpringBoot                      | 图生视频服务       |
| BussinessGateWay | I2V_Pro          | SpringBoot                      | 图生视频专业版服务  |
| BussinessGateWay | I2V_Sea          | SpringBoot                      | 图生视频海外版服务  |
| BussinessGateWay | VE               | SpringBoot                      | 视频编辑服务       |
| BussinessGateWay | VE_Pro           | SpringBoot                      | 视频编辑专业版服务  |
| BussinessGateWay | VE_Sea           | SpringBoot                      | 视频编辑海外版服务  |
| OrderGateWay  | Auth             | SpringBoot                      | 用户认证服务       |
| OrderGateWay  | Admin            | SpringBoot                      | 管理员服务         |
| OrderGateWay  | Accept           | SpringBoot                      | 下单服务           |
| OrderGateWay  | Management       | SpringBoot                      | 订单管理服务       |
| OrderGateWay  | Payment          | SpringBoot                      | 支付服务           |
| OrderGateWay  | Inventory        | SpringBoot                      | 库存服务           |
| OrderGateWay  | Notification     | SpringBoot                      | 通知服务           |
| OrderGateWay  | Delivery         | SpringBoot                      | 配送服务           |
| CommonGateWay | Message          | SpringBoot                      | 短信服务           |
| CommonGateWay | Email            | SpringBoot                      | 邮箱服务           |
