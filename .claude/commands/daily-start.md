---
description: Initialize daily routine with note creation and priority setting
allowed-tools: Read, Write, Edit, LS, Bash
---

# Daily Start

Inicia el día de manera estructurada creando la nota diaria y actualizando las prioridades del día.

## Usage
Ejecuta este comando cada mañana para:
- Crear nota diaria con fecha actual
- Revisar y actualizar tareas del día anterior
- Establecer prioridades del día
- Aplicar framework PLG al planning diario

## Daily Start Protocol

### Step 1: Create Daily Note
```
1. Crear nota en 00_inbox/ con formato YYYY-MM-DD.md
2. Usar template con metadata completo (type, date, day, week, tags)
3. Incluir sections: Resumen ayer, Prioridades hoy, Horario, Estado proyectos
4. Agregar intención del día y framework integration
```

### Step 2: Review Previous Day Progress  
```
1. Leer nota del día anterior en 00_inbox/
2. Identificar qué se logró vs qué quedó pendiente
3. Documentar blockers y learnings del día anterior
4. Evaluar progreso en proyectos activos desde última review
```

### Step 3: Update TODO.md with Daily Context
```
1. Abrir 📝 TODO.md principal
2. Actualizar prioridades críticas del día
3. Refinar tareas basado en progreso del día anterior
4. Integrar PLG framework morning practice (10 min scheduled)
5. Marcar deadlines críticos (ej: Elestio Credits)
```

### Step 4: Framework Integration
```
- Add morning PLG practice (10 min)
- Schedule evening review (10 min)
- Identify framework application opportunities
- Set daily insight generation goal
```

## Daily Note Template Structure

### Metadata Section
```yaml
---
type: daily
date: YYYY-MM-DD
day: [día de la semana]
week: YYYY-WXX
tags: [daily, planning, relevant-tags]
---
```

### Content Sections
1. **Resumen de Ayer** - Logros y blockers del día anterior
2. **Prioridades del Día** - Top 3 críticas + secundarias
3. **Horario Sugerido** - Time blocking para deep work
4. **Estado de Proyectos** - Semáforo con progreso tracking
5. **Notas del Día** - Capture during day
6. **Intención del Día** - Theme/focus statement
7. **Resumen EOD** - End of day review

### PLG Framework Integration
- **Morning Practice**: Industry truth mining (10 min)
- **Daily Application**: Apply framework to active projects
- **Evening Review**: Document insights and learnings
- **Weekly Connection**: Link to weekly PLG sprint goals

## Project Status Integration

### Active Projects Tracking
- Dojo Coding Projects (4 sub-projects)
- AI Agents Development
- Indie Mind Content
- Client work status

### Success Metrics
- Project completion percentages
- Framework insights generated
- Client deliverable status
- Learning goals progress

## Automation Triggers

### Morning Routine (First 30 min)
1. Run /daily-start command
2. Review created daily note
3. Update TODO.md with day priorities
4. Execute framework morning practice
5. Time block calendar for day

### Integration Points
- Link to weekly planning system
- Connect with project management
- Integrate PLG framework practices
- Maintain second brain consistency

## Success Patterns

### High-Impact Daily Starts
- Clear top 3 priorities identified
- Framework practice scheduled
- Previous day properly reviewed
- Day structured for deep work

### Framework Application
- Morning insight generation
- Project-specific contrarian thinking
- Client work through PLG lens
- Evening validation and review

## Quick Commands Integration

### Related Commands
- `/framework-transformer` - For content-to-insight work
- `/neural-review` - For knowledge consolidation
- `/cognitive-amplification` - For complex problem solving

### Daily Workflow
```
Morning: /daily-start → Framework practice → Deep work
Evening: Review note → Update progress → Plan tomorrow
```

---

**Purpose**: Structured daily beginning with framework integration  
**Frequency**: Every morning  
**Time required**: 10-15 minutes setup + framework practice

*Optimized for consistent daily practice and compound productivity growth*