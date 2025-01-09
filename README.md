# 1f40d

🐍

Just learning python.

## How to get decimal and hex representation of emojis

With a shell:

```shell
printf "Decimal: %d\nHexadecimal: %x\n" "'🐍" "'🐍"
```

And of course - with python:

```python
python -c 'print("Decimal:", ord("🐍"), "Hexadecimal:", hex(ord("🐍")))'
```
