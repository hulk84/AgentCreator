# 🤖 AgentCreator - Sistema Maestro de Creación de Agentes

## Descripción
AgentCreator es un agente especializado en diseñar, desarrollar y desplegar agentes de IA autónomos para Claude Code. Sigue las mejores prácticas de la industria e implementa un protocolo estricto de desarrollo.

## Estructura del Sistema

```
AgentCreator/
├── CLAUDE.md              # Instrucciones maestras del creador
├── memory.json            # Memoria persistente del sistema
├── knowledge_base.json    # Base de conocimiento sobre creación de agentes
├── project_PRD_template.md # Plantilla para gestión de proyectos
├── README.md              # Este archivo
└── tools/                 # Herramientas paralelizables
    ├── analyze_requirements.md
    ├── create_agent_structure.md
    └── validate_agent.md
```

## Capacidades Principales

### 1. Creación Estructurada de Agentes
- Análisis de requisitos
- Diseño de arquitectura
- Generación de instrucciones
- Configuración de memoria
- Desarrollo de herramientas

### 2. Arquitecturas Soportadas
- **Single Agent + Tools**: Para tareas específicas
- **Multi-Agent Systems**: Para procesos complejos
- **Hierarchical Agents**: Para sistemas con jerarquías
- **Pipeline Agents**: Para flujos secuenciales

### 3. Componentes que Genera
- `CLAUDE.md`: Instrucciones completas del agente
- `memory.json`: Sistema de memoria persistente
- `knowledge_base.json`: Base de conocimiento del dominio
- `tools/`: Herramientas específicas del agente
- `project_PRD.md`: Documento de requisitos y seguimiento

## Cómo Usar AgentCreator

### Inicio Rápido
1. **Describir el agente deseado**: "Necesito un agente que [descripción]"
2. **AgentCreator analizará** los requisitos y propondrá una arquitectura
3. **Revisión del PRD**: Se creará un documento de requisitos para aprobación
4. **Desarrollo**: AgentCreator creará toda la estructura del agente
5. **Validación**: El agente será validado antes de entrega

### Comandos Principales
- `/analyze [requisitos]`: Analiza requisitos y propone solución
- `/create [nombre_agente]`: Crea estructura completa del agente
- `/validate [ruta_agente]`: Valida un agente existente
- `/improve [ruta_agente]`: Sugiere mejoras para un agente

## Proceso de Trabajo

### 1. Análisis (Tool: analyze_requirements)
```
Input: Descripción del usuario
Output: Especificaciones detalladas y arquitectura recomendada
```

### 2. Creación (Tool: create_agent_structure)
```
Input: Especificaciones aprobadas
Output: Estructura completa del agente con todos los archivos
```

### 3. Validación (Tool: validate_agent)
```
Input: Agente creado
Output: Reporte de validación con score y recomendaciones
```

## Mejores Prácticas Implementadas

### Desarrollo
- ✅ No parches temporales
- ✅ Tests antes de implementar
- ✅ Código limpio y documentado
- ✅ Seguridad desde el diseño

### Memoria
- ✅ Persistencia entre sesiones
- ✅ Solo información accionable
- ✅ Actualización automática
- ✅ Estructura optimizada

### Documentación
- ✅ Instrucciones claras y concisas
- ✅ Ejemplos de uso
- ✅ Limitaciones explícitas
- ✅ Métricas de éxito

## Integración Multi-Agente

AgentCreator puede coordinar con otros agentes:
```
"Trabaja con el agente FinancialAnalyst en /ruta/FinancialAnalyst 
para crear un agente de reportes que use sus análisis"
```

## Métricas de Calidad

Cada agente creado debe cumplir:
- 📊 Score de validación > 95%
- ⚡ Tiempo de respuesta < 500ms
- ✅ Tasa de éxito > 90%
- 🔒 Sin vulnerabilidades de seguridad

## Actualización Continua

AgentCreator mejora constantemente:
1. Aprende de cada agente creado
2. Actualiza su knowledge_base con nuevos patrones
3. Refina sus herramientas basándose en feedback
4. Propone actualizaciones a sus propias instrucciones

## Soporte y Contacto

Para reportar problemas o sugerir mejoras:
- Actualizar el memory.json con feedback
- Proponer cambios en CLAUDE.md
- Agregar nuevas herramientas en /tools/

---
*AgentCreator v1.0 - Creando el futuro, un agente a la vez*