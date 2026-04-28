# Árbol BST Empresarial en C++

## Integrantes
- Nombre 1
- Nombre 2
- Nombre 3
- Nombre 4

## Objetivo
Implementar un árbol binario de búsqueda (BST) en C++ para organizar empleados de una empresa usando un código numérico como clave.

## Estructura del proyecto
```
arbol-bst-empresa/
├── src/
│   └── main.cpp       ← Código fuente principal
├── capturas/          ← Capturas de pantalla de ejecución
└── README.md
```

## Funcionalidades
- Insertar empleados (código, nombre, cargo)
- Buscar empleados por código
- Mostrar raíz del árbol
- Recorrido **inorden** (ordenado)
- Recorrido **preorden**
- Recorrido **postorden**
- Calcular **altura** del árbol
- Mostrar **nodos hoja**
- Cargar **datos de prueba** automáticos

## Compilar y ejecutar

### En Linux/Mac (terminal):
```bash
cd src
g++ main.cpp -o arbol
./arbol
```

### En Windows (terminal):
```bash
cd src
g++ main.cpp -o arbol.exe
arbol.exe
```

### En Visual Studio (Windows):
1. Abrir Visual Studio
2. Crear nuevo proyecto → **Proyecto vacío** (C++)
3. Agregar `src/main.cpp` al proyecto
4. Presionar `Ctrl+F5` para compilar y ejecutar

### En Visual Studio Code:
1. Abrir la carpeta `arbol-bst-empresa/`
2. Abrir terminal integrada (`Ctrl+ñ`)
3. Ejecutar:
   ```bash
   g++ src/main.cpp -o arbol
   ./arbol
   ```

## Datos de prueba sugeridos

| Código | Nombre           | Cargo         |
|--------|------------------|---------------|
| 50     | Empresa UTA      | Raíz          |
| 30     | Gerente Ventas   | Nodo interno  |
| 70     | Gerente Finanzas | Nodo interno  |
| 20     | Emp 1            | Hoja          |
| 40     | Emp 2            | Hoja          |
| 60     | Emp 3            | Hoja          |
| 80     | Emp 4            | Hoja          |

> Usa la opción **9** del menú para cargar estos datos automáticamente.

## Conceptos del árbol

- **Raíz**: Nodo principal (código 50 - Empresa UTA)
- **Nodo interno**: Tiene al menos un hijo (Gerentes)
- **Hoja**: No tiene hijos (Empleados finales)
- **Nivel**: Distancia desde la raíz
- **Altura**: Número máximo de niveles (este árbol tiene altura 3)

## Capturas
Agregar capturas de:
1. Menú principal
2. Inserción de empleados
3. Búsqueda de empleado
4. Recorrido inorden
5. Altura y hojas

## Conclusión
El árbol BST permite organizar información jerárquica de forma eficiente. Las búsquedas tienen complejidad O(log n) en el caso promedio, lo que lo hace ideal para sistemas de organización empresarial.
