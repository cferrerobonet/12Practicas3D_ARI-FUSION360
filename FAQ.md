# Preguntas Frecuentes (FAQ) - Fusion 360

## 🔧 Instalación y Configuración

### ¿Es Fusion 360 gratuito?

**Para estudiantes y educadores**: Sí, Fusion 360 es completamente gratuito con una licencia educativa que se renueva anualmente.

**Para uso personal/hobby**: Autodesk ofrece una versión gratuita limitada para uso no comercial.

**Para uso comercial**: Requiere una suscripción de pago. Hay prueba gratuita de 30 días disponible.

### ¿Qué sistema operativo necesito?

Fusion 360 está disponible para:
- **Windows**: Windows 10 o posterior (64-bit)
- **macOS**: macOS Big Sur (11.0) o posterior

**Nota**: No hay versión nativa para Linux, pero puede funcionar mediante Wine o máquinas virtuales.

### ¿Puedo trabajar sin conexión a internet?

Fusion 360 requiere conexión a internet para:
- Verificación de licencia al inicio
- Guardar proyectos en la nube
- Sincronización de datos

Sin embargo, puedes trabajar sin conexión por períodos limitados (hasta 2 semanas) después de haber iniciado sesión con conexión.

### ¿Dónde se guardan mis archivos?

Los archivos se guardan en la **nube de Autodesk** por defecto. Esto permite:
- Acceso desde cualquier computadora
- Versionado automático
- Colaboración en tiempo real

También puedes exportar archivos localmente en formatos como .f3d, .step, .iges, etc.

## 📚 Aprendizaje y Uso

### ¿Cuánto tiempo lleva aprender Fusion 360?

- **Nivel básico**: 2-4 semanas de práctica regular
- **Nivel intermedio**: 2-3 meses
- **Nivel avanzado**: 6-12 meses

Completar las 12 prácticas de este repositorio te llevará aproximadamente **15-20 horas** y te dará una base sólida.

### ¿Necesito conocimientos previos de CAD?

No. Fusion 360 es accesible para principiantes. Sin embargo, ayuda tener:
- Comprensión básica de geometría
- Visión espacial 3D
- Familiaridad con software en general

### ¿Es mejor Fusion 360 que SolidWorks/Inventor/AutoCAD?

Cada software tiene sus fortalezas:

**Fusion 360**:
- ✅ Basado en la nube
- ✅ CAM integrado
- ✅ Colaboración fácil
- ✅ Más económico
- ❌ Menos potente para ensamblajes muy grandes

**SolidWorks/Inventor**:
- ✅ Más robusto para industria pesada
- ✅ Mejor para ensamblajes grandes
- ❌ Más costoso
- ❌ No basado en nube

**AutoCAD**:
- ✅ Estándar para dibujo 2D
- ❌ Menos intuitivo para 3D

### ¿Puedo usar Fusion 360 para impresión 3D?

¡Absolutamente! Fusion 360 es excelente para diseño de piezas para impresión 3D:
- Exporta directamente a STL, OBJ, 3MF
- Herramientas de análisis de mallas
- Vista previa de la pieza

## 💻 Rendimiento y Hardware

### Mi Fusion 360 va lento, ¿qué puedo hacer?

1. **Reducir calidad gráfica**: Preferences > Graphics > Performance
2. **Cerrar programas innecesarios**
3. **Actualizar drivers de GPU**
4. **Simplificar el modelo**: Ocultar componentes innecesarios
5. **Limpiar historial**: Hacer "Cleanup" del timeline cuando sea posible

### ¿Qué especificaciones de hardware recomiendan?

**Mínimo**:
- CPU: Intel Core i3 o equivalente
- RAM: 4 GB
- GPU: DirectX 11 compatible
- Disco: 3 GB libres

**Recomendado**:
- CPU: Intel Core i7 o AMD Ryzen 7
- RAM: 16 GB
- GPU: NVIDIA GTX 1060 o mejor
- Disco: SSD con 20 GB libres

**Óptimo** (para modelos complejos):
- CPU: Intel Core i9 o AMD Ryzen 9
- RAM: 32 GB
- GPU: NVIDIA RTX 3070 o mejor
- Disco: NVMe SSD

### ¿Necesito una GPU dedicada?

No es estrictamente necesario, pero es altamente recomendado:
- GPU integrada: Funciona para modelos simples
- GPU dedicada: Mejor experiencia, especialmente para renderizado

## 🔄 Archivos y Compatibilidad

### ¿Qué formatos puede importar/exportar Fusion 360?

**Importar**:
- .f3d (nativo de Fusion 360)
- .step, .stp (STEP)
- .iges, .igs (IGES)
- .sat (ACIS)
- .smt (Solid Edge)
- .3dm (Rhino)
- .stl, .obj (mallas)
- .dwg, .dxf (AutoCAD 2D)

