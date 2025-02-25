# Jaccard 🧬

Calculate the similarity index between two texts.

This uses the [Jaccard index](https://en.wikipedia.org/wiki/Jaccard_index) (developed by [Paul Jaccard](https://en.wikipedia.org/wiki/Paul_Jaccard)) to determine how similar two texts are.


### Prerequisites

Before starting, ensure you have the following dependencies installed locally:

- **dune** (v**3.16** or higher)
- **OCaml** (v**4.08.0** or higher)
- **make**

### Usage

**Steps**

1. Clone this repository and open it

2. Compile the program with the command

```
make
```

3. Then you can use it as specified here :

```
USAGE: ./jaccard <str1> <str2> [OPTIONS]

   <str1>          : The first text to compare (as a string)
   <str2>          : The second text to compare (as a string)

OPTIONS:
   -n              : print the numeric result only. E.g: 42.00%
   -h              : display this message
```

<br>

You can find some **Input-Output examples** [here](/examples/examples.md)

### License

This project is licensed under the Apache 2.0 License - see the [LICENSE](/LICENSE) file for details.