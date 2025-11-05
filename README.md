# Mercaderías Modernas – Sistema de Gestión de Inventarios en C

## Descripción del proyecto
Este programa fue desarrollado como parte del **Método Caso 1 – Programación (Unidad 3: Sentencias de Control)**.  
Simula un sistema básico de gestión de inventarios para la PYME *“Mercaderías Modernas”*, aplicando las principales estructuras de control en el lenguaje **C**:

- **Condicionales:** `if–else`, `switch`
- **Bucles:** `while`, `do–while`, `for`
- **Constantes y variables** (sin uso de arreglos, punteros ni estructuras)

El programa permite:
- Comprobar el nivel de inventario y ejecutar reposición automática.
- Controlar el acceso mediante contraseña.
- Simular ventas diarias con reposiciones automáticas.
- Evaluar la mejora de eficiencia antes y después del sistema.
- Procesar ítems de manera secuencial, garantizando una ejecución controlada.

---

## Objetivo académico
Analizar críticamente las decisiones de programación tomadas y demostrar la aplicación práctica de las sentencias de control en un contexto empresarial.  
El caso se fundamenta en la integración de conceptos de las **Unidades 1, 2 y 3** del temario de Programación.

---

## contenido del repositorio
| Archivo | Descripción |
|----------|--------------|
| `main.c` | Código fuente del programa en C |
| `README.md` | Documento explicativo del proyecto |

---

## Compilación y ejecución

### Requisitos
- Compilador **GCC** o cualquier entorno compatible con C11.  
- Sistema operativo Linux, macOS o Windows (con WSL o MinGW).

### Compilar
```bash
gcc -std=c11 -Wall -Wextra -O2 -o mm_inventory main.c
