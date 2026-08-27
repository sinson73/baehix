最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计 http3 quic 简单原理了解
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://book.xmbldh.asia/blog/4225055.sHtMl

原标题：大事务拆分防止连接池耗尽
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://book.xmbldh.asia/blog/2377295.sHtMl

原标题：日志敏感信息脱敏泄露防护
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://book.xmbldh.asia/blog/9325238.sHtMl

原标题：golang 系统设计线上故障排查完整流程
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://book.xmbldh.asia/blog/6372149.sHtMl

原标题：新手向：看懂项目README的正确阅读姿势
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://book.xmbldh.asia/blog/9945753.sHtMl

原标题：实战项目：搭建本地Mock服务快速开发联调
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://book.xmbldh.asia/blog/5967245.sHtMl

原标题：浏览器本地存储安全使用技巧
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://book.xmbldh.asia/blog/5582487.sHtMl

原标题：golang mongodb 分页性能优化技巧
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://book.xmbldh.asia/blog/0663689.sHtMl

原标题：golang 系统设计压测数据构造方法实现
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：http://book.xmbldh.asia/blog/0838109.sHtMl

原标题：性能笔记：TCP参数内核调优服务高并发场景
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://book.xmbldh.asia/blog/8706032.sHtMl

原标题：golang 系统设计重试退避策略业务落地
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://book.xmbldh.asia/blog/1211444.sHtMl

原标题：实战项目：实现简单缓存服务缓存穿透击穿防护
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://book.xmbldh.asia/blog/4535499.sHtMl

原标题：项目实践：接口压测，逐步加压观察系统表现
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://book.xmbldh.asia/blog/6079044.sHtMl

原标题：Practice：实现业务id生成不连续有序ID方案
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://book.xmbldh.asia/blog/7877916.sHtMl

原标题：记一次分库分表路由计算错误数据写入错误分片
简介：golang go 调用动态链接库 so 文件，go 加载 so 动态库调用函数，复用编译好的 C 动态库。
 | 原文链接：http://book.xmbldh.asia/blog/7502679.sHtMl

原标题：部署实践：数据库迁移脚本版本管理实践
简介：golang staticcheck 静态代码分析，staticcheck 深度静态检查，发现代码错误、性能问题、风格问题。
 | 原文链接：http://book.xmbldh.asia/blog/5796731.sHtMl

原标题：golang redis 连接池参数最佳值
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://book.xmbldh.asia/blog/5625495.sHtMl

原标题：安全复盘：业务数据脱敏防止泄露实践
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://book.xmbldh.asia/blog/5890278.sHtMl

原标题：Issue：WSL2内存持续暴涨不自动释放
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://book.xmbldh.asia/blog/7518532.sHtMl

原标题：避坑：请求未设置read超时无限挂起连接
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://book.xmbldh.asia/blog/5423728.sHtMl

原标题：golang 系统设计消息堆积排查扩容完整步骤
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://book.xmbldh.asia/blog/9023171.sHtMl

原标题：DevOps：多阶段构建Dockerfile最佳实践
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://book.xmbldh.asia/blog/1076052.sHtMl

原标题：开发复盘：大事务拆分优化业务性能实践
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://book.xmbldh.asia/blog/4575727.sHtMl

原标题：golang ci 流水线环境变量管理方案
简介：golang 内存 dump 线上堆快照采集，线上生成内存 dump 文件，线下分析，定位内存泄漏问题。
 | 原文链接：http://book.xmbldh.asia/blog/7578450.sHtMl

原标题：MySQL 慢查询索引优化实战
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://book.xmbldh.asia/blog/2102723.sHtMl

原标题：入门实践：实现简单文件读写功能
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://book.xmbldh.asia/blog/7908727.sHtMl

原标题：vue3 组合式 API 业务开发实战
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://book.xmbldh.asia/blog/7349421.sHtMl

原标题：新手参与开源社区贡献指南
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://book.xmbldh.asia/blog/6341359.sHtMl

