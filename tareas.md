# Archivo de tareas — SocialAI

Tareas generadas a partir de `readme.md` para planificar el desarrollo del proyecto.

## 1) Definición y preparación del proyecto

- [ ] Definir objetivos del MVP y criterios de éxito.
- [ ] Documentar alcance funcional de la primera versión.
- [ ] Crear repositorio base con estructura inicial (frontend/backend).
- [ ] Configurar flujo de trabajo (ramas, commits, convenciones).

## 2) Frontend (Flutter)

- [ ] Crear proyecto Flutter base.
- [ ] Implementar navegación principal entre pantallas:
  - [ ] Chat
  - [ ] Estado de ánimo (Mood)
  - [ ] Retos sociales (Challenges)
  - [ ] Perfil
- [ ] Diseñar e implementar componentes reutilizables:
  - [ ] `chat_message`
  - [ ] `mood_selector`
  - [ ] `challenge_card`
  - [ ] `notification_banner`
- [ ] Construir interfaz de chat con entrada de texto e historial.
- [ ] Construir pantalla para registrar estado de ánimo diario.
- [ ] Construir pantalla de retos diarios con acciones sugeridas.
- [ ] Construir pantalla de perfil básico de usuario.

## 3) Backend y Firebase

- [ ] Configurar proyecto Firebase.
- [ ] Configurar Firebase Auth para autenticación de usuarios.
- [ ] Configurar Firestore con colecciones iniciales:
  - [ ] usuarios
  - [ ] registros de estado de ánimo
  - [ ] retos
  - [ ] historial de chat
- [ ] Implementar servicios backend:
  - [ ] `user_service`
  - [ ] `mood_service`
  - [ ] `challenge_service`
  - [ ] `notification_service`

## 4) Módulos de IA

- [ ] Implementar módulo de detección de emociones desde texto.
- [ ] Definir y validar categorías emocionales:
  - [ ] happy
  - [ ] sad
  - [ ] lonely
  - [ ] anxious
  - [ ] neutral
  - [ ] stressed
- [ ] Implementar generador de respuestas empáticas considerando:
  - [ ] emoción detectada
  - [ ] historial de conversación
  - [ ] perfil del usuario
- [ ] Implementar generador de retos sociales según:
  - [ ] emoción detectada
  - [ ] actividad previa
  - [ ] nivel de dificultad
- [ ] Integrar LLM API con el backend.

## 5) Lógica de negocio

- [ ] Relacionar emoción detectada con estilo de respuesta del chat.
- [ ] Registrar y consultar historial emocional por usuario.
- [ ] Calcular tendencias y frecuencia de estados de ánimo.
- [ ] Evitar recomendaciones repetitivas en retos diarios.
- [ ] Definir reglas para progresión de dificultad de retos.

## 6) Notificaciones y engagement

- [ ] Integrar Firebase Cloud Messaging.
- [ ] Programar recordatorios de retos diarios.
- [ ] Programar check-ins emocionales.
- [ ] Añadir mensajes de apoyo y hábitos saludables.
- [ ] Permitir activar/desactivar notificaciones desde perfil.

## 7) Lineamientos de seguridad emocional (AI Behavior)

- [ ] Implementar validaciones para mantener tono:
  - [ ] empático
  - [ ] calmado
  - [ ] de apoyo
  - [ ] motivador
- [ ] Bloquear lenguaje manipulador o culpabilizante.
- [ ] Forzar recomendaciones que fomenten interacción humana real.
- [ ] Añadir regla explícita: no reemplazar relaciones humanas.

## 8) QA y pruebas

- [ ] Definir casos de prueba para cada módulo del MVP.
- [ ] Probar flujo completo: registro → chat → detección emocional → reto.
- [ ] Verificar persistencia de datos en Firestore.
- [ ] Probar funcionamiento de notificaciones en dispositivos reales.
- [ ] Realizar pruebas de usabilidad básicas.

## 9) Entrega MVP

- [ ] Preparar build de prueba interna.
- [ ] Documentar instalación y ejecución del proyecto.
- [ ] Documentar arquitectura mínima y decisiones técnicas.
- [ ] Publicar roadmap de mejoras post-MVP.
