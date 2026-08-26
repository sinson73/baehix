最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Hands‑on：手写简单消息队列理解存储模型
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://wiki.o78ojz.asia/arts/082590.Doc

原标题：性能复盘：磁盘Swap大量使用系统卡顿优化
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://wiki.o78ojz.asia/arts/160060.Doc

原标题：请求重试组件退避策略实现
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://wiki.o78ojz.asia/arts/542249.Doc

原标题：新手向：开源项目依赖安装失败排查
简介：golang 重试退避机制代码实现，Go 实现请求重试与指数退避，处理临时故障，提升调用稳定性。
 | 原文链接：http://wiki.o78ojz.asia/arts/716433.Doc

原标题：golang 系统设计日志规范结构化日志落地
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://wiki.o78ojz.asia/arts/114433.Doc

原标题：golang 系统设计 traceId 全链路透传完整方案
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://wiki.o78ojz.asia/arts/029174.Doc

原标题：golang 系统设计分布式锁看门狗续期原理理解
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://wiki.o78ojz.asia/arts/815434.Doc

原标题：golang 系统设计 rest 状态码合理使用指南
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://wiki.o78ojz.asia/arts/283446.Doc

原标题：Debug：异步任务堆积，服务响应越来越慢
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://wiki.o78ojz.asia/arts/340995.Doc

原标题：golang docker 网络模式桥接 host
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://wiki.o78ojz.asia/arts/221221.Doc

原标题：坑点：软链接权限问题容器读取文件失败
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://wiki.o78ojz.asia/arts/450511.Doc

原标题：安全实践：请求输入校验防御恶意参数
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://wiki.o78ojz.asia/arts/785306.Doc

原标题：Troubleshoot：DNS解析异常导致第三方调用失败
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://wiki.o78ojz.asia/arts/568504.Doc

原标题：golang 系统设计读写分离延迟业务兼容
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://wiki.o78ojz.asia/arts/020957.Doc

原标题：部署复盘：配置热更新不用重启服务方案
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://wiki.o78ojz.asia/arts/228370.Doc

原标题：性能笔记：操作系统文件句柄、虚拟内存调优
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://wiki.o78ojz.asia/arts/200298.Doc

原标题：性能笔记：连接池参数调优数据库RPC连接池
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://wiki.o78ojz.asia/arts/972105.Doc

原标题：优化实践：预加载与懒加载业务场景取舍
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://wiki.o78ojz.asia/arts/147448.Doc

原标题：golang 系统设计容量评估简单方法论
简介：golang 优雅停机服务关闭实现，监听系统信号，关闭服务等待请求处理完毕，实现 Go 服务优雅停机。
 | 原文链接：http://wiki.o78ojz.asia/arts/381527.Doc

原标题：golang 系统设计本地缓存与分布式缓存
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://wiki.o78ojz.asia/arts/851413.Doc

原标题：golang k8s 资源请求限制配置
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://wiki.o78ojz.asia/arts/992439.Doc

原标题：golang 系统设计指标埋点代码低侵入实现
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://wiki.o78ojz.asia/arts/770996.Doc

原标题：golang mongodb 索引优化查询速度
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://wiki.o78ojz.asia/arts/649077.Doc

原标题：安全复盘：业务数据脱敏防止泄露实践
简介：Nginx 反向代理路由配置实战，配置 Nginx 反向代理，实现请求转发、路由分发，掌握 Nginx 基础配置能力。
 | 原文链接：http://wiki.o78ojz.asia/arts/382036.Doc

原标题：golang 系统设计数据库查询优化完整流程
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://wiki.o78ojz.asia/arts/593103.Doc

原标题：项目实践：MySQL读写分离本地模拟实践
简介：golang go http 文件服务器自定义，http.FileServer 自定义 FileSystem，拦截访问，增加鉴权逻辑。
 | 原文链接：http://wiki.o78ojz.asia/arts/645643.Doc

原标题：golang channel 通道并发处理
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://wiki.o78ojz.asia/arts/203213.Doc

原标题：Git 误删提交代码恢复找回
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://wiki.o78ojz.asia/arts/085166.Doc

原标题：golang 系统设计消息可靠性投递实现
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://wiki.o78ojz.asia/arts/387992.Doc

原标题：实战：容器内执行调试排错完整实操流程
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://wiki.o78ojz.asia/arts/551775.Doc

原标题：实践：前后端时间格式统一规范落地实践
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://wiki.o78ojz.asia/arts/529192.Doc

原标题：快速入门：API接口调试完整实操步骤
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://wiki.o78ojz.asia/arts/315851.Doc

原标题：方案对比：定时任务框架选型与架构对比
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://wiki.o78ojz.asia/arts/858110.Doc

