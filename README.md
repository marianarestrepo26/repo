# MiniOS - Sistema Operativo Web

MiniOS es un prototipo de sistema operativo web desarrollado únicamente con HTML y CSS, sin utilizar JavaScript. Simula la experiencia de un sistema operativo básico con múltiples aplicaciones que se cargan dinámicamente mediante iframes.

## 🎯 Propósito del Proyecto

Este proyecto demuestra cómo crear interfaces de usuario complejas e interactivas utilizando únicamente tecnologías web fundamentales (HTML y CSS), sin depender de JavaScript para la funcionalidad básica. Es ideal para:

- Aprender los fundamentos del desarrollo web
- Comprender el poder de CSS moderno
- Practicar diseño responsive
- Explorar arquitecturas de aplicaciones modulares

## 📁 Estructura del Proyecto

```
mini-os/
├── index.html              # Interfaz principal del sistema
├── apps/                   # Directorio de aplicaciones
│   ├── notes.html         # Aplicación de notas
│   ├── homeworks.html     # Gestor de tareas
│   └── weather.html       # Centro meteorológico
├── styles/                 # Directorio de estilos
│   └── main.css           # Estilos principales del sistema
├── README.md              # Documentación del proyecto
└── package.json           # Configuración del proyecto
```

### Descripción de Componentes

#### 🖥️ **index.html** - Interfaz Principal
- Actúa como el "escritorio" del sistema operativo
- Contiene la barra de tareas superior
- Panel de navegación lateral con botones de aplicaciones
- Área principal donde se cargan las aplicaciones mediante iframes
- Sistema de navegación basado en radio buttons y CSS

#### 📱 **Aplicaciones (Directorio /apps/)**

1. **notes.html** - Aplicación de Notas
   - Gestión de notas personales
   - Categorización por tipo (personal, trabajo, estudio, etc.)
   - Sistema de prioridades (alta, media, baja)
   - Formulario para crear nuevas notas

2. **homeworks.html** - Gestor de Tareas
   - Control de tareas y actividades
   - Estados: pendiente, en progreso, completada, vencida
   - Barras de progreso visual
   - Estadísticas de productividad
   - Categorización por tipo de actividad

3. **weather.html** - Centro Meteorológico
   - Información climática actual
   - Pronóstico extendido de 7 días
   - Selector de ciudades colombianas
   - Alertas meteorológicas
   - Detalles completos (humedad, viento, presión, etc.)

#### 🎨 **styles/main.css** - Sistema de Diseño
- Grid Layout para la estructura principal
- Sistema de colores consistente
- Diseño responsive con breakpoints
- Animaciones y transiciones suaves
- Componentes reutilizables

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica y formularios
- **CSS3**: 
  - Grid Layout y Flexbox
  - Custom Properties (variables CSS)
  - Pseudo-selectores (:checked, :hover)
  - Media queries para responsive design
  - Gradientes y efectos visuales
  - Backdrop-filter para efectos de cristal

## 🚀 Cómo Visualizar el Proyecto

### Opción 1: Servidor de Desarrollo Local
```bash
# Si tienes Node.js instalado
npm install
npm run dev
```

### Opción 2: Servidor HTTP Simple
```bash
# Con Python 3
python -m http.server 8000

# Con Python 2
python -SimpleHTTPServer 8000

# Con Node.js (http-server)
npx http-server
```

### Opción 3: Abrir Directamente
Puedes abrir el archivo `index.html` directamente en tu navegador, aunque algunas funcionalidades de iframe pueden requerir un servidor HTTP.

## 🌐 Despliegue

### GitHub Pages
1. Sube el proyecto a un repositorio público en GitHub
2. Ve a Settings > Pages
3. Selecciona la rama principal como fuente
4. El sitio estará disponible en: `https://tu-usuario.github.io/mini-os`

### Netlify
1. Arrastra la carpeta del proyecto a [Netlify Drop](https://app.netlify.com/drop)
2. O conecta tu repositorio de GitHub para despliegue automático

## 📋 Navegación y Uso

### Navegación Principal
- **Radio Buttons**: Utiliza los botones en el panel lateral para cambiar entre aplicaciones
- **Responsive**: El diseño se adapta automáticamente a diferentes tamaños de pantalla
- **Iframes**: Cada aplicación se carga en un iframe independiente

### Funcionalidades por Aplicación

#### Notas
- Completa formularios para crear notas
- Selecciona categorías y prioridades
- Visualiza notas existentes con diferentes estados visuales

#### Tareas
- Revisa estadísticas de productividad
- Crea nuevas tareas con fechas límite
- Monitorea el progreso visual de actividades

#### Clima
- Cambia entre diferentes ciudades
- Consulta pronósticos extendidos
- Revisa alertas meteorológicas

## 🎨 Características de Diseño

### Sistema de Colores
- **Primario**: Azul (#3498db)
- **Secundario**: Verde (#27ae60)
- **Acento**: Naranja (#f39c12)
- **Peligro**: Rojo (#e74c3c)
- **Neutros**: Grises variados

### Responsive Design
- **Mobile**: < 768px (diseño vertical)
- **Tablet**: 768px - 1024px (diseño híbrido)
- **Desktop**: > 1024px (diseño completo)

### Efectos Visuales
- Gradientes de fondo
- Sombras suaves
- Transiciones animadas
- Efectos de hover
- Backdrop filters

## 🔧 Personalización

### Agregar Nuevas Aplicaciones
1. Crea un nuevo archivo HTML en `/apps/`
2. Agrega un radio button en `index.html`
3. Crea el iframe correspondiente
4. Agrega las reglas CSS para mostrar/ocultar

### Modificar Estilos
- Edita `/styles/main.css` para cambios globales
- Modifica estilos inline en aplicaciones específicas
- Utiliza CSS custom properties para cambios de tema

## 📊 Gestión del Proyecto

### Azure DevOps
- Tareas organizadas por sprints
- Seguimiento de progreso individual
- Documentación de decisiones técnicas
- Control de versiones integrado

### Estructura de Tareas
1. **Diseño de Arquitectura**
2. **Desarrollo de Interfaz Principal**
3. **Creación de Aplicaciones**
4. **Implementación de Estilos**
5. **Testing y Optimización**
6. **Documentación y Despliegue**

## 🎓 Aprendizajes Clave

### Técnicos
- Uso avanzado de selectores CSS
- Arquitectura de aplicaciones modulares
- Diseño responsive sin frameworks
- Gestión de estado con CSS puro

### Metodológicos
- Planificación de proyectos
- Documentación técnica
- Control de versiones
- Trabajo en equipo

## 🚀 Futuras Mejoras

- [ ] Más aplicaciones (calculadora, editor de texto)
- [ ] Temas personalizables
- [ ] Mejores animaciones
- [ ] Accesibilidad mejorada
- [ ] PWA capabilities

## 👥 Contribuidores

Este proyecto fue desarrollado como parte de un ejercicio académico en desarrollo web frontend, demostrando que es posible crear experiencias de usuario ricas utilizando únicamente HTML y CSS.

## 📄 Licencia

Este proyecto es de código abierto y está disponible bajo la Licencia MIT.

---

**MiniOS v1.0** - Sistema Operativo Web | Desarrollado con ❤️ usando solo HTML y CSS