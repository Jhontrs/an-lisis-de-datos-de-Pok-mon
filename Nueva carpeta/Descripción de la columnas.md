> **Descripción de la columnas**

**Nombre (name):**\
Esta columna indica el nombre del Pokémon, como \"Pikachu\" o
\"Charizard\". Es un campo de texto que identifica de manera única a
cada criatura en el conjunto de datos.

**Rango (rank):\
**Representa la posición del Pokémon en una clasificación específica,
posiblemente relacionada con su número en la Pokédex nacional o
regional. Es un valor numérico entero que ayuda a ordenar los Pokémon de
manera secuencial.

**Generación (generation):**\
Se refiere a la generación en la que el Pokémon fue introducido por
primera vez en los videojuegos de la serie principal. Las generaciones
van desde la 1 hasta la 9, y este dato es útil para clasificar los
Pokémon según su antigüedad.

**Evoluciona de (evolves_from):**\
Indica el nombre del Pokémon del cual evoluciona la criatura actual. Por
ejemplo, \"Pikachu\" evoluciona de \"Pichu\". Si el Pokémon no proviene
de una evolución previa (como los Pokémon legendarios o las primeras
etapas de una cadena evolutiva), este campo estará vacío.

**Tipo 1 (type1) y Tipo 2 (type2):**\
Estas columnas especifican los tipos elementales del Pokémon. \"Tipo 1\"
es obligatorio y define la principal afiliación elemental (como
\"Electric\" o \"Fire\"), mientras que \"Tipo 2\" es opcional y
representa un segundo tipo (por ejemplo, \"Flying\" en el caso de
Charizard). Si el Pokémon solo tiene un tipo, \"Tipo 2\" permanece
vacío.

**Estadísticas de Combate (hp, atk, def, spatk, spdef, speed):**\
Estas columnas contienen valores numéricos que representan las
estadísticas base del Pokémon:

-   HP (hp): Puntos de salud, que determinan cuánto daño puede resistir
    antes de debilitarse.

-   Ataque (atk): Poder de ataque físico, que influye en el daño causado
    por movimientos físicos.

-   Defensa (def): Resistencia a los ataques físicos.

-   Ataque Especial (spatk): Poder de ataque para movimientos
    especiales.

-   Defensa Especial (spdef): Resistencia a los ataques especiales.

-   Velocidad (speed): Determina el orden de ataque en combate.

**Total (total):\
**Es la suma de todas las estadísticas base del Pokémon (HP, Ataque,
Defensa, Ataque Especial, Defensa Especial y Velocidad). Este valor
proporciona una medida general de la fortaleza del Pokémon en combate.

**Altura (height) y Peso (weight):\
**Indican las dimensiones físicas del Pokémon. La altura se mide en
metros y el peso en kilogramos, lo que permite comparar el tamaño de
diferentes especies.

**Habilidades (abilities) y Habilidades Agrupadas (abilities_grouped):\
**Estas columnas detallan las habilidades especiales del Pokémon.
\"Habilidades\" las listas separadas por comas (por ejemplo, \"Static,
Lightning Rod\"), mientras que \"Habilidades Agrupadas\" puede
presentarlas en un formato estructurado, como una lista entre corchetes.
Las habilidades pueden afectar el combate de diversas maneras, como
causar efectos secundarios al atacar o defenderse.
