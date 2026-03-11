# 🕹️ Videojuego - Escape Room (Assembly Z80)

> Un videojuego de exploración y lógica desarrollado íntegramente en lenguaje ensamblador para la arquitectura Amstrad CPC, enfocado en la gestión directa de hardware y memoria.

---

## 🎯 El Desafío
El reto principal fue construir una lógica de juego compleja (gestión de inventario, colisiones y cambio de escenarios) trabajando con las limitaciones físicas de una arquitectura de computadoras real:
* **Problema:** Controlar el flujo de un juego con 16 habitaciones y mecánicas de desbloqueo usando recursos mínimos.
* **Solución:** Implementación de rutinas optimizadas de lectura de memoria, manejo de etiquetas para saltos condicionales y gestión manual de la memoria de video.

## 🛠️ Tecnologías y Entorno
* **Lenguaje:** Lenguaje Ensamblador (Assembly Z80) / Código Máquina.
* **Plataforma:** WinAPE (Emulador de Amstrad CPC).
* **Modo de Video:** Modo 0 (Permitiendo una paleta de 16 colores simultáneos para mayor detalle en sprites).

## ✨ Aspectos Técnicos
* ✅ **Gestión de Memoria:** Uso estratégico de direcciones de memoria específicas para almacenar el estado de las 7 llaves y las banderas (flags) de las habitaciones bloqueadas.
* ✅ **Gráficos por Software:** Renderizado de sprites mediante el direccionamiento directo a la memoria de video del sistema.
* ✅ **Lógica de Juego:** Implementación manual de bucles de control, subrutinas para el movimiento del personaje y validación de colisiones mediante etiquetas.
* ✅ **Interfaz:** Diseño de una experiencia sencilla y funcional dentro de las restricciones del código máquina.
