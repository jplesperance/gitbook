# Radare2

Open a file in debug mode

```text
root@kali$ r2 -d <file>
```

Analyze the file

```text
[0x00400a30]> aa
```

Search for a function

```text
[0x00400a30]> alf | grep <function_name>
```

Examine the code of a function

```text
[0x00400a30]> pdf @<function>
```

