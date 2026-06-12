# recursos-anfaia

Recursos recomendados para desarrolladores, con un fuerte énfasis en **open source** y en las novedades más relevantes de IA, agentes y desarrollo moderno.

> Convención: las herramientas marcadas como **(open source)** publican su código bajo licencia libre (Apache 2.0, MIT, AGPL, GPL, BSD…). Las marcadas como **(open weights)** liberan pesos pero no necesariamente datos o código de entrenamiento.

---

## 🤖 Asistentes de IA (Chat)

- [**ChatGPT**](https://chatgpt.com/) - Asistente conversacional de OpenAI. Versátil para generar texto, programar, resumir y crear contenido.
- [**Claude**](https://claude.ai/) - Asistente de Anthropic. Destaca en documentos largos, razonamiento, escritura y análisis empresarial.
- [**Gemini**](https://gemini.google.com/) - Asistente de Google integrado con su ecosistema (Workspace, Android, búsqueda).
- [**Perplexity**](https://www.perplexity.ai/) - Buscador conversacional con citas y fuentes. Ideal para investigar y contrastar información actualizada.
- [**DeepSeek**](https://chat.deepseek.com/) - Chat de DeepSeek con su familia V4 (Pro y Flash, razonamiento integrado). Enfoque técnico, matemático y de programación.
- [**Mistral Le Chat**](https://chat.mistral.ai/chat) - Chat de Mistral AI con modelos europeos (Mistral Large 3, Medium 3.5, Small) y capacidades multimodales.
- [**Microsoft Copilot**](https://copilot.microsoft.com/) - Asistente de Microsoft integrado en Windows, Edge y Microsoft 365.
- [**Grok**](https://grok.com/) - Asistente de xAI integrado en X (Twitter), con acceso en tiempo real y modelos Grok 4.1/4.3.
- [**Qwen Chat**](https://chat.qwen.ai/) - Chat de Alibaba con la familia Qwen 3.5/3.6 (open weights) y Qwen3.7-Max, fuerte en multilingüe y razonamiento.
- [**Kimi**](https://kimi.com/) - Asistente de Moonshot AI con modelos de gran contexto y la familia Kimi K2.x (open weights).
- [**Google AI Studio**](https://aistudio.google.com/) - Entorno web gratuito para prototipar con los modelos Gemini multimodales y generar código vía API.
- [**Granite Playground**](https://www.ibm.com/granite/playground/) - Plataforma de IBM para probar sus modelos Granite empresariales **(open weights)**.

---

## 💻 IDEs y Editores de Código

- [**VSCode**](https://code.visualstudio.com/) - Editor de Microsoft. Núcleo **open source** (MIT), enorme ecosistema de extensiones e integración con casi cualquier asistente de IA.
- [**Cursor**](https://www.cursor.com/) - Fork de VSCode centrado en IA: Composer agente, edición multifichero, tab completion contextual.
- [**Windsurf**](https://windsurf.com/) - IDE con agente Cascade que combina chat, edición y ejecución autónoma de tareas.
- [**Zed**](https://zed.dev/) **(open source)** - Editor ultra rápido escrito en Rust, con colaboración en tiempo real y soporte nativo para asistentes de IA.
- [**Void**](https://voideditor.com/) **(open source)** - Alternativa libre a Cursor: fork de VSCode con agentes de IA y soporte para modelos locales.
- [**JetBrains IDEs**](https://www.jetbrains.com/) - IntelliJ, PyCharm, WebStorm… con su asistente AI Assistant y Junie (modo agente).
- [**JupyterLab**](https://jupyter.org/) **(open source)** - Interfaz interactiva para Python, R, Julia y notebooks de datos.

---

## 🧠 Agentes de Programación (Coding Agents)

Herramientas que escriben, editan y ejecutan código de forma autónoma o semiautónoma.

### CLI / Terminal
- [**Claude Code**](https://claude.com/claude-code) - CLI oficial de Anthropic. Trabaja en el repo, ejecuta comandos, edita ficheros y soporta hooks, sub-agentes, MCP y SDK.
- [**OpenAI Codex CLI**](https://github.com/openai/codex) **(open source, Apache 2.0)** - CLI de OpenAI para programar con sus modelos directamente en la terminal.
- [**Gemini CLI**](https://github.com/google-gemini/gemini-cli) **(open source, Apache 2.0)** - CLI oficial de Google con la familia Gemini 3 (Pro/Flash) y herramientas integradas.
- [**Aider**](https://aider.chat/) **(open source, Apache 2.0)** - Pair programmer por CLI, integra con Git, soporta múltiples modelos (Claude, GPT, locales).
- [**OpenHands**](https://github.com/All-Hands-AI/OpenHands) **(open source, MIT)** - Antes OpenDevin. Agente autónomo capaz de modificar código, ejecutar comandos y navegar.
- [**Goose**](https://block.github.io/goose/) **(open source, Apache 2.0)** - Agente de Block extensible vía MCP, funciona local con cualquier modelo.
- [**SWE-agent**](https://github.com/princeton-nlp/SWE-agent) **(open source, MIT)** - Agente de investigación de Princeton para resolver issues reales de GitHub.

### Editor / Extensiones
- [**Cline**](https://github.com/cline/cline) **(open source, Apache 2.0)** - Agente autónomo en VSCode con plan/act, MCP y soporte para cualquier proveedor.
- [**Roo Code**](https://github.com/RooVetGit/Roo-Code) **(open source, Apache 2.0)** - Fork avanzado de Cline con modos personalizados y orquestación.
- [**Continue**](https://continue.dev/) **(open source, Apache 2.0)** - Asistente para VSCode y JetBrains, totalmente configurable con modelos locales o cloud.
- [**Kilo Code**](https://github.com/Kilo-Org/kilocode) **(open source)** - Fork open source que combina lo mejor de Cline y Roo.
- [**GitHub Copilot**](https://github.com/features/copilot) - El clásico de Microsoft/GitHub, ahora con modo agente y soporte multimodelo.

### Web / SaaS
- [**Devin**](https://devin.ai/) - Agente de Cognition Labs orientado a tareas de ingeniería de software de extremo a extremo.
- [**Replit Agent**](https://replit.com/) - Crea, edita y despliega aplicaciones completas en el IDE web de Replit.
- [**Bolt.new**](https://bolt.new/) - De StackBlitz. Genera webapps completas que se ejecutan al instante en el navegador.
- [**v0**](https://v0.dev/) - De Vercel. Genera componentes y aplicaciones Next.js con shadcn/ui.
- [**Lovable**](https://lovable.dev/) - Constructor de aplicaciones web full-stack mediante chat.

---

## 🧩 Frameworks para Construir Agentes

### SDKs oficiales de proveedores
- [**Claude Agent SDK**](https://docs.claude.com/en/api/agent-sdk/overview) - SDK oficial de Anthropic (Python y TypeScript) para construir agentes con herramientas, MCP y memoria.
- [**OpenAI Agents SDK**](https://github.com/openai/openai-agents-python) **(open source, MIT)** - Framework ligero de OpenAI para orquestación de agentes con handoffs, guardrails y traces.
- [**Google ADK**](https://google.github.io/adk-docs/) **(open source, Apache 2.0)** - Agent Development Kit de Google, multi-agente, multi-modelo, con despliegue en Vertex AI.
- [**Microsoft AutoGen**](https://github.com/microsoft/autogen) **(open source, MIT)** - Framework multiagente conversacional de Microsoft Research.
- [**Microsoft Semantic Kernel**](https://github.com/microsoft/semantic-kernel) **(open source, MIT)** - SDK de Microsoft para integrar LLMs en aplicaciones .NET, Python y Java.

### Frameworks comunitarios
- [**LangGraph**](https://www.langchain.com/langgraph) **(open source)** - Framework basado en grafos de LangChain para agentes con estado, ciclos y memoria.
- [**LangChain**](https://python.langchain.com/) **(open source, MIT)** - Framework veterano de orquestación de LLMs, herramientas y memoria.
- [**LlamaIndex**](https://www.llamaindex.ai/) **(open source, MIT)** - Framework Python para RAG, agentes y workflows sobre datos privados.
- [**CrewAI**](https://github.com/crewAIInc/crewAI) **(open source, MIT)** - Orquestación de equipos de agentes colaborativos en Python.
- [**PydanticAI**](https://ai.pydantic.dev/) **(open source, MIT)** - Framework Python de tipado fuerte para construir agentes basados en Pydantic.
- [**Agno**](https://github.com/agno-agi/agno) **(open source, MPL-2.0)** - Antes Phidata. Framework Python ligero para agentes multimodales con memoria y herramientas.
- [**Smolagents**](https://github.com/huggingface/smolagents) **(open source, Apache 2.0)** - De Hugging Face. Agentes minimalistas que "piensan en código".
- [**Mastra**](https://mastra.ai/) **(open source, Elastic 2.0)** - Framework TypeScript para agentes con memoria, RAG y workflows.
- [**BeeAI Framework**](https://github.com/i-am-bee/beeai-framework) **(open source, Apache 2.0)** - Multi-agente en TS/Python con MCP/ACP, de IBM Research.
- [**BeeAI Platform**](https://beeai.dev/) **(open source)** - Plataforma para descubrir, ejecutar y componer agentes de múltiples frameworks.
- [**Letta**](https://github.com/letta-ai/letta) **(open source, Apache 2.0)** - Antes MemGPT. Agentes con memoria a largo plazo persistente.
- [**Strands Agents**](https://github.com/strands-agents/sdk-python) **(open source, Apache 2.0)** - SDK de AWS para agentes con MCP y enfoque "model-driven".
- [**Atomic Agents**](https://github.com/BrainBlend-AI/atomic-agents) **(open source, MIT)** - Framework modular y ligero basado en Pydantic.
- [**Haystack**](https://haystack.deepset.ai/) **(open source, Apache 2.0)** - Framework de deepset para RAG y pipelines de IA en producción.

### Protocolos y estándares
- [**MCP (Model Context Protocol)**](https://modelcontextprotocol.io/) **(open source)** - Estándar abierto promovido por Anthropic para conectar LLMs con herramientas y datos.
- [**A2A (Agent-to-Agent)**](https://a2a-protocol.org/) **(open source)** - Protocolo abierto de Google para comunicación entre agentes de distintos proveedores.
- [**ACP (Agent Communication Protocol)**](https://agentcommunicationprotocol.dev/) **(open source)** - Protocolo de comunicación entre agentes impulsado por IBM/Linux Foundation.
- [**OpenAI Function Calling**](https://platform.openai.com/docs/guides/function-calling) - Mecanismo del API de OpenAI para invocar funciones externas estructuradas.

### No-code / Low-code
- [**LangFlow**](https://www.langflow.org/) **(open source, MIT)** - Constructor visual de flujos y agentes basado en LangChain.
- [**Flowise**](https://flowiseai.com/) **(open source, Apache 2.0)** - Alternativa visual a LangFlow, drag-and-drop.
- [**Dify**](https://dify.ai/) **(open source)** - Plataforma para construir y desplegar aplicaciones LLM con RAG, agentes y observabilidad.
- [**n8n**](https://n8n.io/) **(fair-code)** - Automatización flexible de workflows con nodos de IA y agentes.

---

## 🌍 Modelos LLM Open Source / Open Weights

### 🔹 Meta (Llama)
- [**Llama 3.3 70B**](https://huggingface.co/meta-llama/Llama-3.3-70B-Instruct) - Modelo denso de gran calidad, comparable a GPT-4o en muchas tareas.
- [**Llama 4 Scout / Maverick**](https://www.llama.com/) - Familia Llama 4 (MoE) con visión nativa y contexto extremadamente largo (hasta 10M tokens en Scout).

### 🔹 DeepSeek
- [**DeepSeek V4**](https://huggingface.co/deepseek-ai/DeepSeek-V4-Pro) - Familia V4 (Pro y Flash) con contexto de 1M tokens y razonamiento integrado, referente abierto en código.
- [**DeepSeek V3.2**](https://huggingface.co/deepseek-ai/DeepSeek-V3.2) - Generación anterior MoE, aún muy usada en producción.
- [**DeepSeek R1**](https://huggingface.co/deepseek-ai/DeepSeek-R1) **(MIT)** - Modelo de razonamiento pionero. Disponibles destilaciones a 1.5B–70B.

### 🔹 Alibaba (Qwen)
- [**Qwen 3.5 / 3.6**](https://huggingface.co/Qwen) - Última generación con modelos densos y MoE (buque insignia abierto: Qwen3.5-397B-A17B), modo "thinking" híbrido y excelente multilingüe.
- [**Qwen3-Coder-Next**](https://huggingface.co/Qwen/Qwen3-Coder-Next) - Variante para programación, competitiva con los frontier en SWE-bench.
- [**QwQ**](https://huggingface.co/Qwen/QwQ-32B) - Modelo de razonamiento abierto al estilo R1 (superado por los modos thinking de Qwen 3+).

### 🔹 Mistral AI
- [**Mistral Large 3**](https://huggingface.co/mistralai/Mistral-Large-3-675B-Instruct-2512) **(Apache 2.0)** - Buque insignia open weights, MoE de 675B (41B activos).
- [**Mistral Small 4**](https://huggingface.co/mistralai/Mistral-Small-4-119B-2603) - Sucesor de Small 3.2; para uso local sigue disponible [Small 3.2 24B](https://huggingface.co/mistralai/Mistral-Small-3.2-24B-Instruct-2506) **(Apache 2.0)**.
- [**Devstral 2**](https://huggingface.co/mistralai/Devstral-2-123B-Instruct-2512) - Especializado en programación agéntica (123B y Small 24B).
- [**Codestral**](https://mistral.ai/news/codestral) - Modelo especializado en código (80+ lenguajes), vía API.
- [**Pixtral**](https://huggingface.co/mistralai/Pixtral-12B-2409) - Multimodal visión + texto.
- [**Magistral**](https://huggingface.co/mistralai/Magistral-Small-2509) - Familia de razonamiento de Mistral.

### 🔹 OpenAI (sí, open weights)
- [**gpt-oss-120b / gpt-oss-20b**](https://github.com/openai/gpt-oss) **(Apache 2.0)** - Primeros modelos de pesos abiertos de OpenAI (2025), pensados para razonamiento y uso de herramientas.

### 🔹 Google (Gemma)
- [**Gemma 4**](https://deepmind.google/models/gemma/gemma-4/) - Familia E2B / E4B / 12B / 26B MoE / 31B con visión y multilingüe. Apta desde móviles hasta GPU de escritorio.
- [**Gemma QAT**](https://huggingface.co/google) - Versiones cuantizadas oficiales (Gemma 3/4) para ejecutar en GPUs de consumo.

### 🔹 Microsoft (Phi)
- [**Phi-4**](https://huggingface.co/microsoft/phi-4) **(MIT)** - 14B con calidad sorprendente para su tamaño.
- [**Phi-4-mini / Phi-4-multimodal**](https://huggingface.co/microsoft) - Versiones pequeñas y multimodales.
- [**Phi-4-reasoning**](https://huggingface.co/microsoft/Phi-4-reasoning) - Variantes de razonamiento (incluida Phi-4-reasoning-vision).

### 🔹 IBM (Granite)
- [**Granite 4.1**](https://huggingface.co/ibm-granite) **(Apache 2.0)** - Familia empresarial 3B–30B para lenguaje, código, visión, voz y guardrails.

### 🔹 Moonshot AI
- [**Kimi K2.6**](https://huggingface.co/moonshotai/Kimi-K2.6) - MoE de ~1T parámetros (32B activos), multimodal, referente abierto en uso de herramientas y agentes.

### 🔹 Zhipu AI (Z.ai)
- [**GLM-5 / GLM-5.1**](https://huggingface.co/zai-org) - Familia china competitiva en razonamiento y código (745B, 44B activos).

### 🔹 Allen AI (verdaderamente abiertos: pesos + datos + código)
- [**OLMo 3 / 3.1**](https://huggingface.co/allenai) **(Apache 2.0)** - Modelos 7B/32B (Base/Instruct/Think) con todo el pipeline de entrenamiento abierto.
- [**Tülu 3**](https://huggingface.co/allenai) - Modelos post-entrenados con datos y receta totalmente abiertos.

### 🔹 Nous Research
- [**Hermes 4.3**](https://huggingface.co/NousResearch) - Última generación de Hermes, fine-tunes alineados.

### 🔹 Cohere
- [**Command A+**](https://huggingface.co/CohereLabs) **(Apache 2.0)** - MoE de 218B (25B activos) optimizado para RAG y herramientas, multilingüe. Primera licencia permisiva de Cohere.

### 🔹 Hugging Face
- [**SmolLM3 3B**](https://huggingface.co/HuggingFaceTB/SmolLM3-3B) **(Apache 2.0)** - SLM de alta calidad con receta totalmente abierta.

---

## ⚙️ Ejecución y Servido de LLMs

### Locales / Personales
- [**Ollama**](https://ollama.com/) **(open source, MIT)** - Cliente CLI para descargar y correr LLMs en local con un solo comando.
- [**LM Studio**](https://lmstudio.ai/) - GUI para ejecutar LLMs localmente con interfaz amigable.
- [**llama.cpp**](https://github.com/ggml-org/llama.cpp) **(open source, MIT)** - Motor de inferencia en C/C++ que hace posible casi todo lo demás.
- [**Llamafile**](https://github.com/Mozilla-Ocho/llamafile) **(open source, Apache 2.0)** - De Mozilla. Empaqueta modelo + runtime en un único ejecutable portable.
- [**Jan**](https://jan.ai/) **(open source, AGPL)** - Alternativa libre y local a ChatGPT, multiplataforma.
- [**Text Generation WebUI**](https://github.com/oobabooga/text-generation-webui) **(open source, AGPL)** - Web UI configurable para experimentar con modelos.

### Producción / Servido
- [**vLLM**](https://github.com/vllm-project/vllm) **(open source, Apache 2.0)** - Motor de inferencia de alto rendimiento con PagedAttention.
- [**SGLang**](https://github.com/sgl-project/sglang) **(open source, Apache 2.0)** - Runtime alternativo a vLLM, fuerte en estructuras y herramientas.
- [**TGI (Text Generation Inference)**](https://github.com/huggingface/text-generation-inference) - De Hugging Face, optimizado para producción.
- [**LiteLLM**](https://github.com/BerriAI/litellm) **(open source, MIT)** - Proxy unificado para llamar a 100+ proveedores con la API de OpenAI.

### Interfaces de Chat
- [**Open WebUI**](https://github.com/open-webui/open-webui) **(open source)** - Interfaz tipo ChatGPT autohospedada, integrada con Ollama y MCP.
- [**LibreChat**](https://github.com/danny-avila/LibreChat) **(open source, MIT)** - Frontend multiusuario para múltiples LLMs.
- [**AnythingLLM**](https://github.com/Mintplex-Labs/anything-llm) **(open source, MIT)** - Cliente con RAG, agentes y workspaces por usuario.
- [**Open Interpreter**](https://github.com/OpenInterpreter/open-interpreter) **(open source, AGPL)** - Ejecuta código generado por LLMs en local con un chat.

---

## 🧪 IA / Modelado / Fine-tuning

- [**Hugging Face Hub**](https://huggingface.co/) - Plataforma central de modelos y datasets abiertos.
- [**Transformers**](https://github.com/huggingface/transformers) **(open source, Apache 2.0)** - Framework de referencia para modelos NLP/multimodales.
- [**PEFT (LoRA, QLoRA)**](https://github.com/huggingface/peft) **(open source)** - Fine-tuning eficiente en parámetros.
- [**TRL**](https://github.com/huggingface/trl) **(open source, Apache 2.0)** - Entrenamiento por refuerzo (DPO, GRPO, SFT) para LLMs.
- [**Unsloth**](https://github.com/unslothai/unsloth) **(open source, Apache 2.0)** - Fine-tuning 2-5× más rápido y con menos memoria.
- [**Axolotl**](https://github.com/axolotl-ai-cloud/axolotl) **(open source, Apache 2.0)** - Herramienta para fine-tuning configurable por YAML.
- [**Google Colab**](https://colab.research.google.com/) - Notebooks con GPU gratis.
- [**Kaggle Kernels**](https://www.kaggle.com/code) - Notebooks con datasets integrados.

---

## 🛠️ Utilidades de IA

- [**Napkin AI**](https://app.napkin.ai/) - Convierte textos en diagramas e infografías con un clic.
- [**Kokoro TTS**](https://kokorotts.net/es) **(open weights, Apache 2.0)** - TTS de calidad con un modelo abierto de 82M.
- [**Whisper**](https://github.com/openai/whisper) **(open source, MIT)** - STT de OpenAI.
- [**faster-whisper**](https://github.com/SYSTRAN/faster-whisper) **(open source, MIT)** - Implementación 4× más rápida con CTranslate2.
- [**Coqui TTS / XTTS**](https://github.com/coqui-ai/TTS) **(open source)** - Síntesis de voz multilingüe y clonación.

---

## 🗄️ Bases de Datos

- [**PostgreSQL**](https://www.postgresql.org/) **(open source, PostgreSQL License)** - El SQL de referencia.
- [**SQLite**](https://www.sqlite.org/) **(open source, dominio público)** - Embebido, sin servidor.
- [**DuckDB**](https://duckdb.org/) **(open source, MIT)** - OLAP embebido, perfecto para análisis local de grandes datasets.
- [**Supabase**](https://supabase.com/) **(open source, Apache 2.0)** - BaaS sobre Postgres con auth, storage y APIs en tiempo real.
- [**Neon**](https://neon.tech/) - Postgres serverless con branching.
- [**MinIO**](https://github.com/minio/minio) **(open source, AGPL)** - Almacenamiento de objetos compatible con S3.
- [**Bonsai**](https://bonsai.io/) - ElasticSearch gestionado (plan gratuito).

### Vector / Búsqueda Semántica
- [**pgvector**](https://github.com/pgvector/pgvector) **(open source, PostgreSQL License)** - Extensión Postgres para vectores. Empieza por aquí.
- [**Qdrant**](https://github.com/qdrant/qdrant) **(open source, Apache 2.0)** - Base de datos vectorial escrita en Rust, muy rápida.
- [**Chroma**](https://github.com/chroma-core/chroma) **(open source, Apache 2.0)** - Ligera y pensada para LLMs.
- [**Milvus**](https://github.com/milvus-io/milvus) **(open source, Apache 2.0)** - Vector DB nativa cloud para miles de millones de vectores.
- [**Weaviate**](https://github.com/weaviate/weaviate) **(open source, BSD-3)** - Vector DB con módulos integrados para vectorización y RAG.
- [**LanceDB**](https://github.com/lancedb/lancedb) **(open source, Apache 2.0)** - Vector DB embebida y serverless, multimodal.
- [**FAISS**](https://github.com/facebookresearch/faiss) **(open source, MIT)** - Librería de búsqueda vectorial de Meta (CPU/GPU).

---

## 🚀 APIs / Backend

- [**FastAPI**](https://fastapi.tiangolo.com/) **(open source, MIT)** - Framework Python rápido y tipado para APIs.
- [**Litestar**](https://litestar.dev/) **(open source, MIT)** - Alternativa moderna a FastAPI, muy completa.
- [**Hono**](https://hono.dev/) **(open source, MIT)** - Framework web ultraligero para JS/TS y runtimes edge.
- [**Render**](https://render.com/) - Hosting de backends y bases de datos.
- [**Railway**](https://railway.app/) - Despliegue simple con DX excelente.
- [**Fly.io**](https://fly.io/) - Despliegue global de apps en contenedores cerca del usuario.
- [**OpenAPI Generator**](https://openapi-generator.tech/) **(open source, Apache 2.0)** - Generación de clientes y docs a partir de OpenAPI.

---

## 🎨 Despliegue Frontend

- [**Vercel**](https://vercel.com/) - Hosting optimizado para Next.js, ideal para frontends modernos.
- [**Netlify**](https://www.netlify.com/) - Despliegue automático conectado a Git.
- [**Cloudflare Pages**](https://pages.cloudflare.com/) - Hosting JAMstack rápido en la red de Cloudflare.
- [**Coolify**](https://coolify.io/) **(open source)** - Alternativa autohospedada a Vercel/Netlify/Heroku.

---

## 🧱 UI / Frameworks de Componentes

- [**Tailwind CSS**](https://tailwindcss.com/) **(open source, MIT)** - Utility-first CSS. Estándar de facto.
- [**shadcn/ui**](https://ui.shadcn.com/) **(open source, MIT)** - Componentes copiables sobre Tailwind + Radix.
- [**Radix UI**](https://www.radix-ui.com/) **(open source, MIT)** - Primitivos accesibles sin estilo.
- [**Material UI**](https://mui.com/) **(open source, MIT)** - Componentes React Material Design.
- [**DaisyUI**](https://daisyui.com/) **(open source, MIT)** - Componentes sobre Tailwind.
- [**Bootstrap**](https://getbootstrap.com/) **(open source, MIT)** - El clásico framework CSS.
- [**Park UI**](https://park-ui.com/) **(open source)** - Sobre Panda CSS y Ark UI.

---

## 🖼️ Frameworks Frontend

- [**Next.js**](https://nextjs.org/) **(open source, MIT)** - El framework React full-stack más usado.
- [**Astro**](https://astro.build/) **(open source, MIT)** - Multi-framework, ideal para contenido y sites con islas de interactividad.
- [**Vue.js**](https://vuejs.org/) / [**Nuxt**](https://nuxt.com/) **(open source, MIT)** - Vue progresivo y su meta-framework.
- [**Svelte / SvelteKit**](https://svelte.dev/) **(open source, MIT)** - Compila a JS puro, excelente rendimiento.
- [**SolidJS**](https://www.solidjs.com/) **(open source, MIT)** - Reactividad de grano fino sin Virtual DOM.
- [**HTMX**](https://htmx.org/) **(open source, BSD-2)** - HTML hipermedia + interactividad sin SPA.
- [**Remix / React Router**](https://reactrouter.com/) **(open source, MIT)** - Web standards + React.

---

## 📊 Visualización de Datos

- [**Recharts**](https://recharts.org/) **(open source, MIT)** - Gráficas para React fáciles de integrar.
- [**Chart.js**](https://www.chartjs.org/) **(open source, MIT)** - Biblioteca simple y popular.
- [**Plotly.js**](https://plotly.com/javascript/) **(open source, MIT)** - Visualizaciones avanzadas e interactivas.
- [**D3.js**](https://d3js.org/) **(open source, ISC)** - Potente y flexible, con curva de aprendizaje.
- [**Observable Plot**](https://observablehq.com/plot/) **(open source, ISC)** - API declarativa sobre D3.
- [**ECharts**](https://echarts.apache.org/) **(open source, Apache 2.0)** - Visualizaciones potentes mantenidas por Apache.

---

## 📡 MQTT / IoT

- [**Mosquitto**](https://mosquitto.org/) **(open source, EPL/EDL)** - Broker MQTT ligero.
- [**EMQX**](https://github.com/emqx/emqx) **(open source, Apache 2.0)** - Broker MQTT escalable.
- [**HiveMQ Cloud**](https://www.hivemq.com/mqtt-cloud-broker/) - Broker MQTT gestionado (plan gratuito).
- [**MQTT Explorer**](https://mqtt-explorer.com/) - GUI para depurar MQTT.
- [**Home Assistant**](https://www.home-assistant.io/) **(open source, Apache 2.0)** - Plataforma de domótica abierta.

---

## 🔐 Seguridad

- [**Keycloak**](https://www.keycloak.org/) **(open source, Apache 2.0)** - Gestión de identidades empresarial.
- [**Authentik**](https://goauthentik.io/) **(open source, MIT)** - Alternativa moderna a Keycloak.
- [**Auth0**](https://auth0.com/) - Autenticación como servicio (plan gratuito).
- [**Nginx Proxy Manager**](https://github.com/NginxProxyManager/nginx-proxy-manager) **(open source, MIT)** - GUI para gestionar Nginx + SSL.
- [**Caddy**](https://caddyserver.com/) **(open source, Apache 2.0)** - Servidor web con HTTPS automático.
- [**Traefik**](https://traefik.io/traefik/) **(open source, MIT)** - Reverse proxy y load balancer cloud-native.
- [**Certbot**](https://certbot.eff.org/) **(open source)** / [**Let's Encrypt**](https://letsencrypt.org/) - Certificados SSL gratuitos.
- [**NGINX**](https://nginx.org/) **(open source, BSD-2)** - Servidor web de referencia.

---

## 🔄 CI/CD y Contenedores

- [**GitHub Actions**](https://github.com/features/actions) - Automatización integrada con GitHub.
- [**Forgejo Actions**](https://forgejo.org/) **(open source, GPL-3.0)** - Equivalente en el fork comunitario de Gitea.
- [**Docker**](https://www.docker.com/) - Plataforma de contenedores estándar.
- [**Podman**](https://podman.io/) **(open source, Apache 2.0)** - Contenedores sin daemon, drop-in replacement de Docker.
- [**Docker Hub**](https://hub.docker.com/) - Registro público de imágenes.
- [**Dokploy**](https://github.com/Dokploy/dokploy) **(open source)** - Alternativa autohospedada a Vercel/Heroku.
- [**Dockge**](https://github.com/louislam/dockge) **(open source, MIT)** - Gestor visual de stacks docker-compose.
- [**Portainer CE**](https://www.portainer.io/) **(open source)** - GUI para Docker y Kubernetes.
- [**LocalStack**](https://www.localstack.cloud/) - Simulador local de servicios AWS.

---

## 🔭 Observabilidad / Test

- [**Postman**](https://www.postman.com/) - Testing manual y automático de APIs.
- [**Bruno**](https://www.usebruno.com/) **(open source, MIT)** - Alternativa offline-first y gitops a Postman.
- [**Hoppscotch**](https://hoppscotch.io/) **(open source, MIT)** - Cliente API web.
- [**Phoenix**](https://github.com/Arize-ai/phoenix) **(open source, Elastic 2.0)** - Observabilidad y evaluación de aplicaciones LLM.
- [**LangFuse**](https://github.com/langfuse/langfuse) **(open source, MIT)** - Observabilidad, traces, evals y prompt management para LLMs.
- [**Helicone**](https://github.com/Helicone/helicone) **(open source, Apache 2.0)** - Observabilidad LLM como proxy o async.
- [**OpenLLMetry**](https://github.com/traceloop/openllmetry) **(open source, Apache 2.0)** - Extensión de OpenTelemetry para LLMs.
- [**Grafana**](https://grafana.com/) **(open source, AGPL)** + [**Prometheus**](https://prometheus.io/) **(open source, Apache 2.0)** - Stack de monitorización estándar.

---

## 🤖 Automatización

- [**n8n**](https://n8n.io/) **(fair-code)** - Workflows con nodos de IA y agentes.
- [**Activepieces**](https://www.activepieces.com/) **(open source, MIT)** - Alternativa libre a Zapier.
- [**Windmill**](https://www.windmill.dev/) **(open source, AGPL)** - Plataforma para scripts, flujos y apps internas.
- [**Ansible**](https://docs.ansible.com/) **(open source, GPL-3.0)** - Automatización de infraestructura por YAML.
- [**Terraform**](https://www.terraform.io/) / [**OpenTofu**](https://opentofu.org/) **(open source)** - Infraestructura como código (OpenTofu es el fork libre).

---

## 🧰 Utilidades

- [**Git**](https://git-scm.com/) **(open source, GPL-2.0)** - Control de versiones distribuido.
- [**Forgejo**](https://forgejo.org/) **(open source, GPL-3.0)** - Forge Git autohospedable (fork comunitario de Gitea).
- [**Omni-Tools**](https://github.com/iib0011/omni-tools) **(open source, MIT)** - Toolkit web autohospedado de utilidades en el navegador.
- [**Dawarich**](https://dawarich.app/docs/intro) **(open source)** - Historial de ubicación self-hosted.
- [**Immich**](https://immich.app/) **(open source, AGPL)** - Alternativa libre a Google Photos.
- [**Nextcloud**](https://nextcloud.com/) **(open source, AGPL)** - Suite colaborativa autohospedada.

---

## ⚡ Herramientas de Desarrollo Modernas

- [**uv**](https://github.com/astral-sh/uv) **(open source, MIT)** - Gestor de Python en Rust ultrarrápido (reemplaza pip, venv, pyenv, pip-tools…).
- [**Ruff**](https://github.com/astral-sh/ruff) **(open source, MIT)** - Linter + formatter de Python en Rust, 10-100× más rápido.
- [**Vite**](https://vitejs.dev/) **(open source, MIT)** - Empaquetador moderno para apps web.
- [**Bun**](https://bun.sh/) **(open source, MIT)** - Runtime, bundler, test runner y package manager JS todo-en-uno.
- [**Deno**](https://deno.com/) **(open source, MIT)** - Runtime JS/TS seguro por defecto, con APIs web.
- [**pnpm**](https://pnpm.io/) **(open source, MIT)** - Gestor de paquetes JS eficiente en disco.
- [**Biome**](https://biomejs.dev/) **(open source, MIT)** - Linter + formatter JS/TS en Rust, alternativa a ESLint+Prettier.
- [**Turborepo**](https://turbo.build/) **(open source, MPL-2.0)** - Build system de Vercel para monorepos.

---

## 🖼️ Recursos Gráficos

- [**Pexels**](https://www.pexels.com/) - Imágenes y vídeos gratuitos de calidad.
- [**Unsplash**](https://unsplash.com/) - Fotografía gratuita de alta calidad.
- [**Lucide**](https://lucide.dev/) **(open source, ISC)** - Iconos abiertos modernos.
- [**Heroicons**](https://heroicons.com/) **(open source, MIT)** - Iconos de los creadores de Tailwind.
- [**Tabler Icons**](https://tabler.io/icons) **(open source, MIT)** - 5000+ iconos SVG libres.
- [**Phosphor Icons**](https://phosphoricons.com/) **(open source, MIT)** - Familia de iconos consistente y flexible.

---

## 🛠️ Configuración de Entornos de Desarrollo

- [**Windows**](https://github.com/ANFAIA/recursos-anfaia/blob/main/entorno_windows.md) - Pasos para configurar tu Windows 🪟
- [**Linux - Ubuntu**](https://github.com/ANFAIA/recursos-anfaia/blob/main/entorno_linux_ubuntu.md) - Pasos para configurar tu Linux Ubuntu 🐧
- [**Linux - Fedora**](https://github.com/ANFAIA/recursos-anfaia/blob/main/entorno_linux_fedora.md) - Pasos para configurar tu Linux Fedora 🐧
- [**macOS**](https://github.com/ANFAIA/recursos-anfaia/blob/main/entorno_macosx.md) - Pasos para configurar tu Mac 🍎
- [**Entorno virtual en Python**](https://github.com/ANFAIA/recursos-anfaia/blob/main/virtual_environment.md) - Crear y gestionar un venv en Python

---

## 📚 Tutoriales

- [**FastAPI**](https://github.com/dibanez/fastapi_tutorial) - Tutorial de inicio de una API con FastAPI.
- [**Django**](https://github.com/dibanez/django_library_workshop) - Tutorial de una app Django con API incluida.
