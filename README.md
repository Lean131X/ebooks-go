# ebooks-go
Sistema de Gestión de Libros Electrónicos (Go) - Aprendizaje Autónomo 1


## Objetivo general
Diseñar un sistema básico que permita registrar libros y usuarios, y consultar la información desde un menú en consola, aplicando estructuras de programación vistas en la Unidad 1 de Go.

## Objetivos específicos
1. Implementar un menú en consola para gestionar usuarios y libros mediante funciones en Go.  
2. Desarrollar operaciones básicas (registrar, listar y buscar) usando condicionales y bucles.  
3. Aplicar programación modular separando la lógica de usuarios, libros y búsquedas.

## Alcance (v1.0)
- Usuarios: registrar y listar  
- Libros: registrar y listar  
- Búsqueda: por título  
- Menú en consola

## Fuera de alcance (v1.0)
Lectura real de e-books, autenticación/roles, BD real, reportes avanzados.

## Estructura planificada
```
ebooks-go/
├─ main.go
├─ usuarios.go
├─ libros.go
└─ README.md
```

markdown
Copiar código

## Paquetes incorporados (Go stdlib)
`fmt`, `bufio`, `os`, `strings`

## Programación funcional
Cada operación se implementará como una función independiente y reutilizable
(`crearUsuario`, `listarUsuarios`, `crearLibro`, `listarLibros`, `buscarLibrosPorTitulo`).

## Video explicativo (guion)
1) Objetivo general y específicos  
2) Alcance y módulos  
3) Estructura del repositorio  
4) Relación con Unidad 1  
5) Mejoras futuras
