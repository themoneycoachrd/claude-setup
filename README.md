# Usa Claude mejor que el 99% de las personas

Guía interactiva para configurar Claude Cowork como asistente personal en una mañana. Pensada para gerentes y CFOs que quieren pasar de chatear con IA a usarla como sistema de trabajo.

## Qué es esto

Una página web (HTML standalone) que te lleva paso a paso desde "nunca he usado Claude" a tener un asistente configurado que sabe quién eres, recuerda lo que hacen juntos, se conecta a tus herramientas, y trabaja mientras duermes.

Incluye dos caminos:
- **Express** — Instalas un skill y Claude te guía. 20 minutos.
- **Paso a paso** — Te explico cada paso y tú lo haces. 1 hora.

## Basado en

- El video ["Set Up Claude Cowork better than 99% of people"](https://www.youtube.com/watch?v=pl90LATQlHI) de Simon (Better Creating)
- 30 días de uso real configurando Claude Cowork para una firma de contabilidad en República Dominicana

## Estructura

```
/
├── README.md
├── pages/
│   └── guia-setup.html          ← La guía interactiva (HTML standalone)
├── skills/
│   └── mi-setup-claude.skill    ← Skill descargable para configurar Claude
└── assets/
    └── (imágenes y recursos)
```

## Cómo usar

1. Abre `pages/guia-setup.html` en tu navegador
2. Elige tu camino (Express o Paso a paso)
3. Sigue las instrucciones

## Hosting

Desplegado en Vercel. Cada push a `main` publica automáticamente.

## Autor

Felix Rosa · [The Money Coach](https://www.instagram.com/themoneycoachrd/) · 2026
