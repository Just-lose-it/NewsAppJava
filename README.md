# NewsAppJava
清华大学小学期程序设计训练作业

## 计划

### Day 1

- [x] 创建 Android Studio Java 项目
- [x] 引入 Retrofit、Gson、Glide、ExoPlayer、Room 依赖
- [x] 设计 News 数据类（Java Bean）
- [x] 创建 Retrofit 接口类（NewsApiService）
- [ ] 创建 Repository 类统一处理网络请求
- [ ] 创建主页面（MainActivity）和 XML 布局（RecyclerView + SwipeRefreshLayout）
- [ ] 实现新闻列表适配器（NewsAdapter）
- [ ] 下拉刷新：绑定 SwipeRefreshLayout
- [ ] 上拉加载：RecyclerView 滚动监听 + 分页逻辑
- [ ] 点击列表项跳转到详情页，传递新闻ID

### Day2
- [ ] 搜索界面（SearchView + Spinner 分类 + 日期选择器）
- [ ] 修改新闻请求接口，支持搜索参数（关键词、分类、时间）
- [ ] 显示所有分类
- [ ] 可添加/删除分类（持久化到 SharedPreferences）
- [ ] 支持“全部”分类切换（相当于不传 category 参数）
- [ ] 展示标题、来源、时间、内容
- [ ] 视频播放（ExoPlayer）
- [ ] 请求 GLM 模型接口获取摘要（假设你有接口，或先用mock数据）
- [ ] 将摘要缓存至本地（文件或Room）

### Day3
- [ ] 定义 Room 实体类：HistoryEntry、FavoriteEntry
- [ ] 每次进入详情页自动添加历史记录
- [ ] 收藏按钮点击添加至收藏表
- [ ] 历史记录/收藏记录页面（2个 Activity 或 Tab 切换）
- [ ] 离线缓存新闻内容（保存 JSON/文本到本地）
- [ ] 离线状态读取 Room 和文件缓存内容
- [ ] 网络异常处理（如 Toast 提示、无网络占位图）
- [ ] 性能测试（滑动流畅度、加载速度）
- [ ] 崩溃测试（异常捕获、空数据处理）
