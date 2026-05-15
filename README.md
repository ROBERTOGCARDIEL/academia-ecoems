# Academia ECOEMS 🎓

Plataforma de estudio para el examen ECOEMS (CCH UNAM e IPN) con IA narrativa y voz.

## Cómo publicar en Vercel (GRATIS, 5 minutos)

### Opción A — Sin instalar nada (más fácil):
1. Ve a **github.com** → crea cuenta gratis
2. Crea un repositorio nuevo llamado `academia-ecoems`
3. Sube estos 4 archivos: `index.html`, `api/claude.js`, `vercel.json`, `package.json`
4. Ve a **vercel.com** → "Sign up with GitHub"
5. Click en "Add New Project" → elige tu repositorio
6. En "Environment Variables" agrega:
   - Nombre: `ANTHROPIC_API_KEY`
   - Valor: tu API key de Anthropic
7. Click "Deploy"
8. ¡Listo! Vercel te da un link tipo `academia-ecoems.vercel.app`

### Opción B — Con Vercel CLI:
```bash
npm i -g vercel
vercel --prod
# Cuando pregunte por env variables, agrega ANTHROPIC_API_KEY
```

## Estructura del proyecto
```
academia-ecoems/
├── index.html          # La app completa
├── api/
│   └── claude.js       # Proxy seguro para la API de Claude
├── vercel.json         # Configuración de Vercel
└── package.json        # Metadatos del proyecto
```

## Características
- 🎓 9 materias del ECOEMS con teoría completa
- 🤖 IA narrativa (Claude) que explica cada tema
- 🔊 Voz en español (Text-to-Speech)
- 📝 Exámenes con retroalimentación de IA
- 📊 Progreso y análisis por materia
- 🧠 Técnicas de memoria y anti-nervios
- 👥 Multi-usuario con registro y contraseña
