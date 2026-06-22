Install in Claude

Claude Skills 安装方式

Claude 支持将一个包含 SKILL.md 的文件夹打包成 .zip 后上传为 Skill。

准备 Skill 文件夹

请准备以下结构：

baiyueguang-learning/
├── SKILL.md
├── ONTOLOGY.md
├── TRANSLATOR.md
└── examples/
    ├── index.md
    ├── 线性无关.md
    ├── 导数.md
    ├── 概率.md
    ├── 递归.md
    ├── 设计思维.md
    ├── 市场营销.md
    ├── 摄影曝光.md
    ├── 红楼梦.md
    └── 法国大革命.md

打包

将整个 baiyueguang-learning/ 文件夹压缩为：

baiyueguang-learning.zip

注意：

压缩包内部必须包含文件夹本身，而不是直接把所有文件散在 zip 根目录。

正确结构：

baiyueguang-learning.zip
└── baiyueguang-learning/
    ├── SKILL.md
    ├── ONTOLOGY.md
    ├── TRANSLATOR.md
    └── examples/

上传到 Claude

1. 打开 Claude。
2. 进入 Settings。
3. 找到 Features / Capabilities。
4. 打开 Skills。
5. 选择 Upload Skill。
6. 上传 baiyueguang-learning.zip。
7. 启用该 Skill。

使用方式

在 Claude 中输入：

请使用白月光学习法调查：设计思维

或：

请用 Baiyueguang Learning Skill 分析：概率论

Claude 应该输出：

* 账号
* 信息源
* 关注列表
* 点赞记录
* 收藏夹
* 历史记录
* 共同好友
* 时间线
* 关系网
* 重复信息
* 新线索
* 下一条线索

Skill 名称建议

白月光学习法

或：

Baiyueguang Learning Skill
