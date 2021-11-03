
---
title: "Examples"
linkTitle: "Examples"
github_url: "https://my/lovely/url"
weight: 3
date: 2017-01-05
description: >
  See your project in action!
---

{{% pageinfo %}}
This is a placeholder page that shows you how to use this template site.
{{% /pageinfo %}}

Do you have any example **applications** or **code** for your users in your repo or elsewhere? Link to your examples here.

Here are some lovely icons:
  <i class="fas fa-handshake"></i> 
  <i class="fas fa-handshake-slash"></i> 
  
Here is an ould triangle:

{{< svg "triangle.svg" >}}
  
Here is a mindmap:

```markmap
# markmap

## Links

- <https://markmap.js.org/>
- [GitHub](https://github.com/gera2ld/markmap)

## Related

- [coc-markmap](https://github.com/gera2ld/coc-markmap)
- [gatsby-remark-markmap](https://github.com/gera2ld/gatsby-remark-markmap)

## Features

- links
- **inline** ~~text~~ *styles*
- multiline
  text
- `inline code`
- Katex - $x = {-b \pm \sqrt{b^2-4ac} \over 2a}$
```

Here is some code that should look the way I expect it to:

```go {.myclass data-line="2"}
func main() {
  input := `var foo = "bar";`

  lexer := lexers.Get("javascript")
  iterator, _ := lexer.Tokenise(nil, input)
  style := styles.Get("github")
  formatter := html.New(html.WithLineNumbers())

  var buff bytes.Buffer
  formatter.Format(&buff, style, iterator)

  fmt.Println(buff.String())
}
```
