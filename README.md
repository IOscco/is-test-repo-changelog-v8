# is-test-repo-changelog-v8

## Descripcion y proposito

Repositorio de prueba funcional **publico** con **80 archivos** (subset de mf-apex) para validar en Confluence DEMO:

- Escenario **A**: fallback GitHub 406 (diff ensamblado por `/files`)
- Escenario **B**: changelog LLM por capas, olas y consolidacion
- Sync de documentacion (README + paginas hijas en `docs/`)

Apunta a la pagina Confluence **Documentacion de Sistemas DEMO** (ID `732659714`).

## Repositorio

https://github.com/IOscco/is-test-repo-changelog-v8

## Estructura

```
is-test-repo-changelog-v8/
├── README.md
├── docs/                 # Sync a Confluence
├── src/                  # Codigo representativo (sin data/_raw ni poc JSON masivos)
├── .github/workflows/
└── vite.config.ts
```

## Jira

Prueba funcional: **JIRA-AI-970** / **JIRA-AI-1009**.

- **PR #1:** carga inicial 80 archivos (validacion Escenarios A + B)
