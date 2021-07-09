---
layout: page
title: "Number Convertor"
subtitle: "Golang"
date: 2021-07-05 21:00:00 +0000
categories: Go
author: Jerry
meta: "Springfield"
---

In my first graduate year, a professor assigned us to write a number converter in C([here](https://github.com/mchen81/2020S-system-foundation/blob/main/number-converter/nt.c)). I liked the project, but I did not like C, so I decided to make this program again in GO.

## Input

The input can be in binary, signed number, unsigned number, or hex as long as it is not out range of int32. You can input a number from 2,147,483,647 to 4,294,967,295, it is considered as an unsigned int32.

```
0x123  // a hex number
0b110  // a binary number
35     // a digital number
-10    // a digital number
```

## Output

The output will print out 5 differernt types of number as following:

```
(signed) -3
(unsigned) 4294967293
(binary) 0b11111111111111111111111111111101
(binary) 1111 1111 1111 1111 1111 1111 1111 1101
(hex) 0xfffffffd
```

## Error Handling

If the input format is not correct, or it's too big or too small for int32, it tells

```
429496729323 is too big or too small(for int32).
```

```
0c123 is not a valid digital number
```

### Using Go Routines

This project is just for me to practice, so I used unbuffered channels:

```go
	bi := make(chan string)
	bih := make(chan string)
	hex := make(chan string)

	go func() {
		bi <- toBinary(un)
	}()

	go func() {
		bih <- toHumanReadBinary(un)
	}()

	go func() {
		hex <- toHex(un)
	}()

```
