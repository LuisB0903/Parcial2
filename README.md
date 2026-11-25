# 🎮 Proyecto Parcial 2

Este documento contiene las reglas de colaboración y la estructura de ramas del proyecto.

---

## 🛠️ Configuración Inicial Obligatoria

Asegúrate de cumplir con estos requisitos:

1. **Versión del Motor:** Unreal Engine 5 (V 8).
2. **Git LFS:** Debes tener instalado Git LFS en tu computadora antes de clonar el proyecto.

- Ejecuta en tu terminal: `git lfs install`

3. **Estructura del Proyecto:** El repositorio utiliza programación visual con Blueprints y configuraciones de Inteligencia Artificial (IA).

---

## 🌿 Flujo de Ramas (Git Flow)

Trabajamos con la siguiente estructura:

- **`main`**: Versiones finales. Aquí están las entregas del proyecto para las evaluaciones de los parciales.
- **`develop`**: Rama de integración. Contiene los archivos que programamos en clase.

- **`feature/nombre-tarea`**: Ramas de desarrollo. Crea una nueva rama desde `develop` para aislar los avances de IA y objetos interactivos.

- **`bugfix/nombre-error`**: Ramas para corregir fallos encontrados en `develop`.

---

## 🚀 Proceso para Subir Cambios (Pull Requests)

Sigue este protocolo:

1. Asegúrate de que el nivel compila sin errores en tu rama local.

2. Haz `git pull origin develop` en tu rama para resolver conflictos localmente antes de subirla.

3. Sube tu rama a GitHub y abre un Pull Request (PR) hacia la rama `develop`.

4. El PR requiere la revisión de al menos un compañero antes de fusionarse.

---

## ⚠️ Reglas de Convivencia con Unreal y Git

Para evitar conflictos de mezcla:

- **Archivos Binarios:** Los mapas y Blueprints son binarios. Avisa al equipo antes de modificar una clase de IA o un nivel.

- **Commits Atómicos:** Haz commits pequeños y frecuentes. Un commit debe solucionar una sola cosa.

---

## 📝 Formato de Commits

Usa prefijos en tus mensajes de commit:

- `feat:` Nueva característica.

- `fix:` Corrección de un error.

- `refactor:` Rediseño de código existente sin cambiar su función.

- `asset:` Añadidos recursos visuales o sonoros.
