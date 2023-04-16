---
Teamcore: Flujo de ramas
---
```mermaid
gitGraph:
options
{
    "nodeSpacing": 0,
    "nodeRadius": 0
}
end
   commit
   branch dev
   branch feat
   checkout feat
   commit
   commit
   checkout dev
   merge feat
   checkout main
   merge dev
   
````
