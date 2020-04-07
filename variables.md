# Variables

- Variables are immutable by default
- `let` keyword declares a variable 

```rust
let height = 30;
```

- A variable can be made mutable by adding `mut` keyword 

```rust
let mut height = 30;
```

- Constants are declared with `const`
 
```rust
const MAX_COUNT: u32 = 10;
```

- Constants can be declared in any scrope, including global
- Must annotate the type
- Value cannot be assigned at runtime, eg: values returned from functions

- Shadowing

```rust
let height = 20; //20
let height = height + 30; //50
let height = height * 2; //100
```

- A new variable is created when 'let' is used each time, unlike mut

