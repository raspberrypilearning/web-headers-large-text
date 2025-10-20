使用 `<h1>` 标签来表示此内容是页面上最大的标题。

下一个标题标签是 `<h2>`，用于较低级别的标题。

要添加段落文本，请使用 `<p>` 标签：

--- code ---
---
language: html
filename: index.html
line_numbers: false
line_number_start: 1
line_highlights: 2, 7
---
    <header class="border-bottom secondary">
      <h1>Lorem ipsum</h1> 
    </header>
  
    <main>
      <section>
      <h2>Lorem ipsum dolor.</h2>
      <p>Lorem ipsum dolor sit amet.</p>
      </section>
    </main>

--- /code ---

**提示**：初始项目在 `style.css` 文件中有自定义样式，用于设置 `<h1>` 、 `<h2>` 和 `<p>` 元素使用的字体，以便它们与项目字体调色板相匹配。

![占位符文本显示 <h1>、<h2> 和段落 HTML 元素，并应用了默认项目字体。](images/headers.png)

你还可以使用初始项目中包含的 `bigfont` 和 `hugefont` 自定义类。

--- code ---
---
language: html
filename: index.html
line_numbers: false
--- 
<p class="hugefont">Lorem</p>
<p class="bigfont">Lorem</p>

--- /code ---

![“Lorem ”一词以巨大的字体显示，然后在下面以大字体重复显示。 巨大字体比大字体要大很多。](images/size.png)
