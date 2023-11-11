# Lecture 9
![](./%D0%91%D0%B5%D0%B7%20%D0%BD%D0%B0%D0%B7%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F%20(2).png)
# Table of Content
## 1.Modules
## 2.Export
## 3.Import
># What is module sope
## Module in module scope ast ki iake az scopho ast mo baroi inro istifoda burdan dufilei nav kushoda dar iake az onho "type = "module" " medihem  Before modules, a variable declared outside any function was a global variable. In modules, a variable declared outside any function is hidden and not available to other modules unless itis explicitly exported. 
># What is Import and Export in js?
## Export in az iak file variable io iagon funksi io iagon logika ro girifta ba digar file mebarad export hamesha dar okhir navisonida meshavad
```
this file bu name main.js
let a = 5

expor { a }

you can take in in another file
```
## Import in az igon file iagon chizro qabul kardan import hamesha dar avval navisonida meshavad
```
import { a } from "./main.js" the name of file
```