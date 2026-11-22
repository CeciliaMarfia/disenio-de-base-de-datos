# Diseño de Bases de Datos

Material de la materia Diseño de Bases de Datos (Facultad de Informática, UNLP), cursada 2025.

## Estructura

```
.
├── conceptual/                  # Modelo conceptual (entidad-relación)
│   ├── explicacion-modelo-conceptual.pptx
│   ├── practica-1-modelo-conceptual.pdf
│   └── practica-2-modelo-conceptual.pdf
├── logico-fisico/               # Pasaje a modelo lógico y físico
│   ├── explicacion-modelo-logico.pptx
│   └── explicacion-modelo-fisico.pptx
├── lenguaje-de-consultas/
│   ├── algebra-relacional/
│   │   ├── explicacion-4-algebra-relacional.pdf
│   │   └── practica-3-algebra-relacional.pdf
│   └── sql/
│       ├── explicacion-5-sql.pdf
│       ├── explicacion-6-sql-parte-2.pdf
│       └── practica-4-sql.pdf
├── teoria/                      # Diapositivas de las clases teóricas
│   ├── 3-1-conceptual-segunda-parte.pptx
│   ├── 5-1-algebra-relacional.pptx
│   ├── 6-2-sql-parte-2.pptx
│   ├── 7-optimizacion.pptx
│   ├── 8-1-transacciones-primera-parte.pptx
│   └── ejemplos-caser/          # Ejemplos de modelos hechos en CASER
├── docker/                      # Entorno MySQL + Adminer
│   ├── guia-mysql-adminer-docker.pdf
│   └── docker-curso-dbd.zip
└── practica/                    # Resoluciones propias de las prácticas
```

## Temas

1. **Modelo conceptual**: entidades, relaciones, atributos, cardinalidades y jerarquías.
2. **Modelo lógico y físico**: pasaje del modelo conceptual a tablas, claves y restricciones.
3. **Álgebra relacional**: selección, proyección, producto cartesiano, junta, división y demás operadores.
4. **SQL**: consultas, funciones de agregación, agrupamiento, subconsultas y modificación de datos.
5. **Optimización de consultas**.
6. **Transacciones**.

## Entorno de trabajo

Para practicar SQL se usa MySQL con Adminer en Docker. Los pasos están en [`docker/guia-mysql-adminer-docker.pdf`](docker/guia-mysql-adminer-docker.pdf) y los archivos de configuración en `docker/docker-curso-dbd.zip`.
