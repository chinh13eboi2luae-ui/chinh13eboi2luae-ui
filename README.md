# LE DUC MANH

**LLM integrations · Developer automation · Open source**

I build tools that connect language-model APIs with practical developer workflows. My current work focuses on API gateways, automated issue investigation, and reproducible testing.

Based in Ho Chi Minh City, Vietnam.

## Current work

### LLM API Gateway

A Node.js and TypeScript gateway with OpenAI-compatible and Anthropic-compatible interfaces, streaming responses, request queues, concurrency controls, and tool-call translation.

### OSS AI Runner

A Python runner for finding suitable issues, reproducing bugs, validating patches in Docker, and maintaining pull requests. The workflow includes task-based model routing, independent behavioral checks, and explicit test evidence.

[Explore the public workflow demo →](https://github.com/chinh13eboi2luae-ui/oss-ai-runner-demo)

## Selected open-source contributions

These pull requests document the proposed changes, reproduction cases, and local validation.

| Project | Proposed change |
| --- | --- |
| [Oribi](https://github.com/samhoon000/Oribi/pull/115) | Display empty column names clearly in Markdown reports. |
| [sqlite-utils](https://github.com/simonw/sqlite-utils/pull/959) | Preserve already-nullable columns when changing `NOT NULL` constraints. |

## Technical focus

| Area | Tools and technologies |
| --- | --- |
| API integrations | Node.js, TypeScript, REST, streaming SSE, WebSocket |
| Developer automation | Python, Git, GitHub API |
| Verification | Docker, pytest, Ruff, mypy |
| Deployment | Ubuntu, Nginx, Windows runners |

## How I work

- Reproduce the reported behavior before changing code.
- Keep patches focused and add regression coverage.
- Run behavioral checks alongside the project's tests and static checks.
- Document validation scope, remaining limitations, and AI assistance.

For project questions or collaboration, use the issue tracker in the relevant repository.
