#KERNEX | Multi-Tier Nemotron AI Platform
KERNEX is an enterprise-grade AI model ecosystem powered by the NVIDIA Nemotron model family via the Nebius Token Factory API. It features an intelligent Complexity-Aware Model Router that dynamically analyzes incoming requests and dispatches them to the optimal tier—maximizing speed, execution accuracy, and compute efficiency.

##🧠 Dynamic Model Routing Architecture
KERNEX eliminates the trade-off between speed and intelligence using a tri-tier routing system:

                  ┌─────────────────────────────────────────┐
                  │          KERNEX Core Router             │
                  │   (Powered by Nemotron-3.5 Nano/Nemo)   │
                  └────────────────────┬────────────────────┘
                                       │
                         Analyzes Prompt Complexity
                                       │
         ┌─────────────────────────────┼─────────────────────────────┐
         ▼                             ▼                             ▼
┌───────────────────┐        ┌───────────────────┐        ┌───────────────────┐
│   Low Complexity  │        │ Medium Complexity │        │ High Complexity   │
├───────────────────┤        ├───────────────────┤        ├───────────────────┤
│   Nemotron-3.5    │        │    Nemotron-3     │        │   Nemotron-3.5    │
│      Nemo/Nano    │        │       Ultra       │        │       Super       │
│                   │        │                   │        │                   │
│ • Simple C Code   │        │ • Algorithm Opt.  │        │ • Multimodal/VL   │
│ • Rapid Queries   │        │ • System Logic    │        │ • Heavy Reasoning │
│ • Low Latency     │        │ • Refactoring     │        │ • Architecture    │
└───────────────────┘        └───────────────────┘        └───────────────────┘

##✨ Core Platform Capabilities
🚦 Intelligent Prompt Router: The lightweight Nemo tier acts as an instant classifier, evaluating prompt complexity in real time before routing execution to Ultra or Super.

🏆 Nemotron Super Engine: Apex-tier model handling multi-step reasoning, architectural synthesis, and complex vision-language tasks (Super-VL).

⚡ Sub-Second Code Generation: Generates pure, compilable C/C++ and multi-language code with standard ASCII operators and zero conversational clutter.

🔒 Zero-Trust Security Proxy: Backend proxy hides API credentials from client network inspections and browser storage.

📊 Real-Time Telemetry: Live streaming of token counts, generation latency, and output throughput (tok/s).

##🛠️ Built With
AI Engine: NVIDIA Nemotron Family (Nemotron-3.5-Nano, Nemotron-3-Ultra, Nemotron-3.5-Super-VL)

API Provider: Nebius Token Factory

Frontend: React, TypeScript, TanStack, Tailwind CSS

Backend Proxy: Python (Flask, Flask-CORS)

##🚀 Quickstart & Development
Prerequisites
Node.js (v18+) and npm

Python 3.9+

Nebius Token Factory API Key
