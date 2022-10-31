```go
package main

import "fmt"

type Profile struct {
        Name    string
        From    string
        Company string
}

func main() {
        me := &Profile{
                Name:    "Artur Shaidullin",
                From:    "Kazan, Russia",
                Company: "Avito",
        }

        fmt.Printf(`Hi there! 👋
About me:
- name: %s
- from: %s
- company: %s`, me.Name, me.From, me.Company)
}
```
