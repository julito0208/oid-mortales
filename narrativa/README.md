# Narrativa — Trilogía *Oíd Mortales*

> Biblia narrativa de la trilogía. Historia real (cruda) + guion/narrativa de cada juego.
> Documento de trabajo: se edita y reorganiza en iteraciones.

## El nombre

La trilogía toma su título del primer verso del **Himno Nacional Argentino**
(letra de Vicente López y Planes, aprobada por la Asamblea del Año XIII el
**11 de mayo de 1813**):

> **¡Oíd, mortales, el grito sagrado:**
> **Libertad, libertad, libertad!**

Cada juego es una palabra de ese grito, **un prócer como protagonista**, y una etapa de la
Guerra de Independencia:

| # | Juego | Protagonista | Verso / tema | Período | Set-piece montado |
|---|-------|--------------|--------------|---------|-------------------|
| 1 | **El Grito Sagrado** | **Manuel Belgrano** | El nacimiento del grito | 1806–1820 | Cargas de caballería en **Tucumán / Salta** |
| 2 | **Resistencia** | **Martín M. de Güemes** | Aguantar el grito | 1806–1821 | **Guerra Gaucha** (Salta/Jujuy) — gaucho-core |
| 3 | **Libertad** | **José de San Martín** | Cumplir el grito | 1808–1822 | España → **San Lorenzo** → Andes → Maipú |

> **Nota de scope:** el foco de producción sigue siendo la **vertical slice** de un
> primer juego (ver [`docs/PROJECT_CONTEXT.md`](../docs/PROJECT_CONTEXT.md)). Esta biblia
> mira la trilogía completa, pero **El Grito Sagrado** es lo único que se desarrolla ahora.

## Estructura de carpetas

```
narrativa/
├─ README.md                      ← este archivo (visión de la trilogía)
├─ historia-cruda-general.md      ← CRUDO MAESTRO de toda la gesta (fuente para repartir)
├─ 01-el-grito-sagrado/
│  ├─ historia-cruda.md           ← SOLO Belgrano: sus hechos, batallas, encuentros
│  └─ guion.md                    ← guion/narrativa del juego (ficción + historia)
├─ 02-resistencia/
│  ├─ historia-cruda.md
│  └─ guion.md
└─ 03-libertad/
   ├─ historia-cruda.md
   └─ guion.md
```

- **`historia-cruda-general.md`** → el **crudo maestro**: toda la Guerra de Independencia
  (fechas, batallas, decisiones, personajes) marcada con su relación a Belgrano 🔵 / Güemes 🟤 /
  San Martín 🟢. Desde acá se **reparte** el material a cada juego.
- **`NN-*/historia-cruda.md`** → la materia prima **de ese prócer**. Solo su línea: sus hechos,
  sus batallas, con quién se encuentra. Sin dramatizar. Fuente de precisión histórica (línea Pigna).
- **`guion.md`** → cómo lo convertimos en juego: protagonista, actos, misiones, personajes, tono,
  diálogos. La ficción se apoya en la historia cruda, nunca la contradice.

## Hilo conductor de la trilogía

**Cada juego es un prócer** — jugás como Belgrano, después como Güemes, después como San Martín.
No son tres desconocidos: sus historias se **entrelazan** y el hilo pasa de mano en mano.

Costuras reales que conectan los juegos:
- **Belgrano → Güemes:** Güemes militó en el Ejército del Norte bajo Belgrano antes de volverse
  el caudillo gaucho de Salta. El maestro y el discípulo.
- **Belgrano → San Martín:** en 1814 Belgrano, agotado, **le entrega el Ejército del Norte a
  San Martín** (encuentro de la Posta de Yatasto). El testigo pasa de mano.
- **La Bandera** que Belgrano crea en el juego 1 es el símbolo bajo el que pelean los otros dos.

Arco de la trilogía (uno por prócer, no de un solo personaje):
1. **Belgrano / El Grito Sagrado** — *el que crea*: de abogado a general improvisado. Inventa la
   Bandera y los símbolos. La Patria nace. Idealismo y sacrificio.
2. **Güemes / Resistencia** — *el que aguanta*: la guerra popular montada. Frena al imperio con
   gauchos. Madurez, pérdida, guerra larga. Gaucho-core.
3. **San Martín / Libertad** — *el que trasciende*: cruza los Andes, libera medio continente y
   se retira del poder. Entrega total.

## Principios narrativos

- **Historia como columna vertebral, ficción como matices.** Fechas, batallas y próceres son
  reales; la ficción se usa para llenar huecos (diálogos íntimos, secundarios de tropa,
  motivaciones), nunca para contradecir el hecho histórico.
- **El prócer de carne y hueso, no de bronce.** Jugás como Belgrano/Güemes/San Martín pero los
  mostramos humanos: dudas, miedo, enfermedad, cansancio. Bajarlos del monumento es el objetivo.
- **El grito es un motivo recurrente.** Arranca literal (Himno, 1813) y se vuelve símbolo:
  cada juego cierra con una variación del verso.
- **Gaucho-Core.** La estética y la mirada criolla/gaucha atraviesan todo; en *Resistencia*
  (Güemes) es el corazón mismo del juego.
- **Sin maniqueísmo barato.** Realistas y patriotas, criollos y españoles: gente, no íconos.
```