原标题：golang proto 默认值坑点梳理
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://wiki.o78ojz.asia/arts/128441.Doc

原标题：golang 系统设计滑动窗口限流代码示例
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://wiki.o78ojz.asia/arts/421540.Doc

原标题：时间精度统一业务判断修复
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://wiki.o78ojz.asia/arts/825836.Doc

原标题：线上故障：第三方接口超时未设置熔断雪崩
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://wiki.o78ojz.asia/arts/930429.Doc

原标题：架构笔记：事件驱动架构适用场景与坑点
简介：golang go 项目工程目录布局标准，不同规模 go 项目目录结构，小型项目中型项目大型微服务项目布局。
 | 原文链接：http://wiki.o78ojz.asia/arts/563236.Doc

原标题：项目构建脚本编译打包解析
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://wiki.o78ojz.asia/arts/781041.Doc

原标题：新手向：配置项目eslint/prettier代码格式化
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://wiki.o78ojz.asia/arts/935287.Doc


二、踩坑排错｜Troubleshooting
原标题：日志切割配置防止日志丢失
简介：golang go 随机数安全与非安全，math/rand 伪随机与 crypto/rand 密码学安全随机，区分业务场景。
 | 原文链接：http://wiki.o78ojz.asia/arts/601037.Doc

原标题：实践：多配置文件合并加载组件实现
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://wiki.o78ojz.asia/arts/260816.Doc

原标题：实战项目：搭建本地Mock服务快速开发联调
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://wiki.o78ojz.asia/arts/962822.Doc

原标题：golang es 高亮搜索结果实现方案
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://wiki.o78ojz.asia/arts/233160.Doc

原标题：golang es 映射 mapping 设计避坑
简介：golang gorm ORM 数据库操作，GORM 实操数据库 CRUD，模型定义，关联查询，简化 Go 数据库开发。
 | 原文链接：http://wiki.o78ojz.asia/arts/931988.Doc

原标题：golang 系统设计技术方案文档模板参考
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://wiki.o78ojz.asia/arts/822728.Doc

原标题：实战：容器内执行调试排错完整实操流程
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://wiki.o78ojz.asia/arts/972333.Doc

原标题：坑点：软链接权限问题容器读取文件失败
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://wiki.o78ojz.asia/arts/829437.Doc

原标题：内网测试服务搭建团队调试
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://wiki.o78ojz.asia/arts/270352.Doc

原标题：golang github actions 多平台构建
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://wiki.o78ojz.asia/arts/342184.Doc

原标题：开发复盘：超时参数统一治理线上服务实践
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://wiki.o78ojz.asia/arts/203233.Doc

原标题：golang redis lua 脚本开发调试
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://wiki.o78ojz.asia/arts/137951.Doc

原标题：Redis 分布式锁高并发安全实现
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://wiki.o78ojz.asia/arts/278225.Doc

原标题：实战项目：WSL开发环境完整配置实操
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://wiki.o78ojz.asia/arts/312929.Doc

原标题：安全实践：敏感信息加密存储传输完整方案
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://wiki.o78ojz.asia/arts/607704.Doc

原标题：Practice：模拟热点key，验证缓存防护策略
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://wiki.o78ojz.asia/arts/781596.Doc

原标题：实践：接口参数自动校验业务落地实践
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://wiki.o78ojz.asia/arts/641464.Doc

原标题：HelloCI：理解持续集成基础工作流程
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://wiki.o78ojz.asia/arts/119435.Doc

原标题：Cookie 跨环境登录配置调整
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://wiki.o78ojz.asia/arts/726511.Doc

原标题：Architecture：静态配置与动态配置架构分离
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://wiki.o78ojz.asia/arts/866189.Doc

原标题：避坑：文件锁处理不当多进程竞争死锁
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://wiki.o78ojz.asia/arts/768579.Doc

原标题：实践：大文件分片上传后端完整实现思路
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://wiki.o78ojz.asia/arts/558582.Doc

原标题：架构笔记：批量任务系统架构防重复、断点续跑
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://wiki.o78ojz.asia/arts/610463.Doc

原标题：实践：API接口文档自动导出离线文档实践
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://wiki.o78ojz.asia/arts/888650.Doc

原标题：方案对比：定时任务框架选型与架构对比
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.o78ojz.asia/arts/850713.Doc

原标题：坑点：依赖缓存未更新，旧代码持续运行
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://wiki.o78ojz.asia/arts/614836.Doc

原标题：golang 系统设计代码安全审计简单思路
简介：golang 容器健康检查接口开发，Go 开发 HTTP 健康接口，供容器编排工具探测实例存活状态。
 | 原文链接：http://wiki.o78ojz.asia/arts/428765.Doc

