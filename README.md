# 🎲 Kiriki (Juego de Dados por Consola)

Este es un juego de consola en Python que implementa una versión simplificada del clásico juego de dados **Kiriki**. Se trata de un juego de faroles, azar y estrategia, ideal para disfrutar entre amigos... ¡aunque sea virtualmente!

---

## 🕹️ ¿En qué consiste Kiriki?

Kiriki es un juego de dados en el que los jugadores lanzan dos dados y deben **mentir o decir la verdad** sobre su tirada, con el objetivo de superar al jugador anterior sin ser descubiertos. El siguiente jugador puede creer o **dudar del anuncio**. Si duda y tenía razón, gana. Si duda y se equivoca, pierde. ¡Así de simple y adictivo!

---

## 💡 Características de esta implementación

- Juego por consola para 2 o más jugadores (modo texto).
- Lanzamiento aleatorio de dados (simulado con `Random`).
- Sistema de turnos.
- Validación de faroles y comprobación de la tirada real.

---

## 🚀 Cómo ejecutar

1. Asegúrate de tener **Python instalado** en tu sistema.
2. Compila el archivo principal del juego:
   ```bash
   python kiriki.py

## 🧠 Reglas simplificadas
1. El jugador 1 lanza los dados y dice qué ha salido (puede mentir o decir la verdad).

2. El jugador 2 debe decidir:
    - Creer y lanzar los dados para superar la tirada anunciada.
    - Dudar. Si el jugador anterior mentía, el que duda gana. Si decía la verdad, pierde una vida.

3. El juego continúa con el siguiente jugador, si no lo hubiera, el jugador que ha quedado con vidas es el ganador.

## 🧑‍💻 Autor
Alejandro Rodríguez Moreno
