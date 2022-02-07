# Titlepage for LPNU reports

Typeset LaTeX title page for reports and other types of works

## Screenshot
![Screenshot](https://raw.githubusercontent.com/electrocicada/lpnu-titlepage/main/images/titlepage.jpg "Screenshot")
## Requirements
There are several packages in this document related to the encoding and the special characters.  
Font encoding:
```
\usepackage[T2A]{fontenc}
```
Input encoding:
```
\usepackage[utf8]{inputenc}
```
Language-specific packag
```
\usepackage[ukrainian]{babel}
```
The title page also contains the logo. These packages are required for correct display
```
\usepackage{graphicx}
\graphicspath{{images/}} 
```
## Use keywords to define titlepage attributes
```
\newcommand\Type{лабораторної роботи}
\newcommand\Number{№1}
\newcommand\Subject{Основи організації та функціонування комп'ютерів}
\newcommand\Theme{Дослідження інструкцій переходів і зсувів. Організація циклів}
\newcommand\Class{ст.гр. КІ-24}
\newcommand\Author{Дерев'янко С.Т.}
\newcommand\Position{ст.викладач}
\newcommand\Teacher{Кудрявцев О.Т.}
```
