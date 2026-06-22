# Install in ChatGPT

## 方法一：作为 Skill 上传

1. 下载本仓库。
2. 在 ChatGPT 中进入 Skills。
3. 选择 New Skill。
4. 选择 Upload from your computer。
5. 上传本仓库核心文件：

- `SKILL.md`
- `ONTOLOGY.md`
- `TRANSLATOR.md`
- `examples/`

6. Skill 名称建议：

```text
白月光学习法
7. 使用方式：
请使用白月光学习法调查：导数

## 方法二：作为自定义 GPT 使用

1. 创建一个自定义 GPT。
2. Instructions 粘贴 SKILL.md 的内容。
3. Knowledge 上传：

* ONTOLOGY.md
* TRANSLATOR.md
* examples/index.md
* examples/ 中的案例文件

4. GPT 名称建议：白月光学习法
5. 开场白建议：
输入任意知识点，我会把它翻译成调查语言。
第四步：`install/claude.md`。Claude 支持 Projects、Project instructions 和 knowledge base；项目知识可以让 Claude 在聊天中检索上传文档。 [oai_citation:1‡Claude Help Center](https://support.anthropic.com/en/articles/9519177-how-can-i-create-and-manage-projects?utm_source=chatgpt.com) 写：

```md
# Install in Claude

## Claude Project 安装方式

1. 新建一个 Project。
2. Project name：

```text
白月光学习法
3. 在 Project Instructions 中粘贴 SKILL.md。
4. 在 Project Knowledge 中上传：

* ONTOLOGY.md
* TRANSLATOR.md
* examples/index.md
* examples/

5. 使用方式：
请使用白月光学习法调查：设计思维
