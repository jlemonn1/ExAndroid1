# 🐾 **MOCK EXAM: Gestión de Animales en un Refugio**  

---

## **📚 Contexto**  
Este examen corresponde a la asignatura **Programación Multimedia para Dispositivos Móviles**. El objetivo es desarrollar una aplicación móvil en **Android Studio** para gestionar los animales que llegan a un refugio temporal.  

La aplicación permitirá registrar animales, actualizar su estado, visualizar la lista de registros y eliminar animales que ya no estén en el refugio. Todos los datos se gestionarán en memoria y no se utilizará persistencia en esta versión del sistema.  

---

## **📋 Requisitos del examen**  

### 1️⃣ **Necesidad del sistema**  
- **Registro de animales:**  
  Los animales deben ser registrados con los siguientes datos:  
  - Nombre 🐕  
  - Especie (gato, perro, otro) 🐾  
  - Estado inicial: "En revisión" 🛠️  

- **Gestión de estados:**  
  Los responsables deben poder cambiar el estado del animal a valores como:  
  - "En adopción" 🏡  
  - "Adoptado" 🎉  

- **Visualización:**  
  Debe existir un mecanismo para mostrar todos los animales registrados, con un máximo de 15 registros.  

- **Límites y validaciones:**  
  - Si se alcanza el límite de 15 animales, el sistema debe mostrar un aviso ⚠️.  
  - Los animales también pueden eliminarse del registro cuando ya no estén en el refugio.  

---

### 2️⃣ **Modelo de datos**  
El modelo se define con las siguientes propiedades:  
```java
public class Animal {
    private String nombre;  // Nombre del animal
    private String especie; // Especie (gato, perro, otro)
    private String estado;  // Estado actual (inicia como "En revisión")
}
```  
Los objetos se almacenarán en un `ArrayList<Animal>` y se realizarán operaciones para agregar, actualizar y eliminar animales.  

---

### 3️⃣ **Consideraciones técnicas**  
💡 **Buenas prácticas:**  
- Sigue la estructura estándar de Android Studio:  
  - **`activities:`** Para las pantallas principales.  
  - **`models:`** Para las clases del modelo (`Animal`).  
  - **`layouts:`** Archivos XML para diseñar las vistas.  
  - **`menu:`** Elementos de navegación como botones o íconos.  
  - **`drawable:`** Recursos gráficos como imágenes o íconos.  

- Utiliza **strings.xml** para textos reutilizables.  
- Diseña una interfaz fácil de usar y que permita una navegación intuitiva.  

---

## **💻 Tarea del estudiante**  

1. **✍️ Análisis del sistema:**  
   - Determina cuántas pantallas son necesarias para implementar las funcionalidades solicitadas.  
   - Describe brevemente la funcionalidad principal de cada pantalla.  

2. **🛠️ Diseño de la arquitectura:**  
   - Diseña el modelo de datos y la estructura del proyecto.  
   - Asegúrate de que todos los archivos estén correctamente ubicados en los directorios correspondientes.  

3. **👨‍💻 Implementación:**  
   - Crea la aplicación móvil en Android Studio.  
   - Integra todas las funcionalidades y asegúrate de que cumpla con los requisitos especificados.  

---

**🌟 ¡Buena suerte y que tu app sea un éxito!** 🚀
