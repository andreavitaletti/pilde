# pilde



## Per vedere il blog in modo grazioso 

[https://docsify-this.net/?basePath=https://raw.githubusercontent.com/andreavitaletti/pilde/main/docs&homepage=blog_2015.md&sidebar=true&loadNavbar=_navbar.md&searchbox=true#/](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/andreavitaletti/pilde/main/docs&homepage=blog_2015.md&sidebar=true&loadNavbar=_navbar.md&searchbox=true#/)


Cambia l'anno, che nell'esepio qui sopra è 2015, con un valore da da 2006 a 2021

## Per stampare su due colonne  

```
--- 
 classoption:
 - twocolumn 
 author: Andrea Vitaletti 
---
```

```
pandoc -s blog_2020_2.md -o blog_2020.pdf
```