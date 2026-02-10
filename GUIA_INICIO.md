# Guía de Inicio Rápido - Fusion 360

## Instalación de Fusion 360

### Para Estudiantes (Licencia Educativa Gratuita)

1. **Registrarse en Autodesk Education**
   - Visita: https://www.autodesk.com/education/edu-software/overview
   - Haz clic en "Get started"
   - Crea una cuenta con tu correo educativo (.edu, .ac, etc.)
   - Verifica tu estado de estudiante o educador

2. **Descargar Fusion 360**
   - Una vez verificado, busca "Fusion 360" en el catálogo
   - Selecciona la versión para tu sistema operativo
   - Descarga el instalador

3. **Instalar**
   - Ejecuta el instalador descargado
   - Sigue las instrucciones en pantalla
   - La instalación puede tomar 15-30 minutos

4. **Activar Licencia**
   - Inicia Fusion 360
   - Inicia sesión con tu cuenta de Autodesk Education
   - La licencia se activará automáticamente

### Para Uso Profesional

1. Visita: https://www.autodesk.com/products/fusion-360/overview
2. Selecciona un plan de suscripción
3. Completa el proceso de compra
4. Descarga e instala siguiendo las instrucciones

### Prueba Gratuita (30 días)

Puedes obtener una prueba gratuita de 30 días sin necesidad de ser estudiante:
1. Visita: https://www.autodesk.com/products/fusion-360/free-trial
2. Regístrate con tu correo electrónico
3. Descarga e instala

## Configuración Inicial

### Primera Ejecución

Al iniciar Fusion 360 por primera vez:

1. **Iniciar Sesión**
   - Ingresa tus credenciales de Autodesk
   - Acepta los términos de servicio

2. **Seleccionar Perfil**
   - **Design**: Para diseño mecánico (recomendado para empezar)
   - **Generative Design**: Para diseño generativo
   - **Electronics**: Para diseño de PCBs
   - Puedes cambiar esto después en Preferences

3. **Configurar Unidades**
   - Ve a Preferences (icono de engranaje o File > Preferences)
   - En "Default units", selecciona:
     - **Milímetros** (recomendado para la mayoría)
     - O el sistema que prefieras

4. **Configurar Preferencias**
   - **General**: Ajusta idioma si es necesario
   - **Graphics**: Ajusta calidad según tu hardware
   - **Design**: Configura comportamiento de herramientas

## Navegación Básica en Fusion 360

### Controles del Ratón

| Acción | Windows/Linux | macOS |
|--------|---------------|-------|
| **Orbit** (Rotar vista) | Clic medio | Shift + Clic medio |
| **Pan** (Desplazar vista) | Shift + Clic medio | Shift + Clic medio + drag |
| **Zoom** | Rueda del ratón | Rueda del ratón / Pinch |

### Atajos de Teclado Esenciales

| Atajo | Función |
|-------|---------|
| **S** | Mostrar/Ocultar menú de comandos |
| **Shift + S** | Buscar herramientas y comandos |
| **F** | Ajustar vista (Fit) |
| **Home** | Vista frontal |
| **Ctrl + Z** | Deshacer |
| **Ctrl + Y** | Rehacer |
| **Ctrl + S** | Guardar |
| **E** | Extrude |
| **L** | Line |
| **C** | Circle |
| **R** | Rectangle |
| **M** | Move |
| **P** | Press Pull |

### Interfaz Principal

```
┌─────────────────────────────────────────────────────────┐
│  [File] [Save] [Undo/Redo]    [Workspace]  [Profile]   │ Toolbar
├──────────┬──────────────────────────────────────────────┤
│          │                                              │
│ Browser  │         Vista 3D / Canvas                    │
│          │                                              │
│ Design   │                                              │
│ Tree     │    [ViewCube]                                │
│          │                                              │
│ Timeline │                                              │
│          │    [Navigation Bar]                          │
│          │                                              │
├──────────┴──────────────────────────────────────────────┤
│  Timeline ──────────────────────────────────────────►  │
└─────────────────────────────────────────────────────────┘
```

## Tu Primera Pieza en Fusion 360

### Ejercicio: Crear un Cubo Simple

1. **Crear un Sketch**
   - Haz clic en "Create Sketch"
   - Selecciona un plano (ejemplo: XY Plane)

2. **Dibujar un Rectángulo**
   - Presiona "R" o selecciona Rectangle
   - Haz clic para definir una esquina
   - Haz clic de nuevo para la esquina opuesta
   - Presiona "D" para dimensionar: 50mm x 50mm
   - Presiona ESC o "Finish Sketch"

3. **Extruir el Sketch**
   - Presiona "E" o selecciona Extrude
   - Ingresa 50mm de distancia
   - Presiona Enter o haz clic en OK

¡Felicidades! Has creado tu primera pieza 3D.

## Recursos de Aprendizaje

### Tutoriales Interactivos

Fusion 360 incluye tutoriales interactivos:
- Ve a Help > Interactive Learning
- Completa los tutoriales de "Getting Started"

### Documentación Oficial

- [Fusion 360 Help](https://help.autodesk.com/view/fusion360/)
- [Learning Paths](https://help.autodesk.com/view/fusion360/ENU/courses/)

### Comunidad

- [Foros de Autodesk](https://forums.autodesk.com/t5/fusion-360/ct-p/1234)
- [Galería de Diseños](https://gallery.autodesk.com/)
- [Blog de Fusion 360](https://www.autodesk.com/products/fusion-360/blog)

## Solución de Problemas Comunes

### Fusion 360 no inicia
- Verifica que tu conexión a internet esté activa
- Fusion 360 requiere conexión para verificar la licencia
- Reinicia tu computadora e intenta de nuevo

### El modelo se ve pixelado
- Ve a Preferences > Graphics
- Aumenta la calidad de renderizado
- Asegúrate de que los drivers de tu GPU estén actualizados

### Comandos lentos o lag
- Cierra otros programas que consuman muchos recursos
- Reduce la calidad gráfica en Preferences
- Considera actualizar tu hardware si es muy antiguo

### No puedo guardar mi proyecto
- Verifica tu conexión a internet
- Los proyectos se guardan en la nube de Autodesk
- Revisa que tengas espacio disponible en tu cuenta

## Próximos Pasos

1. Completa la configuración inicial
2. Practica la navegación 3D
3. Crea tu primera pieza siguiendo el ejercicio
4. Continúa con la [Práctica 01](../Practica01/README.md)

---

**¿Listo para comenzar?** Dirígete a la [Práctica 01](../Practica01/README.md) para iniciar tu viaje en el modelado 3D.