原标题：调优方案：Nginx性能参数调优高并发配置
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://book.xmbldh.asia/blog/4463670.sHtMl

原标题：部署复盘：静态站点部署CDN完整流程
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://book.xmbldh.asia/blog/5686310.sHtMl

原标题：Troubleshooting：K8sPodOOMKilled完整排查流程
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://book.xmbldh.asia/blog/8429862.sHtMl

原标题：golang kafka 同步异步消费对比
简介：golang 分布式追踪全链路日志打印，日志打印 traceId，各个服务日志可串联，排查跨服务调用问题。
 | 原文链接：http://book.xmbldh.asia/blog/3733218.sHtMl

原标题：开发复盘：内存缓存LRU淘汰策略实现实践
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://book.xmbldh.asia/blog/5317974.sHtMl

原标题：nodejs 跨域中间件配置细节
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://book.xmbldh.asia/blog/3640787.sHtMl

原标题：开发记录：短信发送服务封装，失败重试策略
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://book.xmbldh.asia/blog/1637189.sHtMl

原标题：golang 项目 docker compose 本地调试
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://book.xmbldh.asia/blog/0100617.sHtMl

原标题：开发代理服务网络限制解决
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://book.xmbldh.asia/blog/6831255.sHtMl

原标题：踩坑记录：CPU亲和配置不合理多核心负载不均
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://book.xmbldh.asia/blog/4461865.sHtMl

原标题：Security：SSRF服务端请求伪造漏洞防御
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://book.xmbldh.asia/blog/2964248.sHtMl

原标题：golang 系统设计本地缓存过期淘汰策略选型
简介：消息队列生产消费模型入门，讲解消息队列生产、存储、消费流程，理解异步解耦、削峰，掌握消息队列基础概念。
 | 原文链接：http://book.xmbldh.asia/blog/3138089.sHtMl


二、踩坑排错｜Troubleshooting
原标题：跨库查询性能优化处理
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://book.xmbldh.asia/blog/8012541.sHtMl

原标题：golang 系统设计本地缓存更新失效方案实现
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://book.xmbldh.asia/blog/5856216.sHtMl

原标题：端口占用释放资源重启服务
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://book.xmbldh.asia/blog/2256281.sHtMl

原标题：不必要字符转义关闭业务异常
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://book.xmbldh.asia/blog/0289432.sHtMl

原标题：golang 内存缓存简单实现方案
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://book.xmbldh.asia/blog/0031221.sHtMl

原标题：避坑：文件锁处理不当多进程竞争死锁
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://book.xmbldh.asia/blog/9652649.sHtMl

原标题：golang etcd 分布式锁实现原理
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://book.xmbldh.asia/blog/2798221.sHtMl

原标题：golang 系统设计接口幂等架构设计
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://book.xmbldh.asia/blog/3450116.sHtMl

原标题：golang 灰度权重流量分发简单实现
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://book.xmbldh.asia/blog/5769215.sHtMl

原标题：golang kafka 批量发送消费优化
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://book.xmbldh.asia/blog/6011216.sHtMl

原标题：调优方案：前端静态资源打包性能体积优化
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://book.xmbldh.asia/blog/0580901.sHtMl

原标题：前端 pdf 预览渲染方案对比
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://book.xmbldh.asia/blog/3275343.sHtMl

原标题：golang 系统设计并发控制协程池任务池实现
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://book.xmbldh.asia/blog/3707613.sHtMl

原标题：实战：基于DockerCompose搭建本地开发栈
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://book.xmbldh.asia/blog/2721714.sHtMl

原标题：golang 集成测试启动测试数据库
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://book.xmbldh.asia/blog/8648793.sHtMl

原标题：golang 系统设计限流熔断降级组合使用
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://book.xmbldh.asia/blog/8275219.sHtMl

原标题：golang gitlab ci 配置自动构建镜像
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://book.xmbldh.asia/blog/4607354.sHtMl

