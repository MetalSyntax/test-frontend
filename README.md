
# **WorldsAcross Test Frontend Ionic Angular**

Esta aplicación está diseñada para proporcionar una experiencia fluida en la gestión de reservas, estudiantes y tutores, con características como filtrado, actualización al deslizar y navegación basada en gestos.

---

## **Características**

### **Funcionalidad Principal**
- **Gestionar Reservas**: Ver, filtrar y actualizar dinámicamente los datos de reservas.
- **Gestión de Estudiantes**: Navegar y seleccionar estudiantes con una interfaz limpia y fácil de usar.
- **Gestión de Tutores**: Filtrar tutores según especialidades y cargar dinámicamente más resultados.

### **Características Interactivas**
- **Actualizar al Deslizar**: Permite a los usuarios actualizar los datos al deslizar hacia abajo.
- **Manejo de Errores**: Muestra mensajes de error amigables cuando las llamadas API fallan.
- **Formularios Reactivos**: Valida las entradas del usuario con retroalimentación visual.

---

## **Requisitos Previos**

Asegúrate de tener lo siguiente instalado en tu sistema:

1. **Node.js** (v20.11.1): [Descargar Node.js](https://nodejs.org/)
2. **Angular CLI** (v19): Instalar mediante npm:
   ```bash
   npm install -g @angular/cli@19
   ```
3. **Capacitor CLI** (v7): Instalar mediante npm:
   ```bash
   npm install -g @capacitor/cli@7
   ```

---

## **Comenzando**

### **Clonar el Repositorio**

```bash
git clone https://github.com/your-repository/ionic-angular-project.git
cd ionic-angular-project
```

### **Instalar Dependencias**

Ejecuta el siguiente comando para instalar todas las dependencias necesarias:

```bash
npm install
```

### **Servir la Aplicación**

Para ejecutar la aplicación en un entorno de desarrollo:

```bash
npm run ng serve
```

La aplicación será accesible en `http://localhost:4200` en tu navegador.

---

## **Construcción de la Aplicación**

### **Para la Web**

Para construir la aplicación para su despliegue:

```bash
npm run ng build --prod
```

---

## **Estructura del Proyecto**

### **Páginas**
- **ClassesPage**: Muestra y filtra los datos de las reservas, admite actualización al deslizar y paginación.
- **TutorsPage**: Muestra los datos de los tutores con filtrado por especialidad y un botón de "Cargar más".
- **StudentPage**: Permite seleccionar estudiantes individuales y admite navegación basada en gestos.

### **Servicios**
- **ApiService**: Maneja todas las llamadas API e incluye manejo de errores para una experiencia de usuario fluida.

---

## **Scripts**

### **Servidor de Desarrollo**
Ejecuta la aplicación localmente:
```bash
npm run ng serve
```

### **Construir para Producción**
Optimiza la app para producción:
```bash
npm run ng build --prod
```

---

## **Notas Adicionales**

### **Endpoints de API**

- **URL**: `https://test.worldsacross.com/api`
- **Tutores**: `/tutors`
- **Usuarios (Estudiantes)**: `/users`
- **Reservas**: `/booking`

---

## **Solución de Problemas**

### **Problemas Comunes**
1. **Dependencias Faltantes**: Ejecuta `npm install` para asegurarte de que todas las dependencias estén instaladas.
2. **Errores de Capacitor**: Ejecuta `npx cap sync` para sincronizar las configuraciones de las plataformas nativas.

### **Contacto**
Si encuentras algún problema, no dudes en ponerte en contacto a través de [GitHub Issues](https://github.com/your-repository/issues).

---

## **Licencia**

Este proyecto está bajo la licencia [MIT License](LICENSE).

---