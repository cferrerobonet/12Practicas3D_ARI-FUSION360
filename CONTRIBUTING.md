# Cómo Contribuir al Proyecto

¡Gracias por tu interés en contribuir a la colección de prácticas de Fusion 360! Este documento proporciona lineamientos para contribuir al proyecto.

## 🌟 Formas de Contribuir

Hay muchas formas de contribuir a este proyecto:

1. **Reportar errores** en la documentación o ejercicios
2. **Sugerir mejoras** en las prácticas existentes
3. **Agregar nuevos recursos** útiles
4. **Mejorar la traducción** o claridad del contenido
5. **Crear contenido adicional** (tutoriales, ejemplos, etc.)
6. **Compartir tus proyectos** realizados con estas prácticas

## 📋 Antes de Contribuir

### Revisa lo Existente

- Busca en los [Issues existentes](https://github.com/cferrerobonet/12Practicas3D_ARI-FUSION360/issues) para evitar duplicados
- Lee la documentación actual para entender el estilo y estructura

### Código de Conducta

- Sé respetuoso y constructivo
- Acepta críticas constructivas
- Enfócate en lo mejor para la comunidad de aprendizaje
- Usa lenguaje inclusivo y profesional

## 🔧 Proceso de Contribución

### 1. Fork del Repositorio

```bash
# Haz clic en el botón "Fork" en GitHub
# Luego clona tu fork
git clone https://github.com/TU-USUARIO/12Practicas3D_ARI-FUSION360.git
cd 12Practicas3D_ARI-FUSION360
```

### 2. Crea una Rama

```bash
# Crea una rama descriptiva para tu contribución
git checkout -b feature/nombre-descriptivo
# o
git checkout -b fix/descripcion-del-error
```

### 3. Realiza tus Cambios

**Para documentación:**
- Mantén el formato Markdown consistente
- Usa encabezados apropiados (H1, H2, H3)
- Incluye ejemplos cuando sea posible
- Revisa ortografía y gramática

**Para nuevas prácticas:**
- Sigue la estructura de prácticas existentes
- Incluye: objetivo, descripción, contenido, ejercicios, tiempo estimado
- Usa lenguaje claro y pedagógico
- Proporciona recursos adicionales

**Para recursos/enlaces:**
- Verifica que los enlaces funcionen
- Proporciona descripción breve
- Organiza en categorías apropiadas

### 4. Commit de tus Cambios

```bash
# Agrega los archivos modificados
git add .

# Crea un commit con mensaje descriptivo
git commit -m "tipo: descripción breve del cambio"
```

**Tipos de commit:**
- `docs:` Cambios en documentación
- `feat:` Nueva característica o práctica
- `fix:` Corrección de error
- `style:` Cambios de formato (sin cambiar contenido)
- `refactor:` Reorganización de contenido
- `test:` Agregar o actualizar ejercicios de prueba

**Ejemplos:**
```
docs: corregir ortografía en Práctica 03
feat: agregar nueva práctica sobre renderizado avanzado
fix: corregir enlaces rotos en RECURSOS.md
```

### 5. Push a tu Fork

```bash
git push origin feature/nombre-descriptivo
```

### 6. Crear Pull Request

1. Ve a tu fork en GitHub
2. Haz clic en "New Pull Request"
3. Selecciona tu rama
4. Completa la descripción del PR:
   - ¿Qué cambia este PR?
   - ¿Por qué es necesario?
   - ¿Cómo se prueba?
5. Envía el PR

## 📝 Lineamientos de Estilo

### Markdown

```markdown
# H1 para títulos principales (solo uno por archivo)
## H2 para secciones principales
### H3 para subsecciones

- Listas con guiones
- Usa líneas en blanco entre secciones

**Negrita** para énfasis importante
*Cursiva* para énfasis leve

`código` para comandos o código inline

\`\`\`
bloques de código
para múltiples líneas
\`\`\`
```

### Lenguaje

- Usa **español** para todo el contenido principal
- Mantén términos técnicos en inglés cuando sea apropiado (ej: "Extrude", "Sketch")
- Explica acrónimos la primera vez que se usan: "CAD (Computer-Aided Design)"
- Usa lenguaje claro y directo
- Evita jerga innecesaria

### Formato de Prácticas

Cada práctica debe seguir esta estructura:

```markdown
# Práctica XX: Título Descriptivo

## Objetivo
[Una o dos oraciones claras sobre el objetivo]

## Descripción
[Párrafo descriptivo del contenido]

## Contenido de la Práctica

### 1. Sección Principal
- Punto 1
- Punto 2

### 2. Otra Sección
...

## Ejercicios
1. Ejercicio específico
2. Otro ejercicio

## Archivos
- `archivo1.f3d`: Descripción
- `archivo2.pdf`: Descripción

## Tiempo Estimado
XX minutos
```

## 🐛 Reportar Errores

Cuando reportes un error, incluye:

1. **Título claro** del problema
2. **Descripción detallada** del error
3. **Pasos para reproducir** (si aplica)
4. **Comportamiento esperado**
5. **Screenshots** si es relevante
6. **Contexto adicional**

### Ejemplo de Issue de Error

```markdown
**Título:** Enlace roto en Práctica 05

**Descripción:**
El enlace a la documentación oficial en la Práctica 05 
está roto y lleva a una página 404.

**Ubicación:**
- Archivo: `Practica05/README.md`
- Línea: ~45

**Enlace actual:**
https://help.autodesk.com/view/fusion360/ENLACE-VIEJO

**Sugerencia:**
Actualizar a: https://help.autodesk.com/view/fusion360/ENLACE-NUEVO
```

## 💡 Sugerir Mejoras

Para sugerir mejoras:

1. Abre un Issue con etiqueta "enhancement"
2. Describe claramente la mejora propuesta
3. Explica por qué sería beneficiosa
4. Si es posible, proporciona ejemplos

## 🎓 Agregar Nuevas Prácticas

Si deseas agregar una práctica completamente nueva:

1. **Consulta primero** abriendo un Issue para discutir
2. Asegúrate de que complemente las prácticas existentes
3. Mantén el nivel de dificultad progresivo
4. Proporciona ejercicios prácticos
5. Incluye estimación de tiempo realista

## 🔍 Proceso de Revisión

### Qué Esperamos

- Revisaremos los PRs en un plazo razonable
- Podemos solicitar cambios o aclaraciones
- Mantendremos comunicación respetuosa
- Reconoceremos todas las contribuciones

### Criterios de Aceptación

Un PR será aceptado si:
- Sigue los lineamientos de este documento
- Mantiene la calidad del contenido existente
- Es pedagógicamente útil
- No contiene errores obvios
- Está escrito en español correcto

## 📜 Licencia

Al contribuir, aceptas que tu contribución será licenciada bajo Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0).

## 🙏 Reconocimiento

Todos los contribuidores serán reconocidos en:
- Sección de agradecimientos del README
- Historial de commits de Git
- Release notes cuando aplique

## 📧 Preguntas

Si tienes preguntas sobre cómo contribuir:

1. Revisa este documento completo
2. Busca en Issues existentes
3. Abre un nuevo Issue con etiqueta "question"

---

## Lista de Verificación para PRs

Antes de enviar tu Pull Request, verifica:

- [ ] He leído y seguido las guías de contribución
- [ ] Mi código/documentación sigue el estilo del proyecto
- [ ] He revisado ortografía y gramática
- [ ] He probado los enlaces (si aplica)
- [ ] He agregado descripción clara en el PR
- [ ] Mi commit tiene un mensaje descriptivo
- [ ] He actualizado documentación relacionada (si aplica)

---

**¡Gracias por contribuir al proyecto! Cada contribución ayuda a que más personas aprendan Fusion 360. 🚀**