原标题：golang 系统设计延迟消息实现几种方案对比
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://book.xmbldh.asia/blog/9319192.sHtMl

原标题：项目实践：多环境配置管理组件设计与实现
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://book.xmbldh.asia/blog/5256236.sHtMl

原标题：用户敏感数据脱敏代码实现
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://book.xmbldh.asia/blog/6475488.sHtMl

原标题：golang prometheus counter gauge 使用
简介：golang html 模板渲染简单示例，Go HTML 模板渲染，服务端渲染页面，填充数据输出 HTML 页面。
 | 原文链接：http://book.xmbldh.asia/blog/8035472.sHtMl

原标题：架构复盘：数据库主从架构设计与延迟应对方案
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://book.xmbldh.asia/blog/6958524.sHtMl

原标题：OAuth2 第三方登录服务搭建
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://book.xmbldh.asia/blog/9124168.sHtMl

原标题：Issue：Docker网络模式选择错误容器互通失败
简介：golang go mod replace 本地模块替换，replace 替换模块为本地目录，修改第三方库本地调试。
 | 原文链接：http://book.xmbldh.asia/blog/0236700.sHtMl

原标题：浮点计算精度错误处理方案
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://book.xmbldh.asia/blog/0454990.sHtMl

原标题：Git 误删提交代码恢复找回
简介：看懂报错日志快速定位问题，讲解日志阅读方法，解析堆栈信息含义，学会从报错信息中定位代码出错位置。
 | 原文链接：http://book.xmbldh.asia/blog/4184897.sHtMl

原标题：部署复盘：蓝绿发布实现零停机业务更新
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://book.xmbldh.asia/blog/2971537.sHtMl

原标题：开发复盘：百万数据批量导入数据库优化方案
简介：多版本开发环境共存配置，实现同一工具多版本并存，快速切换不同版本，适配不同项目对版本的差异化需求。
 | 原文链接：http://book.xmbldh.asia/blog/1831274.sHtMl

原标题：golang 系统设计高可用服务架构梳理
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://book.xmbldh.asia/blog/4698788.sHtMl

原标题：golang 系统设计自动化测试 ci 流水线集成实操
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://book.xmbldh.asia/blog/3933753.sHtMl

原标题：golang consul 服务发现简单示例
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://book.xmbldh.asia/blog/2661068.sHtMl

原标题：架构笔记：数据库连接池架构参数调优思路
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://book.xmbldh.asia/blog/2370014.sHtMl

原标题：golang 系统设计自动化测试 ci 流水线集成实操
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://book.xmbldh.asia/blog/8239320.sHtMl

原标题：项目实践：实现统一接口返回封装与全局异常处理
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://book.xmbldh.asia/blog/6061976.sHtMl

原标题：安全实践：生产环境禁止开启debug调试模式
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://book.xmbldh.asia/blog/0057735.sHtMl

原标题：golang minio 预签名 url 临时访问
简介：git rebase 整理提交历史实操，使用 rebase 整理杂乱提交记录，将多条提交合并，保持 git 提交历史干净线性。
 | 原文链接：http://book.xmbldh.asia/blog/4928834.sHtMl

原标题：golang 简易埋点日志上报实现
简介：CI 持续集成自动构建流程，讲解 CI 基础概念，配置流水线实现代码提交后自动构建、测试，提升交付自动化。
 | 原文链接：http://book.xmbldh.asia/blog/6911531.sHtMl

原标题：新手教程：gitrebase基础使用与风险提示
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://book.xmbldh.asia/blog/1948732.sHtMl

原标题：golang defer panic 异常处理
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://book.xmbldh.asia/blog/8049200.sHtMl

原标题：Redis 内存淘汰策略数据防丢失
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://book.xmbldh.asia/blog/2641530.sHtMl

三、实战开发｜Practice
原标题：Issue：防火墙拦截ICMP，MTU问题网络丢包
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://book.xmbldh.asia/blog/7090575.sHtMl

