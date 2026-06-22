# Claude 安装说明

Claude 支持将一个包含 `SKILL.md` 的文件夹打包成 `.zip` 后上传为 Skill。

## 准备 Skill 文件夹

请准备如下目录结构：

```text
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
```

## 打包

将整个 `baiyueguang-learning/` 文件夹压缩为：

```text
baiyueguang-learning.zip
```

## 注意

压缩包内部必须包含文件夹本身，而不是直接把所有文件放在 ZIP 根目录。

正确结构：

```text
baiyueguang-learning.zip
└── baiyueguang-learning/
    ├── SKILL.md
    ├── ONTOLOGY.md
    ├── TRANSLATOR.md
    └── examples/
```

错误结构：

```text
baiyueguang-learning.zip
├── SKILL.md
├── ONTOLOGY.md
├── TRANSLATOR.md
└── examples/
```

## 上传到 Claude

1. 打开 Claude。
2. 进入 **Settings**。
3. 找到 **Features / Capabilities**。
4. 打开 **Skills**。
5. 点击 **Create Skill**。
6. 上传 `baiyueguang-learning.zip`。
7. 等待 Claude 完成导入。

## 使用

安装完成后，可以直接在对话中调用：

```text
使用白月光学习法解释线性无关。
```

```text
用白月光学习法讲解导数。
```

```text
按照白月光学习法分析概率问题。
```
