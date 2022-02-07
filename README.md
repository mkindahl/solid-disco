# solid-disco

Experimentation with cross-repository event dispatch.

This repository dispatch events to other repositories to trigger
actions.

We are experimenting with both `workflow_dispatch` and `repository_dispatch`.

```ebnf
Statement = ( NamedFunction | AnonymousFunction | Assignment | Expr ) , "\n" ;
Expr = AnonymousFunction | Term | "(" , Expr , ")" ,
    { AnonymousFunction | Term | "(" , Expr , ")" } ;
```