原标题：golang 系统设计 mq 消息积压解决方案
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://book.xmbldh.asia/blog/3477938.sHtMl

原标题：golang 系统设计消息队列解耦削峰
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://book.xmbldh.asia/blog/7039225.sHtMl

原标题：从零搭建简单CLI命令行工具
简介：golang 分布式唯一 id 多种方案对比，雪花、redis、uuid 对比各方案优缺点，指导业务选型使用。
 | 原文链接：http://book.xmbldh.asia/blog/2410223.sHtMl

原标题：Issue：日志疯狂打日志快速占满磁盘空间
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://book.xmbldh.asia/blog/5680489.sHtMl

原标题：灰度发布策略服务平滑升级
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://book.xmbldh.asia/blog/0870167.sHtMl

原标题：调优方案：Nginx性能参数调优高并发配置
简介：golang 内存 dump 线上堆快照采集，线上生成内存 dump 文件，线下分析，定位内存泄漏问题。
 | 原文链接：http://book.xmbldh.asia/blog/3028515.sHtMl

原标题：全局时间标准统一逻辑错乱修复
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://book.xmbldh.asia/blog/6881248.sHtMl

原标题：多套环境灵活切换配置方案
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://book.xmbldh.asia/blog/7877523.sHtMl

原标题：golang 系统设计 api 文档 swagger redoc 落地
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://book.xmbldh.asia/blog/4472126.sHtMl

原标题：部署实践：容器时区统一配置解决方案
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://book.xmbldh.asia/blog/3772027.sHtMl

原标题：复盘总结：技术选型对比文档模板实践
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：http://book.xmbldh.asia/blog/8050006.sHtMl

原标题：端口占用访问失败排查方案
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://book.xmbldh.asia/blog/9712755.sHtMl

原标题：排错：对象存储跨域配置不生效前端上传失败
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://book.xmbldh.asia/blog/9380712.sHtMl

原标题：架构笔记：高并发系统核心设计思路总结
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://book.xmbldh.asia/blog/3754099.sHtMl

原标题：排错：GitLFS大文件推送失败完整排障
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://book.xmbldh.asia/blog/7725553.sHtMl

原标题：调优方案：Docker容器内核参数性能调优
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://book.xmbldh.asia/blog/9468673.sHtMl

原标题：新手快速上手 Git 版本控制实操指南
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://book.xmbldh.asia/blog/9659441.sHtMl

原标题：golang 系统设计第三方 sdk 二次封装技巧
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://book.xmbldh.asia/blog/1175055.sHtMl

原标题：性能笔记：压测如何定位真实系统瓶颈
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://book.xmbldh.asia/blog/7269840.sHtMl

原标题：全局时间标准统一逻辑错乱修复
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://book.xmbldh.asia/blog/0771313.sHtMl

原标题：golang mysql 连接泄漏检测方法
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://book.xmbldh.asia/blog/8023969.sHtMl

原标题：性能复盘：内存泄漏定位，内存持续上涨优化
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://book.xmbldh.asia/blog/6936763.sHtMl

原标题：Spring 事务传播机制配置生效
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://book.xmbldh.asia/blog/1316776.sHtMl

原标题：golang 系统设计告警风暴抑制合并降噪方案
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://book.xmbldh.asia/blog/0645976.sHtMl

原标题：Practice：实现限流之后友好业务返回处理
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://book.xmbldh.asia/blog/9433003.sHtMl

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://book.xmbldh.asia/blog/9308579.sHtMl

原标题：rebase 操作防止代码丢失
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://book.xmbldh.asia/blog/6195193.sHtMl

原标题：golang mysql 事务回滚异常处理
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://book.xmbldh.asia/blog/5921698.sHtMl

原标题：golang 系统设计消息队列 topic 设计原则梳理
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://book.xmbldh.asia/blog/3416720.sHtMl

原标题：golang 系统设计故障止损降级回滚执行原则
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://book.xmbldh.asia/blog/9042074.sHtMl

