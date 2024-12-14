# Mapa Conceptual de "Logos" en Heráclito

```mermaid
graph TD
    A[Logos] --> B[Como Razón Universal]
    A --> C[Como Palabra o Discurso]
    A --> D[Como Ley Común]
    A --> E[Unidad de Opuestos]
    A --> F[Crítica al Entendimiento Humano]
    A --> G[Como Sabiduría]
    A --> H[Relación con el Cambio]
    
    %% Razón Universal
    B --> B1[Permanece siempre - DK 22 B1]
    B --> B2[Todo sucede según el logos - DK 22 B31]
    B --> B3[Estructura del cosmos - DK 22 B41]
    B --> B4[Contrarios convergen - DK 22 B64]

    %% Palabra o Discurso
    C --> C1[Escuchar al logos - DK 22 B50]
    C --> C2[Logos como medio de sabiduría - DK 22 B56]
    C --> C3[Hablar con verdad - DK 22 B116]

    %% Ley Común
    D --> D1[Lo común une a todos - DK 22 B2]
    D --> D2[Leyes humanas según el logos - DK 22 B45]
    D --> D3[Justicia cósmica - DK 22 B44]

    %% Unidad de Opuestos
    E --> E1[Todo es uno - DK 22 B50]
    E --> E2[Arriba y abajo es un solo camino - DK 22 B10]
    E --> E3[Armonía invisible superior - DK 22 B80]

    %% Crítica al Entendimiento Humano
    F --> F1[Incapacidad de entender - DK 22 B1]
    F --> F2[Lo cercano es ignorado - DK 22 B17]
    F --> F3[Desconexión humana - DK 22 B89]

    %% Sabiduría
    G --> G1[Reconocer el logos es sabio - DK 22 B50]
    G --> G2[Solo los sabios entienden - DK 22 B43]
    G --> G3[El logos como verdad absoluta - DK 22 B112]

    %% Relación con el Cambio
    H --> H1[Nunca el mismo río - DK 22 B49]
    H --> H2[El logos guía el devenir - DK 22 B46]
    H --> H3[Todo fluye hacia el logos - DK 22 B76]
yaml
Copy code

> **Importante**: Fíjate bien en dónde empieza y termina el bloque de código.  
> - Comienza con tres backticks ``` + la palabra `mermaid`.  
> - Finaliza con tres backticks separados (sin agregar texto después de la línea del diagrama).

---

### ¿Por qué se produce el error?

- **Caracteres conflictivos**: A veces los paréntesis u otros caracteres especiales dentro de los labels **rompen** el parser de Mermaid.
- **Texto mezclado** en el mismo bloque de código: Si pones texto Markdown (`### Por qué funciona`, etc.) **dentro** del bloque `mermaid`, Mermaid intentará parsearlo como parte del diagrama.
- **Etiqueta de código mal cerrada**: Si la línea final de triple backticks no está en una línea **aparte**, se genera un error de sintaxis.

---

Con este bloque **auto contenido** y limpio, deberías poder renderizar tu diagrama en GitHub sin problemas. Luego, si quieres añadir explicaciones tipo “### Por qué funciona” o “### Instrucciones”, **hazlo fuera** del bloque Mermaid.
