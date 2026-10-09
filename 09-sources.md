[← К оглавлению](README.md)

# 9. Первоисточники


## Агентный SDLC и операционная модель

- Anthropic AI-native SDLC — разбор того, как смещается узкое место при агентной разработке: [freeCodeCamp: Agentic AI Engineering in Practice](https://www.freecodecamp.org/news/agentic-ai-engineering-in-practice-how-to-build-with-claude-code-codex-and-gemini/)
- Sonar — что такое agentic SDLC и отличие от AI-assisted: [What is Agentic SDLC](https://www.sonarsource.com/resources/library/what-is-agentic-sdlc/)
- Port — жизненный цикл, перестроенный вокруг агентов: [Agentic SDLC](https://www.port.io/blog/agentic-sdlc-software-lifecycle-rebuilt-around-agents)
- CodeRabbit — гайд по agentic SDLC: [A guide to the agentic SDLC](https://www.coderabbit.ai/guides/agentic-sdlc)
- DronaHQ — agentic SDLC в 2026, границы доверия агентам: [Agentic SDLC Guide](https://www.dronahq.com/agentic-sdlc-guide/)
- Atlan — агенты на каждом этапе SDLC: [AI Agents for SDLC](https://atlan.com/know/ai-agent/ai-agents-for-sdlc/)
- PwC — тиры зрелости GenAI в SDLC (Observer/Experimenter/Integrator/Pioneer): [Future of solutions dev and delivery (PDF)](https://www.pwc.com/m1/en/publications/2026/docs/future-of-solutions-dev-and-delivery-in-the-rise-of-gen-ai.pdf)
- dev.to — обзор agentic coding era: [The Agentic Coding Era Is Here](https://dev.to/monuminu/the-agentic-coding-era-is-here-how-autonomous-ai-coding-agents-are-rewriting-the-sdlc-5dpa)
- arXiv — исследование по агентам, меняющим узкое место доставки: [arXiv:2609.04681](https://arxiv.org/html/2609.04681v1)

## Harness engineering и контекст-инжиниринг

- Jama Software — harness engineering для агентных воркфлоу: [A Guide to Harness Engineering](https://www.jamasoftware.com/blog/harness-engineering/)
- Harness — spec/build/test/operate для агентных систем: [Engineering for the Agentic Era](https://www.harness.io/blog/engineering-for-the-agentic-era-how-to-spec-build-test-and-operate-ai-systems)
- Stack Builders — context engineering поверх AGENTS.md: [Beyond AGENTS.md](https://www.stackbuilders.com/insights/beyond-agentsmd-turning-ai-pair-programming-into-workflows/)
- Modern Agent Harness Blueprint 2026 (runtime, state, tools, approvals, observability): [GitHub Gist](https://gist.github.com/amazingvince/52158d00fb8b3ba1b8476bc62bb562e3)

## AGENTS.md и spec-driven development

- AGENTS.md — стандарт файла инструкций для агентов: [AGENTS.md](https://agents.md)
- BuildBetter — руководство по AGENTS.md для команд (2026): [AGENTS.md Complete Guide](https://blog.buildbetter.ai/agents-md-complete-guide-for-engineering-teams-in-2026/)
- Spec-driven development, полевое исследование: [agentic-engineering-field-study/04-spec-driven-development.md](https://github.com/ianhxu/agentic-engineering-field-study/blob/main/04-spec-driven-development.md)
- SDD с human-in-the-loop и runtime-диагностикой: [Medium / Dave Patten](https://medium.com/@dave-patten/spec-driven-development-with-ai-agents-from-build-to-runtime-diagnostics-415025fb1d62)
- 2026 AI Agent Playbook (SDD ≠ vibe coding): [Forasoft](https://www.forasoft.com/blog/article/spec-driven-agentic-engineering)

## Guardrails и безопасность

- Современные практики агентов (deterministic control flow, bounded tools, MCP, HITL, OpenTelemetry): [SKILL.md, awesome-omni-skill](https://github.com/diegosouzapw/awesome-omni-skill/blob/main/skills/data-ai/ai-agents-vasilyu1983/SKILL.md)
- OWASP Top 10 for LLM Applications: [owasp.org](https://owasp.org/www-project-top-10-for-large-language-model-applications/)

## vLLM и инференс

- vLLM — Tool Calling (стабильная документация, флаги `--enable-auto-tool-choice`, `--tool-call-parser`, `tool_choice`): [docs.vllm.ai (stable)](https://docs.vllm.ai/en/stable/features/tool_calling/)
- vLLM — Tool Calling (v0.10.1, named/auto/required/none): [docs.vllm.ai (v0.10.1)](https://docs.vllm.ai/en/v0.10.1/features/tool_calling.html)
- vLLM — унификация tool calling через guided decoding (RFC): [Issue #39848](https://github.com/vllm-project/vllm/issues/39848)
- vLLM — заметки по продакшн-serving Qwen (профили, VRAM): [vllm-qwen-launcher guide](https://github.com/pajitosingh/vllm-qwen-launcher/blob/main/VLLM-GUIDE.md)
- vLLM — day-0 поддержка новых моделей, long-context, квантизация: [vLLM blog](https://vllm.ai/blog/2026-07-27-k3)

## Open-weight модели для кодирования (сверять версии!)

- SSOJet — лучшие локальные LLM для кода (SWE-bench, self-hosting): [7 Best Local LLMs for Coding](https://ssojet.com/blog/best-local-llms-coding)
- Pinggy — self-hosted LLM для кода в 2026: [Best Open Source Self-Hosted LLMs](https://pinggy.io/blog/best_open_source_self_hosted_llms_for_coding/)
- Codersera — сравнение open-source моделей 2026 (лицензии, агентное кодирование): [Best Open Source LLM 2026](https://codersera.com/blog/best-open-source-llm-2026-llama-4-qwen-3-5-deepseek-v4-gemma-4-mistral/)
- Tembo — локальные LLM под VRAM: [Best Local LLM for Coding](https://www.tembo.io/blog/best-local-llm-for-coding)
- Overchat — рейтинг локальных кодеров 2026: [Best Local LLMs for Coding](https://overchat.ai/ai-hub/best-local-llm-for-coding)
- Hugging Face — open-weight модели для локального запуска: [Open-source LLM models to run locally](https://huggingface.co/blog/daya-shankar/open-source-llm-models-to-run-locally)
- You.com — выбор модели под автодополнение vs агентные задачи: [Best Local LLMs for Coding](https://you.com/resources/best-local-llm-for-coding)
- DigitalApplied — self-host open-weight модели под железо (SWE-bench 60–72%): [Best Open-Weight Coding Models](https://www.digitalapplied.com/blog/best-open-weight-coding-models-self-host-hardware-match-2026)

---

## Оговорка о версиях

Названия и показатели моделей (SWE-bench, размеры, лицензии) и флаги vLLM меняются быстро. В документах они приведены с пометкой «проверить». **Перед фиксацией в своём контуре:**

1. Сверьте точную версию vLLM и имена `--tool-call-parser` под выбранную модель.
2. Проверьте лицензию модели под ваш сценарий.
3. Прогоните модель на 3–5 реальных задачах вашего проекта (критерии приёмки — [документ 3, §3.5](03-agent-roles-and-models.md)).

---

[← К оглавлению](README.md)
