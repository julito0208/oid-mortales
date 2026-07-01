# Roadmap — Vertical Slice Demo

> Objetivo único de esta etapa: **5–15 min jugables que demuestren el feel del combate montado.**
> Regla de oro: si algo no ayuda a demostrar el combate montado, es secundario.

## M0 — Fundaciones (repo + proyecto)

- [x] Estructura de repo, `.gitignore` y Git LFS (`.gitattributes`).
- [ ] Definir SO de desarrollo (Linux vs Windows).
- [ ] Instalar UE5 y crear el `.uproject` base (C++ habilitado).
- [ ] Plugins base: **Enhanced Input**. Mapa de prueba (greybox, sin arte).

## M1 — Movimiento a caballo *(Prioridad #1)*

El caballo tiene que sentirse con **peso, inercia y velocidad** creíbles.

- [ ] Pawn/Character del caballo + jinete (empezar greybox: una cápsula sobre un caballo placeholder).
- [ ] Control: acelerar, frenar, girar con inercia (no arcade instantáneo).
- [ ] Marchas/gaits: paso → trote → galope, con transiciones.
- [ ] Cámara que acompañe bien la velocidad (clave para el feel).
- [ ] **Checkpoint de feel:** jugar 2 min solo cabalgando. ¿Se siente un caballo o una moto?

## M2 — Combate montado con UN arma *(arrancar simple)*

Elegir **una** para el primer prototipo (recomendación: sable corvo por ser melee directo,
o boleadoras si querés apostar al diferenciador de proyectil desde el vamos).

- [ ] Input de ataque simultáneo al control del caballo (el gran desafío: manejar + atacar).
- [ ] Animación de ataque montado (placeholder ok) + detección de golpe.
- [ ] Un enemigo/dummy para pegarle (a pie o montado).
- [ ] **Checkpoint de feel:** ¿pegar montado se siente contundente y responsivo?

## M3 — Iteración de feel *(antes de sumar nada)*

- [ ] Tuning de responsiveness: input buffering, timing de golpe, feedback (cámara, hitstop, sonido).
- [ ] Recién cuando M2 se sienta sólido → evaluar segunda arma.

## M4 — Presentación para el grant *(secundario hasta que M1–M3 estén sólidos)*

- [ ] Vestir el greybox con arte/assets mínimos que vendan la ambientación gaucha.
- [ ] Cinemática corta (Sora/Kling) + voz (ElevenLabs) para el pitch.
- [ ] Recorte de 5–15 min grabable para la aplicación a MegaGrants.

---

### Señales de scope creep a vigilar
- Sumar una segunda o tercera arma antes de que la primera se sienta bien.
- Meter sistemas (inventario, misiones, diálogo) que no demuestran combate montado.
- Pulir arte final antes de tener el feel resuelto en greybox.
