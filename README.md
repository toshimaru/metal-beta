# Metal

Programming language Metal, just a idea, no imprementation.

Inspired by Ruby, Python, CoffeeScript.

Variable
-----

```
a = 1
b = 3
c = a + b
```

Comment out
-----

```
# this is one-line comment
```

Array
-----

```
ary = ['a', 1, 'bcd', 234]
```

Hash
-----

```
hash = {foo: 'bar', nyan: 'cat'}
```

Block expression
-----

Use `{}`(curly brace).

```
if true {
  p 'true'
}
```

Print
----

```
print 1 # => 1
puts 1 # => 1 (one line)
```

Function
-----

```
square = (a, b) -> {
  return a * b
}
```

Class
-----

```
class Foo {
  square (a) -> {
    "public method"
  }

  __private -> {
    'private method'
  }

  _protected_method -> {
    'protected method'
  }
}
```

Inheritance
-----

```
Class Foo < Bar {
}
```

Require
-----

```
require 'hoge'
```

Include
-----

```
Class Foo {
  include emullable
}
```

Condition
-----

```
if a == true {
  # true
} elif a == 2 {
  # else if
} else {
  # otherwise
}

b = 1 if a == true
```

Other Ideas
---
* [Toml](https://github.com/toml-lang/toml) configuration
