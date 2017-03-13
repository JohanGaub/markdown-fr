# Titres

En commençant à écrire dans un document "markdown", nous devons ajouter une titre et quelques sous-en-tetes.

Markdown se sert de 2 styles d'en-tetes, Setext and atx.

Les en-tetes Setext sont “soulignées” en utilisant les signes "égal" (pour le 1er miveau d'en-tetes) et and des tirets (for le second niveau d'en-tetes). Par exemple:

```
C'est un H1
=============

C'est un H2
-------------
```

Any number of underlining =’s or -’s will work.

Atx-style headers use 1-6 hash characters at the start of the line, corresponding to header levels 1-6. For example:

```
# This is an H1

## This is an H2

###### This is an H6
```


Optionally, you may “close” atx-style headers. This is purely cosmetic — you can use this if you think it looks better. The closing hashes don’t even need to match the number of hashes used to open the header. (The number of opening hashes determines the header level.) :

```
# This is an H1 #

## This is an H2 ##

### This is an H3 ######
```


---

Here's a quiz about markdown titles.

Select the valid headers:
- [x] `# hello`
- [ ] `#hello`

> Headers need space between the hash characters and the text.

Select the valid headers:
- [ ]  
```
test
########
```
- [x]   
```
test
=======
```

> Only '=' and '-' are accepted for underlining an header.

---