原标题：零基础理解依赖管理与包管理器
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://wiki.o78ojz.asia/arts/767015.Doc

原标题：golang jwt 过期刷新 token 实现
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://wiki.o78ojz.asia/arts/758167.Doc

原标题：golang 系统设计配置多环境隔离方案落地
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://wiki.o78ojz.asia/arts/700793.Doc

原标题：静态站点自动部署发布方案
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://wiki.o78ojz.asia/arts/711203.Doc

原标题：Architecture：API设计RESTful最佳实践与反模式
简介：文件批量导入导出功能实现，开发批量导入导出接口，处理大量文件数据，完成业务数据批量迁移与导出。
 | 原文链接：http://wiki.o78ojz.asia/arts/238140.Doc

原标题：灰度发布策略服务平滑升级
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://wiki.o78ojz.asia/arts/812211.Doc

原标题：限流规则误拦截正常请求修复
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://wiki.o78ojz.asia/arts/714635.Doc

原标题：安全实践：输入输出双向过滤安全最佳实践
简介：golang wasm webassembly go 编译，go 编译为 wasm，浏览器执行 go 代码，拓展 go 运行场景。
 | 原文链接：http://wiki.o78ojz.asia/arts/460663.Doc

原标题：项目实践：MySQL读写分离本地模拟实践
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://wiki.o78ojz.asia/arts/308329.Doc

原标题：架构笔记：高并发系统核心设计思路总结
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.o78ojz.asia/arts/937351.Doc

原标题：运维笔记：CI流水线缓存策略加速构建速度
简介：golang 结构体深浅拷贝区别实操，区分结构体浅拷贝深拷贝，规避指针引用带来数据意外篡改问题。
 | 原文链接：http://wiki.o78ojz.asia/arts/240367.Doc

原标题：运维笔记：系统内核参数调优生产服务器
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://wiki.o78ojz.asia/arts/711085.Doc

原标题：数据库主从延迟业务兼容处理
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://wiki.o78ojz.asia/arts/545252.Doc

三、实战开发｜Practice
原标题：golang 系统设计网关错误重试超时处理策略
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://wiki.o78ojz.asia/arts/459451.Doc

原标题：时间同步修复令牌提前过期
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://wiki.o78ojz.asia/arts/457058.Doc

原标题：5分钟快速搭建个人技术文档站点
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://wiki.o78ojz.asia/arts/339680.Doc

原标题：新手教程：如何给开源项目提交第一个PR
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://wiki.o78ojz.asia/arts/798311.Doc

原标题：GitHub 项目提交推送完整流程讲解
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://wiki.o78ojz.asia/arts/096689.Doc

原标题：安全实践：容器最小化镜像减少攻击面
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://wiki.o78ojz.asia/arts/481132.Doc

原标题：golang 系统设计容器镜像安全加固要点
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://wiki.o78ojz.asia/arts/648046.Doc

原标题：新手指南：看懂开源项目的Issue与PR
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://wiki.o78ojz.asia/arts/671063.Doc

原标题：hosts 配置本地回环访问修复
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://wiki.o78ojz.asia/arts/921407.Doc

原标题：跨库查询性能优化处理
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://wiki.o78ojz.asia/arts/679284.Doc

原标题：golang gorm 预加载关联查询优化
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://wiki.o78ojz.asia/arts/932019.Doc

原标题：项目实践：接口压测，逐步加压观察系统表现
简介：golang golangci‑lint 静态代码检查配置，golangci‑lint 静态检查，代码规范检测，提前发现代码隐患。
 | 原文链接：http://wiki.o78ojz.asia/arts/958358.Doc

原标题：golang 系统设计避免索引失效书写 sql 原则
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.o78ojz.asia/arts/855095.Doc

原标题：Hands‑on：手写简单消息队列理解存储模型
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://wiki.o78ojz.asia/arts/908133.Doc

原标题：golang 数据库批量更新性能优化
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://wiki.o78ojz.asia/arts/788708.Doc

原标题：golang gin 框架接口开发实战
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://wiki.o78ojz.asia/arts/332206.Doc

原标题：gitignore 文件编写过滤规则
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://wiki.o78ojz.asia/arts/607648.Doc

原标题：开发复盘：统一错误码体系设计落地实践
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.o78ojz.asia/arts/486151.Doc

原标题：golang gitlab ci 配置自动构建镜像
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://wiki.o78ojz.asia/arts/581199.Doc

原标题：golang 系统设计定时任务失败重试告警实现
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://wiki.o78ojz.asia/arts/819103.Doc

原标题：后端登录鉴权模块完整开发
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://wiki.o78ojz.asia/arts/147042.Doc

原标题：上传接口跨域配置特殊适配
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://wiki.o78ojz.asia/arts/481864.Doc

