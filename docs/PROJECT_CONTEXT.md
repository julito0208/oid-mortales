# Contexto de Proyecto — Gaucho Estudios / *Oíd Mortales*

> Fuente de verdad del proyecto. Si algo cambia de scope o dirección, se actualiza acá.

## Qué es

Juego de acción en **Unreal Engine 5** (Nanite, Lumen) con identidad **Gaucho-Core**:
ambientación histórica argentina, combate montado, y estética/cultura gaucha como
diferenciador central. Pensado como posible **trilogía** a futuro, pero el foco actual
está **acotado a un primer juego** con calidad alta en áreas puntuales — **no** un AAA completo.

## Objetivo inmediato: Vertical Slice Demo

- **5–15 minutos** de contenido jugable.
- Debe demostrar el **feel del combate montado** — es el corazón, no se difiere ni recorta.
- Paso previo a buscar funding vía **Epic MegaGrants**.

## Mecánica core: Combate montado

Diferenciador técnico y de diseño más importante, y el más complejo. **Prioridad #1.**

Armas a integrar (en el tiempo, no todas de una):
- **Boleadoras**
- **Lazo**
- **Sable corvo**

Todo montado a caballo de forma creíble: control del caballo + combate simultáneo es
probablemente el mayor desafío técnico de la demo.

## Identidad visual/cultural

- Ambientación histórica argentina (época gaucha).
- Consultor histórico de referencia: **Felipe Pigna**.
- Ancla visual de marca: **poncho salteño** (forma rombo/diamante), rojo punzó, negro,
  blanco, amarillo, con guardas pampa y flecos. Más para marca/UI/menús que para gameplay,
  pero sirve como dirección de arte.

## Pipeline de producción con IA

- **Sora / Kling** → cinemáticas.
- **ElevenLabs** → voces.
- (Todo web / OS-agnóstico.)

## Filosofía de scope

- Viable como **primer juego acotado con calidad targeteada**, NO como trilogía AAA con equipo chico.
- Ante cualquier duda de alcance: **priorizar que el combate montado se vea y se sienta bien**,
  por sobre agregar más sistemas o contenido.
- Todo lo que no sea demostrar el combate montado en la vertical slice es secundario.

## Contexto de negocio

- Funding elegido: **Epic MegaGrants** (no dilutivo, sin equity, por milestones).
  Ventana Cycle 2 2026: fines de junio a principios de septiembre.
- Fuentes complementarias a futuro: Mecenazgo, INCAA, ADVA.
- Julio (dev) sigue en relación de dependencia hasta confirmar el grant.

## Decisiones técnicas tomadas

| Tema | Decisión | Fecha |
|------|----------|-------|
| Motor | Unreal Engine 5 (Nanite, Lumen) | — |
| Experiencia del dev | Viene de dev, gamedev nuevo → se explican decisiones de engine | 2026-07-01 |
| SO de desarrollo | **Debian 13 (Linux)** — decidido; Windows disponible solo si algo lo requiere | 2026-07-01 |
| Hardware dev | Ryzen 9800X3D · 64 GB RAM · RTX 5070 Ti (16 GB) — holgado para UE5 | 2026-07-01 |
| Versionado de assets | Git LFS configurado (`.gitattributes`) | 2026-07-01 |
