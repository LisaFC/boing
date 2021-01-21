
---
title: "Examples"
linkTitle: "Examples"
weight: 3
date: 2017-01-05
description: >
  See your project in action!
---

{{% pageinfo %}}
This is a placeholder page that shows you how to use this template site.
{{% /pageinfo %}}

Do you have any example **applications** or **code** for your users in your repo or elsewhere? Link to your examples here.

I'm going to write some text with `code in it`.

Here's a user's code:

`\([^,]*\), \(.*\)`

<mark>`\(`</mark>`[^,]*`<mark>`\)`</mark>`, \(.*\)` Pierwsza część pomiędzy `\( \)` dopasowuje „Ostatnie”\
`\(`<mark>`[^,]`</mark>`*\), \(.*\)` dopasuj wszystko z wyjątkiem przecinka\
`\([^,]`<mark>`*`</mark>`\), \(.*\)` dowolną ilość razy\
`\([^,]*\)`<mark>`, `</mark>`\(.*\)` dopasowuje dosłownie `, `\
`\([^,]*\), `<mark>`\(`</mark>`.*`<mark>`\)`</mark> Druga część między `\( \)` dopasowuje "Pierwsze"\
`\([^,]*\), \(`<mark>`.`</mark>`*\)` dowolny znak\
`\([^,]*\), \(.`<mark>`*`</mark>`\)` dowolną ilość razy

Here is an alert:

{{< alert title="\<cool\>" color="info" >}}
Alert alert alert
{{< /alert >}}