原标题：golang docker 镜像体积优化技巧
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://wiki.o78ojz.asia/arts/015582.Doc

原标题：Security：RPC调用身份认证安全加固
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://wiki.o78ojz.asia/arts/773726.Doc

原标题：坑点：npm/pip全局版本与项目本地版本冲突
简介：golang grafana 面板 go 业务指标可视化，prometheus 指标对接 grafana，配置监控面板可视化业务状态。
 | 原文链接：http://wiki.o78ojz.asia/arts/482077.Doc

原标题：方案对比：单体、微服务、模块化单体取舍
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://wiki.o78ojz.asia/arts/645404.Doc

原标题：golang docker 部署 es 本地开发
简介：golang fasthttp 客户端连接池调优，fasthttp 客户端连接池配置，复用连接提升请求性能。
 | 原文链接：http://wiki.o78ojz.asia/arts/851153.Doc

原标题：快速入门OpenAPI文档生成基础实践
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://wiki.o78ojz.asia/arts/414698.Doc

原标题：CLI 工具进度条交互效果开发
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://wiki.o78ojz.asia/arts/791585.Doc

原标题：数据库索引重建提升查询速度
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://wiki.o78ojz.asia/arts/500197.Doc

原标题：跨域偶现失败配置修复
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://wiki.o78ojz.asia/arts/202607.Doc

原标题：DevOps：GitLabCI完整流水线配置示例
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://wiki.o78ojz.asia/arts/308336.Doc

原标题：从零搭建本地开发环境完整教程
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://wiki.o78ojz.asia/arts/727615.Doc

原标题：编译打包产物依赖分析解读
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://wiki.o78ojz.asia/arts/816662.Doc

原标题：Issue：操作系统最大打开文件数限制导致报错
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://wiki.o78ojz.asia/arts/629077.Doc

原标题：图片上传预览格式大小处理
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://wiki.o78ojz.asia/arts/917365.Doc

原标题：Troubleshoot：MySQL字符集utf8非utf8mb4emoji报错
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://wiki.o78ojz.asia/arts/285629.Doc

原标题：新手教程：本地项目初始化gitignore配置
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://wiki.o78ojz.asia/arts/564572.Doc

原标题：golang consul 服务发现简单示例
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://wiki.o78ojz.asia/arts/302203.Doc

原标题：golang 系统设计分库分表中间件思路
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://wiki.o78ojz.asia/arts/576467.Doc

四、架构设计｜Architecture
原标题：DevOps：Docker镜像优化，减小镜像体积实践
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://wiki.o78ojz.asia/arts/644685.Doc

原标题：调优方案：服务实例扩容，水平扩展性能
简介：golang 自定义 http round tripper，封装 http 客户端拦截，实现请求日志、签名、重试统一处理逻辑。
 | 原文链接：http://wiki.o78ojz.asia/arts/857077.Doc

原标题：golang es bool 查询条件组合技巧
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://wiki.o78ojz.asia/arts/893705.Doc

原标题：实战项目：WebSocket消息广播房间分组实践
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://wiki.o78ojz.asia/arts/006959.Doc

原标题：nestjs 框架模块化项目搭建
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://wiki.o78ojz.asia/arts/641783.Doc

原标题：golang 系统设计事务消息 rocketmq 简单原理
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://wiki.o78ojz.asia/arts/941082.Doc

原标题：开发记录：文件锁实现多进程互斥实践
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://wiki.o78ojz.asia/arts/648502.Doc

原标题：golang docker 私有仓库搭建使用
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://wiki.o78ojz.asia/arts/146439.Doc

原标题：Troubleshooting：数据库索引失效，查询性能暴跌
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://wiki.o78ojz.asia/arts/891859.Doc

原标题：OpenSource：开源项目版本发布CHANGELOG编写
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://wiki.o78ojz.asia/arts/571383.Doc

原标题：线程池拒绝策略任务丢失防护
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://wiki.o78ojz.asia/arts/657429.Doc

原标题：短信服务封装失败自动重试
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://wiki.o78ojz.asia/arts/809623.Doc

原标题：包管理器依赖冲突解决方案
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://wiki.o78ojz.asia/arts/151590.Doc

原标题：golang redis lua 脚本开发调试
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://wiki.o78ojz.asia/arts/425286.Doc

原标题：设计思考：消息队列重复消费架构层防御手段
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://wiki.o78ojz.asia/arts/837489.Doc

原标题：golang redis 位图用户签到统计
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://wiki.o78ojz.asia/arts/299005.Doc

原标题：golang k8s 节点污点容忍度配置
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://wiki.o78ojz.asia/arts/318686.Doc

原标题：golang kafka 同步异步消费对比
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://wiki.o78ojz.asia/arts/667682.Doc

?
