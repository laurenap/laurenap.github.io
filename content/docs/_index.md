---
title: projects
next: first-page
---

This is a demo of the theme's documentation layout.

{{< cards >}}
  {{< card link="/" title="Image Card" image="(https://images.app.goo.gl/Mj4fXZt4cHHWD2hS6) subtitle="Inside Lauren's Brain | Newsletter" >}}
  {{< card link="/" title="Local Image" image="/images/card-image-unprocessed.jpg" subtitle="Raw image under static directory." >}}
  {{< card link="/" title="Local Image" image="images/space.jpg" subtitle="Image under assets directory, processed by Hugo." method="Resize" options="600x q80 webp" >}}
{{< /cards >}}

## Hello, World!

```go {filename="main.go"}
package main

import "fmt"

func main() {
    fmt.Println("Hello, World!")
}
```
