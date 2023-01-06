下面是已经实现了的功能模块列表说明

| 编号 |     功能模块      |                               说明                               |  状态  |
| --- | ---------------- | ---------------------------------------------------------------- | ----- |
| 1.   | IP/IP列表资产发现 | 端口扫描，服务识别，SSL证书获取                                     | 已完成 |
| 2.   | 域名爆破          | 对给定的域名进行爆破，获取相关子域名                                 | 已完成 |
| 3.   | 字典智能生成      | 根据与有的域名生成字典再进行爆破                                    | 已完成 |
| 4.  | 资产分组管理和搜索 | 对资产进行分组，统一管理，可进行资产监控，资产添加等操作               | 已完成 |
| 5.   | 证书关联IP        | 对接fofa 通过证书关联IP                                           | 已完成 |
| 6.   | 站点识别          | 对目标站点进行指纹识别，输出如Nginx, IIS 等指纹信息                  | 已完成 |
| 7.   | 站点截图          | 对站点首页进行截图                                                 | 已完成 |
| 8.   | 自定义WEB指纹     | 根据保存的站点信息，添加相应的查询规则能快速赛选相关目标               | 已完成 |
| 9.   | 敏感文件泄漏      | 漏扫功能，对站点敏感文件进行扫描                                    | 已完成 |
| 10. | POC检测          | 漏扫功能， 已对接nuclei, 和对接NPoC                                | 已完成 |
| 11   | 搜索引擎爬虫      | 从搜索引擎获取站点URL                                              | 已完成 |
| 12   | 静态URL          | 从站点获取URL                                                     | 已完成 |
| 13   | 任务策略配置      | 可以新建资产发现策略，方便下一次使用同一个配置                        | 已完成 |
| 14   | 计划任务和周期任务 | 可以按照给定时间或者周期的执行任务                                  | 已完成 |
| 15   | Github 关键字监控 | 对Github 上的代码信息，根据关键字进行匹配和监控                      | 已完成 |
| 16   | 资产监控          | 对站点变化监控和域名/IP 资产新增监控                                | 已完成 |
| 17   | 域名查询插件      | 已支持的数据源为11个，alienvault, certspotter,crtsh,fofa,hunter 等 | 已完成 |