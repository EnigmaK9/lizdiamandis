# Mapa Conceptual de "Logos" en Heráclito

```mermaid
graph TD
    A[Logos] --> B[Como Razón Universal]
    A --> C[Como Palabra/Discurso]
    A --> D[Como Ley Común]
    A --> E[Unidad de Opuestos]
    A --> F[Crítica al Entendimiento Humano]
    A --> G[Como Sabiduría]
    A --> H[Relación con el Cambio]
    
    %% Razón Universal
    B --> B1[Permanece siempre (DK 22 B1)]
    B --> B2[Todo sucede según el logos (DK 22 B31)]
    B --> B3[Estructura del cosmos (DK 22 B41)]
    B --> B4[Contrarios convergen (DK 22 B64)]

    %% Palabra/Discurso
    C --> C1[Escuchar al logos (DK 22 B50)]
    C --> C2[Logos como medio de sabiduría (DK 22 B56)]
    C --> C3[Hablar con verdad (DK 22 B116)]

    %% Ley Común
    D --> D1[Lo común une a todos (DK 22 B2)]
    D --> D2[Leyes humanas según el logos (DK 22 B45)]
    D --> D3[Justicia cósmica (DK 22 B44)]

    %% Unidad de Opuestos
    E --> E1[Todo es uno (DK 22 B50)]
    E --> E2[Camino hacia arriba y abajo (DK 22 B10)]
    E --> E3[Armonía invisible superior (DK 22 B80)]

    %% Crítica al Entendimiento Humano
    F --> F1[Incapacidad de entender (DK 22 B1)]
    F --> F2[Lo cercano es ignorado (DK 22 B17)]
    F --> F3[Desconexión humana (DK 22 B89)]

    %% Sabiduría
    G --> G1[Reconocer el logos es sabio (DK 22 B50)]
    G --> G2[Sólo los sabios entienden (DK 22 B43)]
    G --> G3[Logos como verdad absoluta (DK 22 B112)]

    %% Relación con el Cambio
    H --> H1[Nunca el mismo río (DK 22 B49)]
    H --> H2[Logos guía el devenir (DK 22 B46)]
    H --> H3[Todo fluye hacia el logos (DK 22 B76)]
markdown
Copy code

### ¿Por qué funciona?

1. **Encabezado de diagrama**: La línea `graph TD` (Top-Down) indica a Mermaid que vas a generar un diagrama de tipo flowchart.
2. **Bloque de código con lenguaje mermaid**: Entre las triple backticks (```) se especifica ```mermaid, lo que permite a GitHub (y otros visores Mermaid) identificar y renderizar el diagrama.
3. **Estructura de nodos y flechas**: Cada flecha `-->` crea una relación padre-hijo en el diagrama. Los corchetes `[Texto]` se usan para mostrar el label en cada nodo.

### Pasos a seguir

1. **Pega tal cual** el bloque de código anterior en tu `README.md`.
2. **Sube** ese `README.md` a GitHub o visualízalo en la vista previa en línea.  
3. Asegúrate de que tu repositorio tenga activada la opción de renderizar Mermaid (normalmente ya viene activada por defecto en GitHub).

Si hiciste todo y aún no funciona:
- Verifica que el nombre del archivo sea `README.md` (en mayúsculas no suele haber problema, pero mejor revisarlo).
- Revisa la pestaña **Settings** de tu repositorio, buscando alguna opción relacionada con "Diagrams" o "Mermaid".  
- Prueba en [Mermaid Live Editor](https://mermaid-js.github.io/mermaid-live-editor/) para confirmar que el diagrama se genera sin errores. Si ahí funciona, debería funcionar en GitHub también.

¡Así debería renderizarse el diagrama sin problemas!
