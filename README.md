# Del
Del is a programming language created in 2024. It's pretty much a simple version of C with extra feautures; kind of like the C+ that never was. The name "Del" is an acronym and it stands for **D**efinable **E**nvironment **L**anguage.

## Purpose
Del was created for multiple purposes.
1. Because the author was bored
2. Because the author wanted to use it in a GUI library
3. Because the author wanted a language with a controllable environment

### Why?
That is probably the most common response to a new programming language. My answer is "Why not?"

## Download
Find download instructions [here](download.md).

## Docs, Tutorials, & Hello World
Here is a hello world program in Del, given the standard library is available and you are calling the `main` function at startup:

```
include lib "stdlib"

int main(int argc, int argv) {
  println("Hello World");
  return 0;
}
```

If you are dying to know how this is different from a C program, read [here](docs/about.md)

If you want to read the documentation, go [here](docs/index.md)

If you want to learn Del, tutorials are provided [here](learn/index.md)