原标题：gitignore 文件编写过滤规则
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：http://book.xmbldh.asia/blog/6578050.sHtMl

原标题：WSL 内存上限限制防止资源耗尽
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://book.xmbldh.asia/blog/2219192.sHtMl

原标题：golang 系统设计序列化性能选型对比
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://book.xmbldh.asia/blog/9614196.sHtMl

原标题：实践：前后端分离项目登录状态保持完整方案
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://book.xmbldh.asia/blog/3478978.sHtMl

原标题：坑点：缓存过期策略不当引发业务异常
简介：golang fasthttp 客户端连接池调优，fasthttp 客户端连接池配置，复用连接提升请求性能。
 | 原文链接：http://book.xmbldh.asia/blog/8550562.sHtMl

原标题：新手指南：本地多版本环境共存配置
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://book.xmbldh.asia/blog/5507412.sHtMl

原标题：golang 结构体深拷贝几种实现
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://book.xmbldh.asia/blog/5542018.sHtMl

原标题：golang 系统设计分布式锁可重入实现思路
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://book.xmbldh.asia/blog/1230814.sHtMl

原标题：golang 链路追踪简易实现方案
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://book.xmbldh.asia/blog/6683238.sHtMl

四、架构设计｜Architecture
原标题：golang websocket 服务端开发
简介：golang go 并发模式 or‑channel 信号合并，合并多个 done 信号，任意一个完成触发退出逻辑。
 | 原文链接：http://book.xmbldh.asia/blog/5943842.sHtMl

原标题：golang es 更新文档注意版本冲突
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://book.xmbldh.asia/blog/4689640.sHtMl

原标题：架构复盘：系统扩容缩容架构无状态优先原则
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://book.xmbldh.asia/blog/1047974.sHtMl

原标题：golang 系统设计第三方 sdk 二次封装技巧
简介：golang pdf 生成 go 服务端生成 pdf，服务端动态生成 pdf 报表文件，直接输出下载给到前端。
 | 原文链接：http://book.xmbldh.asia/blog/1102274.sHtMl

原标题：快速上手调试工具定位简单代码错误
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://book.xmbldh.asia/blog/7989268.sHtMl

原标题：避坑：定时任务重复执行带来业务脏数据
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://book.xmbldh.asia/blog/2437422.sHtMl

原标题：实战项目：编写Dockerfile多阶段构建减小镜像体积
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://book.xmbldh.asia/blog/8893625.sHtMl

原标题：golang 系统设计参数校验统一处理方案
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://book.xmbldh.asia/blog/8358394.sHtMl

原标题：golang 接口请求日志记录中间件
简介：golang nilnil interface 陷阱复现，interface 包含类型不为 nil 值为 nil，判 ==nil 返回 false 经典坑。
 | 原文链接：http://book.xmbldh.asia/blog/0044764.sHtMl

原标题：golang redis stream 消息队列实践
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://book.xmbldh.asia/blog/6732943.sHtMl

原标题：golang consul 服务发现简单示例
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://book.xmbldh.asia/blog/5518179.sHtMl

原标题：部署实践：多实例服务部署无状态改造
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://book.xmbldh.asia/blog/6546832.sHtMl

原标题：golang 系统设计用户签到统计方案
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://book.xmbldh.asia/blog/3037970.sHtMl

原标题：DevOps：CI构建产物缓存复用加速编译
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://book.xmbldh.asia/blog/3235185.sHtMl

原标题：golang jwt 过期刷新 token 实现
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://book.xmbldh.asia/blog/6492167.sHtMl

原标题：架构笔记：事件驱动架构适用场景与坑点
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://book.xmbldh.asia/blog/0492311.sHtMl

原标题：golang 空接口 interface 使用技巧
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://book.xmbldh.asia/blog/1089375.sHtMl

原标题：Git 混乱提交历史清理方法
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://book.xmbldh.asia/blog/5678423.sHtMl

?
