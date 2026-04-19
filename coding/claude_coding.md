# Claude coding

* Creating a `CLAUDE.md` file allows the model to access your meta information in each prompt. You cat write universal instructions for all promts, for example: 

```CLAUDE.md
- never run "cargo run -q"
- never change port
```

> The model will read it for every instruction in CLAUDE file