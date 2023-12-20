# Operators

- So, they are used to perform _operations_ like **comparisons** and **arithmetic** calculations in the _SQL_.

1. **Arithmetic** :

- `+` : Addition
- `-` : Subtraction
- `*` : Multiplication
- `/` : Division
- `%` : Modulus

* Example ✅

```SQL
SELECT product, price, (price * 0.18) as tax
FROM products;
```

2. **Comparison** :

- `=`: Equal
- `!=` _OR_ `<>` : Not Equal
- `>` : Greater than
- `<` : Less than
- `>=` : Greater than or Equal
- `<=` : Less than or Equal

* Example ✅

```SQL
SELECT name, age FROM students WHERE age > 18;
```

3. **Logical** :

- `AND` : returns true if both components are true.
- `OR` : returns true if any one of the components is true.
- `NOT` : returns the opposite boolean vallue of the condition.

* Example ✅

```SQL
SELECT * FROM employees WHERE salary > 5000000 AND age < 30;
```

4. **Bitwise** :

- `&` : bitwise AND
- `|` : bitwise OR
- `^` : bitwise XOR
