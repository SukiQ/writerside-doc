# 语法

<table>
  <thead>
    <tr>
      <th>标记</th>
      <th>Markdown</th>
      <th>XML</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>段落</td>
      <td>普通文本（换行空行分段）</td>
      <td>&lt;p&gt;段落内容&lt;/p&gt;</td>
    </tr>
    <tr>
      <td>标题</td>
      <td># 一级 到 ###### 六级</td>
      <td>&lt;h1&gt; 到 &lt;h6&gt;</td>
    </tr>
    <tr>
      <td>加粗</td>
      <td>**加粗**</td>
      <td>&lt;b&gt;加粗&lt;/b&gt;</td>
    </tr>
    <tr>
      <td>斜体</td>
      <td>*斜体* 或 _斜体_</td>
      <td>&lt;i&gt;斜体&lt;/i&gt;</td>
    </tr>
    <tr>
      <td>删除线</td>
      <td>~~删除线~~</td>
      <td>&lt;del&gt;删除线&lt;/del&gt;</td>
    </tr>
    <tr>
      <td>下标</td>
      <td>H~2~O</td>
      <td>&lt;sub&gt;2&lt;/sub&gt;</td>
    </tr>
    <tr>
      <td>上标</td>
      <td>X^2^</td>
      <td>&lt;sup&gt;2&lt;/sup&gt;</td>
    </tr>
    <tr>
      <td>换行</td>
      <td>末尾两个空格 + 回车</td>
      <td>&lt;br/&gt;</td>
    </tr>
    <tr>
      <td>分隔线</td>
      <td>---</td>
      <td>&lt;hr/&gt;</td>
    </tr>
    <tr>
      <td>无序列表</td>
      <td>- 项目 或 * 项目</td>
      <td>&lt;ul&gt;&lt;li&gt;项目&lt;/li&gt;&lt;/ul&gt;</td>
    </tr>
    <tr>
      <td>有序列表</td>
      <td>1. 项目</td>
      <td>&lt;ol&gt;&lt;li&gt;项目&lt;/li&gt;&lt;/ol&gt;</td>
    </tr>
    <tr>
      <td>表格</td>
      <td>| 表头 | 表头 |</td>
      <td>&lt;table&gt;...&lt;/table&gt;</td>
    </tr>
    <tr>
      <td>行内代码</td>
      <td>`代码`</td>
      <td>&lt;code&gt;代码&lt;/code&gt;</td>
    </tr>
    <tr>
      <td>代码块</td>
      <td>```java</td>
      <td>&lt;code-block lang="java"&gt;...&lt;/code-block&gt;</td>
    </tr>
    <tr>
      <td>分页</td>
      <td>无标准语法</td>
      <td>&lt;tabs&gt;&lt;tab name="..."&gt;...&lt;/tab&gt;&lt;/tabs&gt;</td>
    </tr>
    <tr>
      <td>步骤流程</td>
      <td>无</td>
      <td>&lt;procedure&gt;&lt;step&gt;...&lt;/step&gt;&lt;/procedure&gt;</td>
    </tr>
    <tr>
      <td>提示</td>
      <td>&gt; 提示内容</td>
      <td>&lt;tip&gt;提示内容&lt;/tip&gt;</td>
    </tr>
    <tr>
      <td>说明</td>
      <td>&gt; {style="note"} 内容</td>
      <td>&lt;note&gt;内容&lt;/note&gt;</td>
    </tr>
    <tr>
      <td>警告</td>
      <td>&gt; {style="warning"} 内容</td>
      <td>&lt;warning&gt;内容&lt;/warning&gt;</td>
    </tr>
    <tr>
      <td>链接</td>
      <td>[名称](url)</td>
      <td>&lt;a href="url"&gt;名称&lt;/a&gt;</td>
    </tr>
    <tr>
      <td>图片</td>
      <td>![alt](image.png)</td>
      <td>&lt;image src="image.png"/&gt;</td>
    </tr>
    <tr>
      <td>视频</td>
      <td>无</td>
      <td>&lt;video src="video.mp4"/&gt;</td>
    </tr>
    <tr>
      <td>文件下载</td>
      <td>无</td>
      <td>&lt;download href="file.zip"/&gt;</td>
    </tr>
    <tr>
      <td>按钮控件</td>
      <td>无</td>
      <td>&lt;control&gt;按钮名&lt;/control&gt;</td>
    </tr>
    <tr>
      <td>快捷键</td>
      <td>无</td>
      <td>&lt;shortcut&gt;Ctrl+S&lt;/shortcut&gt;</td>
    </tr>
    <tr>
      <td>路径</td>
      <td>无</td>
      <td>&lt;path&gt;/usr/bin&lt;/path&gt;</td>
    </tr>
    <tr>
      <td>条件内容</td>
      <td>无</td>
      <td>&lt;if target="intellij"&gt;...&lt;/if&gt;</td>
    </tr>
    <tr>
      <td>变量占位</td>
      <td>无</td>
      <td>&lt;var name="product"/&gt;</td>
    </tr>
    <tr>
      <td>API 文档</td>
      <td>无</td>
      <td>&lt;api-doc file="api.yaml"/&gt;</td>
    </tr>
    <tr>
      <td>导航卡片</td>
      <td>无</td>
      <td>&lt;cards&gt;&lt;card title="..." href="..."/&gt;&lt;/cards&gt;</td>
    </tr>
  </tbody>
</table>

## 标题

```markdown
# 一级标题
## 二级标题
### 三级标题
```

## 无序列表

- 第一项
- 第二项
- 第三项

```markdown
- 第一项
- 第二项
- 第三项
```

## 有序列表

1. 第一项
2. 第二项 
3. 第三项

```markdown
1. 第一项
2. 第二项
3. 第三项
```

## 表格

| 第一列    | 第二列    | 第三列      |   
|--------|--------|----------|
| 1      | 2      | 3        |

```markdown
| 第一列    | 第二列    | 第三列      |   
|--------|--------|----------|
| 1      | 2      | 3        |
```

> 对于复杂表格，请使用 XML 表达式
{style="note"}

## 提示框

- 提示
> 这是一个提示

```markdown
> 这是一个提示
```

- 说明
> 这是一个说明
{style="note"}

```markdown
> 这是一个说明
{style="note"}
```

- 警告
> 这是一个警告
{style="warning"}

```markdown
> 这是一个警告
{style="warning"}
```

## 文件下载
这是一个可下载的文件： <resource src="算力运营门户需求文档.docx"/> 请点击下载.

```markdown
这是一个可下载的文件： <resource src="算力运营门户需求文档.docx"/> 请点击下载.
```

## 图片
![Alt Text](wall.png){ thumbnail="true" width="700" }

```markdown
![Alt Text](wall.png){ thumbnail="true" width="700" }
```

## 代码

<note>
   ```javascript
    async fetch() {
    if ( this.$store.getters['cluster/canList'](SERVICE) ) {
        this.allServices = await this.$store.dispatch('cluster/findAll');
    }
    if ( this.$store.getters['cluster/canList'](SCHEMA) ) {
        this.allSchemas = await this.$store.dispatch('cluster/findAll');
    }
}
```
</note>



```javascript
    async fetch() {
    if ( this.$store.getters['cluster/canList'](SERVICE) ) {
        this.allServices = await this.$store.dispatch('cluster/findAll');
    }
    if ( this.$store.getters['cluster/canList'](SCHEMA) ) {
        this.allSchemas = await this.$store.dispatch('cluster/findAll');
    }
}
```

