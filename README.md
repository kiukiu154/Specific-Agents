# Specific multiagents (Español / English)

Sistema multiagente con enrutamiento automático / Multi-agent system with automatic routing.

![Estado: activo](<BADGE_ESTADO>) ![Licencia: MIT](<BADGE_LICENCIA>)

## Índice / Table of contents

- [Español](#español)
  - [Contenido](#contenido)
  - [Uso](#uso)
  - [Seguridad](#seguridad)
  - [Licencia](#licencia)
  - [Contribuir](#contribuir)
- [English](#english)
  - [Contents](#contents)
  - [Usage](#usage)
  - [Security](#security)
  - [License](#license)
  - [Contributing](#contributing)

## Español

Sistema multiagente con enrutamiento automático: un coordinador clasifica cada petición y la deriva al agente temático correspondiente.

### Contenido

- `.opencode/agents/` — agentes del sistema (coordinator, planner, implementer, reviewer, cybersecurity, start).
- `specific-agents/` — 13 agentes temáticos (financiero, videojuegos, leyes, software, medicina, logística, arte, escritura, mejorador-prompt, ciencia, historia, marketing, productividad).
- `MEMORY.md` — memoria del proyecto.

### Uso

1. Clona el repositorio: `git clone https://github.com/kiukiu154/Specific-Agents`
2. Abre la carpeta en tu herramienta con OpenCode.
3. El agente `start` verifica el estado y el `coordinator` enruta tu petición al agente temático adecuado.

### Seguridad

Si encuentras una vulnerabilidad, consulta la política en [SECURITY.md](SECURITY.md) y no la divulgues públicamente hasta su resolución.

### Licencia

MIT — ver [LICENSE](LICENSE).

### Contribuir

Abre un issue o pull request en el repositorio (`https://github.com/kiukiu154/Specific-Agents`) describiendo el cambio propuesto.

---

## English

Multi-agent system with automatic routing: a coordinator classifies each request and forwards it to the matching topic-specific agent.

### Contents

- `.opencode/agents/` — system agents (coordinator, planner, implementer, reviewer, cybersecurity, start).
- `specific-agents/` — 13 topic-specific multi-agent definitions (financiero, videojuegos, leyes, software, medicina, logistica, arte, escritura, mejorador-prompt, ciencia, historia, marketing, productividad).
- `MEMORY.md` — project memory.

### Usage

1. Clone the repository: `git clone https://github.com/kiukiu154/Specific-Agents`
2. Open the folder in your OpenCode-enabled tool.
3. The `start` agent checks the status and the `coordinator` routes your request to the right topic agent.

### Security

If you find a vulnerability, please follow the policy in [SECURITY.md](SECURITY.md) and do not disclose it publicly until it is resolved.

### License

MIT — see [LICENSE](LICENSE).

### Contributing

Open an issue or pull request in the repository (`https://github.com/kiukiu154/Specific-Agents`) describing the proposed change.