**Exportar**:
- Todos los formatos de importación
- .stl (para impresión 3D)
- .fbx (para animación)
- .iam, .ipt (Inventor - solo suscripción)
- PDF de planos

### ¿Puedo abrir archivos de SolidWorks en Fusion 360?

Directamente no, pero puedes:
1. Exportar desde SolidWorks como .step o .iges
2. Importar ese archivo en Fusion 360

**Nota**: Se pierde el historial de diseño (features), solo importa la geometría.

### ¿Cómo comparto mis diseños con otros?

**Dentro de Fusion 360**:
- Compartir proyecto desde el Data Panel
- Invitar colaboradores
- Control de permisos (ver, editar, etc.)

**Fuera de Fusion 360**:
- Exportar a formatos universales (.step, .stl)
- Generar enlaces públicos para visualización
- Exportar renders o PDFs

## 🎨 Modelado y Diseño

### ¿Qué es mejor: modelado directo o paramétrico?

**Modelado Paramétrico** (Timeline activo):
- ✅ Historial editable
- ✅ Fácil hacer cambios
- ✅ Diseño por intención
- ❌ Puede ser más lento

**Modelado Directo** (Timeline desactivado):
- ✅ Más rápido
- ✅ Mejor para importaciones
- ❌ No hay historial
- ❌ Cambios más difíciles

**Recomendación**: Usa paramétrico para diseños propios, directo para editar importaciones.

### ¿Cómo evito que mi sketch esté "over-constrained"?

Over-constrained significa demasiadas restricciones conflictivas:

**Prevención**:
- Agrega restricciones gradualmente
- Verifica que el sketch sea azul (sub-constrained) antes de agregar más
- Usa "Show Constraints" para ver restricciones existentes
- Elimina restricciones redundantes

### ¿Cuál es la diferencia entre un Body y un Component?

**Body** (Cuerpo):
- Geometría simple
- Múltiples bodies pueden existir en un component
- No tiene su propia posición/orientación

**Component** (Componente):
- Contenedor de uno o más bodies
- Tiene su propia posición/orientación
- Se puede instanciar múltiples veces
- Mejor para ensamblajes

**Regla general**: Usa components para piezas separadas en un ensamblaje.

## 🔧 Problemas Comunes

### "Cannot create feature" - ¿Qué significa?

Este error común puede deberse a:
1. **Geometría inválida**: Sketch no cerrado o con intersecciones
2. **Operación imposible**: Intentar cortar más material del que existe
3. **Referencias perdidas**: Features anteriores fueron modificados

**Solución**: Revisa el sketch o feature problemático, verifica que sea válido.

### Mi modelo desapareció, ¿dónde está?

Posibles causas:
1. **Oculto**: Revisa el Browser, haz clic en el ícono de ojo
2. **Fuera de vista**: Presiona "F" para fit to screen
3. **Layer/Component oculto**: Revisa la estructura en el Browser

### ¿Por qué algunos comandos están en gris (deshabilitados)?

Comandos deshabilitados generalmente porque:
- No hay nada seleccionado
- Selección incorrecta (ej: necesitas una cara, seleccionaste una arista)
- No estás en el workspace correcto
- El comando no aplica al contexto actual

## 📱 Versión Móvil/Tablet

### ¿Hay versión móvil de Fusion 360?

Sí, hay aplicaciones para iOS y Android:
- **Visualización**: Ver y explorar modelos
- **Comentarios**: Agregar anotaciones
- **Edición limitada**: Algunos sketches y operaciones simples

No reemplaza la versión de escritorio, pero es útil para revisiones.

## 💰 Licencias y Costos

### Mi licencia educativa expiró, ¿qué hago?

1. Verifica que sigas siendo elegible (estudiante/educador)
2. Renueva tu licencia en la cuenta de Autodesk Education
3. Si ya no eres elegible, considera:
   - Versión gratuita para uso personal
   - Suscripción comercial
   - Alternativas gratuitas (FreeCAD, OnShape, etc.)

### ¿Puedo usar la licencia educativa para proyectos comerciales?

**No**. La licencia educativa es solo para:
- Aprendizaje
- Enseñanza
- Investigación académica

Para uso comercial necesitas una licencia comercial.

## 🎓 Certificación

### ¿Hay certificaciones oficiales de Fusion 360?

Sí, Autodesk ofrece:
- **Autodesk Certified User (ACU)**: Nivel básico
- **Autodesk Certified Professional (ACP)**: Nivel avanzado

Estas certificaciones:
- Validan tus habilidades
- Son reconocidas por empleadores
- Requieren examen (de pago)

---

## ❓ ¿No encontraste tu pregunta?

- Revisa los [Foros de Autodesk](https://forums.autodesk.com/t5/fusion-360/ct-p/1234)
- Consulta la [Ayuda oficial](https://help.autodesk.com/view/fusion360/)
- Pregunta en la comunidad de Reddit: r/Fusion360
- Abre un Issue en este repositorio

---

*Última actualización: Febrero 2026*
