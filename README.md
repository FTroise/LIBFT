# LIBFT


![Build Status](https://img.shields.io/badge/build-passing-brightgreen) ![License](https://img.shields.io/badge/license-MIT-blue) ![Language](https://img.shields.io/badge/language-C-blue)

> **Libft** is my first project at 42 School, where I created a custom C library. This project includes essential functions from the standard library and additional utilities that I will use in future projects. The objective is to deepen my knowledge of C, memory management, and function handling.

> **Libft** è il mio primo progetto alla 42 School, dove ho creato una libreria C personalizzata. Questo progetto include funzioni essenziali della libreria standard e altre utility aggiuntive che userò nei progetti futuri. L’obiettivo è approfondire la mia conoscenza del C, della gestione della memoria e della manipolazione delle funzioni.

---

## Table of Contents

- [About](#about)
- [Features](#features)
- [Functions](#functions)
- [Compilation](#compilation)
- [Usage](#usage)

---

## About

This project includes:
- **Standard functions**: Recreating basic C library functions.
- **Memory functions**: Functions to manage memory allocation and manipulation.
- **Extra utilities**: Additional string manipulation functions and other utilities.
- **Bonus functions**: Handling linked lists and other data structures.

## Features

| Function Group         | Description                                               | Example                  |
|------------------------|-----------------------------------------------------------|--------------------------|
| **String Manipulation**| Manipulates and analyzes strings in various ways.         | `ft_strlen`, `ft_strcpy` |
| **Memory Management**  | Handles memory allocation, deallocation, and copying.     | `ft_memset`, `ft_calloc` |
| **Character Checks**   | Checks properties of characters (e.g., `isalnum`, `isdigit`). | `ft_isalpha`, `ft_isdigit` |
| **Linked Lists**       | Implements functions for linked list management.          | `ft_lstadd`, `ft_lstdelone` |

| Gruppo di Funzioni       | Descrizione                                               | Esempio                   |
|--------------------------|-----------------------------------------------------------|---------------------------|
| **Manipolazione Stringhe** | Manipola e analizza le stringhe in vari modi.              | `ft_strlen`, `ft_strcpy`  |
| **Gestione della Memoria** | Gestisce l’allocazione, deallocazione e copia della memoria. | `ft_memset`, `ft_calloc`  |
| **Controllo Caratteri**    | Verifica le proprietà dei caratteri (ad esempio, `isalnum`, `isdigit`). | `ft_isalpha`, `ft_isdigit` |
| **Liste Collegate**       | Implementa funzioni per la gestione delle liste concatenate. | `ft_lstadd`, `ft_lstdelone` |


---

## Functions

Here’s a list of all the functions included in **Libft** with a brief description:

| **Function**        | **Description**                                                                                 |
|---------------------|-------------------------------------------------------------------------------------------------|
| `ft_atoi.c`         | 🇬🇧 <span style="color:green">Converts a string to an integer.</span> <br> 🇮🇹 <span style="color:blue">Converte una stringa in un intero.</span> |
| `ft_bzero.c`        | 🇬🇧 <span style="color:green">Sets all bytes of a memory area to zero.</span> <br> 🇮🇹 <span style="color:blue">Imposta tutti i byte di un'area di memoria a zero.</span> |
| `ft_calloc.c`       | 🇬🇧 <span style="color:green">Allocates and clears memory for an array.</span> <br> 🇮🇹 <span style="color:blue">Alloca e azzera la memoria per un array.</span> |
| `ft_isalnum.c`      | 🇬🇧 <span style="color:green">Checks if a character is alphanumeric.</span> <br> 🇮🇹 <span style="color:blue">Verifica se un carattere è alfanumerico.</span> |
| `ft_isalpha.c`      | 🇬🇧 <span style="color:green">Checks if a character is alphabetic.</span> <br> 🇮🇹 <span style="color:blue">Verifica se un carattere è alfabetico.</span> |
| `ft_isascii.c`      | 🇬🇧 <span style="color:green">Checks if a character is in the ASCII set.</span> <br> 🇮🇹 <span style="color:blue">Verifica se un carattere è nel set ASCII.</span> |
| `ft_isdigit.c`      | 🇬🇧 <span style="color:green">Checks if a character is a digit.</span> <br> 🇮🇹 <span style="color:blue">Verifica se un carattere è un numero.</span> |
| `ft_isprint.c`      | 🇬🇧 <span style="color:green">Checks if a character is printable.</span> <br> 🇮🇹 <span style="color:blue">Verifica se un carattere è stampabile.</span> |
| `ft_itoa.c`         | 🇬🇧 <span style="color:green">Converts an integer to a string.</span> <br> 🇮🇹 <span style="color:blue">Converte un intero in una stringa.</span> |
| `ft_lstadd_back.c`  | 🇬🇧 <span style="color:green">Adds a new element at the end of a list.</span> <br> 🇮🇹 <span style="color:blue">Aggiunge un nuovo elemento alla fine di una lista.</span> |
| `ft_lstadd_front.c` | 🇬🇧 <span style="color:green">Adds a new element at the beginning of a list.</span> <br> 🇮🇹 <span style="color:blue">Aggiunge un nuovo elemento all'inizio di una lista.</span> |
| `ft_lstclear.c`     | 🇬🇧 <span style="color:green">Clears and frees an entire list.</span> <br> 🇮🇹 <span style="color:blue">Libera tutta la memoria occupata da una lista.</span> |
| `ft_lstdelone.c`    | 🇬🇧 <span style="color:green">Deletes a single element from a list.</span> <br> 🇮🇹 <span style="color:blue">Cancella un singolo elemento da una lista.</span> |
| `ft_memchr.c`       | 🇬🇧 <span style="color:green">Searches for a character in a memory area.</span> <br> 🇮🇹 <span style="color:blue">Cerca un carattere in un'area di memoria.</span> |
| `ft_memcmp.c`       | 🇬🇧 <span style="color:green">Compares two memory areas.</span> <br> 🇮🇹 <span style="color:blue">Confronta due aree di memoria.</span> |
| `ft_memcpy.c`       | 🇬🇧 <span style="color:green">Copies memory from one area to another.</span> <br> 🇮🇹 <span style="color:blue">Copia la memoria da un'area a un'altra.</span> |
| `ft_memset.c`       | 🇬🇧 <span style="color:green">Fills a memory area with a specific value.</span> <br> 🇮🇹 <span style="color:blue">Riempe un'area di memoria con un valore specifico.</span> |
| `ft_putchar_fd.c`   | 🇬🇧 <span style="color:green">Writes a character to a file descriptor.</span> <br> 🇮🇹 <span style="color:blue">Scrive un carattere su un file descriptor.</span> |
| `ft_putendl_fd.c`   | 🇬🇧 <span style="color:green">Writes a string followed by a newline to a file descriptor.</span> <br> 🇮🇹 <span style="color:blue">Scrive una stringa seguita da un newline su un file descriptor.</span> |
| `ft_putnbr_fd.c`    | 🇬🇧 <span style="color:green">Writes an integer to a file descriptor.</span> <br> 🇮🇹 <span style="color:blue">Scrive un intero su un file descriptor.</span> |
| `ft_split.c`        | 🇬🇧 <span style="color:green">Splits a string into an array of strings based on a delimiter.</span> <br> 🇮🇹 <span style="color:blue">Divide una stringa in un array di stringhe in base a un delimitatore.</span> |
| `ft_strjoin.c`      | 🇬🇧 <span style="color:green">Concatenates two strings into a new string.</span> <br> 🇮🇹 <span style="color:blue">Concatena due stringhe in una nuova stringa.</span> |
| `ft_strlen.c`       | 🇬🇧 <span style="color:green">Calculates the length of a string.</span> <br> 🇮🇹 <span style="color:blue">Calcola la lunghezza di una stringa.</span> |


---

## Compilation

To compile the library, run the following command:

```bash
make


