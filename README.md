# ⚡ React + Redux Toolkit: Global State Practice

Este repositorio es un laboratorio práctico diseñado para dominar el manejo de estado global utilizando **Redux Toolkit (RTK)**. El proyecto se centra en un contador funcional que sirve como base para entender cómo fluye la información desde el Store hasta los componentes de React de manera eficiente.

## 🚀 Características del Proyecto

- **Global State Management:** Implementación de un estado centralizado y predecible.
- **Slice Pattern:** Organización de la lógica de estado, acciones y reducers en un solo lugar mediante `createSlice`.
- **Store Configuration:** Configuración simplificada del store con `configureStore`.
- **Hooks de React-Redux:** Uso de `useSelector` para extraer datos y `useDispatch` para disparar acciones.
- **Inmutabilidad Simplificada:** Aprovechamiento de la librería _Immer_ (integrada en RTK) para escribir lógica de mutación de forma segura.

---

## 🛠️ Stack Tecnológico

- **React:** Biblioteca principal para la UI.
- **Redux Toolkit:** El estándar oficial y eficiente para el desarrollo de Redux.
- **React-Redux:** La capa de unión oficial entre React y Redux.
- **CSS3:** Estilos para una interfaz clara y funcional.

---

## 📂 Contenido del Laboratorio

| Sección       | Concepto Clave                                              | Herramienta      |
| :------------ | :---------------------------------------------------------- | :--------------- |
| **Store**     | El "almacén" central de la verdad (Single Source of Truth). | `configureStore` |
| **Slices**    | Fragmentos de estado y lógica segmentada.                   | `createSlice`    |
| **Actions**   | Despachadores de eventos para modificar el estado.          | `useDispatch`    |
| **Selectors** | Lectura precisa de partes específicas del estado global.    | `useSelector`    |

---

## 🔧 Configuración Local

1.  **Clonar el repo:**

    ```bash
    git clone https://github.com/ignacioDorigo/react-redux-toolkit.git
    ```

2.  **Instalar las dependencias:**

    ```bash
    npm install
    ```

3.  **Lanzar el servidor de desarrollo:**
    ```bash
    npm run dev
    ```

---

## 💡 ¿Por qué Redux Toolkit?

> Tradicionalmente, Redux requería mucho código repetitivo (boilerplate). **Redux Toolkit** transforma esa experiencia, permitiendo configurar el store con una sola función y agrupar acciones y reducers en Slices, lo que hace que el código sea mucho más legible, mantenible y robusto.

---

## 👤 Autor

- **Ignacio Tomás Dorigo** - [GitHub](https://github.com/ignacioDorigo)

- **LinkedIn** - [LinkedIn](https://www.linkedin.com/in/ignacio-dorigo-3aa267203)
