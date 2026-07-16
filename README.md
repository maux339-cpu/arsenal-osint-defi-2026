# Arsenal OSINT + DeFi + Pentest (2026)  Inventario dos **forks** na conta [maux339-cpu](https://github.com/maux339-cpu). Pesquisa autorizada / bug bounty / audit. **Nao e kit de crime.**  | Wave | Data | Foco | |
---

## Wave 6 — Agent hijack + DeFi AI defense (2026-07-16)

**Fonte:** varredura X (AgentSeal, Strix, hack-skills, garak/rebuff, agentic AI top vector, Zscaler refund agents, SCONE-style DeFi AI) + forks no GitHub.

**Indice desta wave:** [agent-hijack-defi-defense-2026](https://github.com/maux339-cpu/agent-hijack-defi-defense-2026) (README + 4 skills defensivas + inventory.json + queries X).

### Ameaca (resumo)

| Vetor | Monetizacao | Defesa |
|-------|-------------|--------|
| Goal hijack / prompt injection | Bot com tools (refund, e-mail, shell) obedece texto sujo | DATA!=COMMAND, HITL, least privilege, AgentSeal/promptfoo/garak |
| Agentes ofensivos em SC | Hunt automatico de vulns DeFi | Slither+Foundry+Echidna, pause/circuit breaker, so alvo autorizado |

### Forks novos Wave 6 (5)

| Fork | Upstream | Funcao |
|------|----------|--------|
| [agentseal](https://github.com/maux339-cpu/agentseal) | getagentseal | Scan MCP poisoning + prompt injection resistance |
| [strix](https://github.com/maux339-cpu/strix) | usestrix | AI agents pentest (web/app) |
| [hack-skills](https://github.com/maux339-cpu/hack-skills) | yaklang | Pack SKILL.md (AI/LLM + smart contract domains) |
| [garak](https://github.com/maux339-cpu/garak) | NVIDIA | LLM vulnerability scanner |
| [rebuff](https://github.com/maux339-cpu/rebuff) | protectai | Detector prompt injection |

### Cross-ref (ja no arsenal)

promptfoo · slither · echidna · foundry · damn-vulnerable-defi-foundry · security-agent-skills-arsenal

### Pipeline Wave 6

```text
Agent go-live:  agentseal + promptfoo/garak + HITL checklist (skills no indice Wave 6)
DeFi AI audit:  slither -> foundry -> echidna -> LLM review defensivo (so contrato proprio/bounty)
```

### Skills locais (no indice Wave 6)

- agent-goal-hijack-defense
- prompt-injection-authorized-test
- defi-ai-audit-hunt
- agent-privilege-checklist

**Politica:** igual Wave 5 — forks no GitHub; **nao** instalar cegamente em agents. Revisar SKILL.md. Uso autorizado only.

------|------|------| | 1 | 2026-07-15 | OSINT core + recon + DeFi base + HexStrike | | 2 | 2026-07-15 | Gaps OSINT (web-check, GHunt, social-analyzer...) | | 3 | 2026-07-15 | Crypto audit avancado + AI pentest + payloads | | 4 | 2026-07-15 | **On-chain investigations** (Zach stack + GraphSense + lists) Ã”Ã‡Ã¶ 28 forks |
| 5 | 2026-07-15 | **OSINT agent skills** (SKILL.md packs) â€” 13 forks novos + ja existentes |
| 6 | 2026-07-16 | **Agent hijack + DeFi AI defense** — 5 forks + indice skills |  ---  ## Wave 4 Ã”Ã‡Ã¶ On-chain investigations / blockchain forensics  Fonte: varredura X (lista ZachXBT + OffcierCia + SlowMist + GraphSense + BlockSec) + check de repos publicos no GitHub. **28 forks novos** (nenhum duplicado com waves 1Ã”Ã‡Ã´3).  ### Listas / handbooks (metodologia)  | Fork | Upstream | Funcao | |------|----------|--------| | [On-Chain-Investigations-Tools-List](https://github.com/maux339-cpu/On-Chain-Investigations-Tools-List) | OffcierCia | Catalogo canonico de tools de investigacao on-chain | | [Crypto-OpSec-SelfGuard-RoadMap](https://github.com/maux339-cpu/Crypto-OpSec-SelfGuard-RoadMap) | OffcierCia | OpSec crypto / self-guard | | [ultimate-defi-research-base](https://github.com/maux339-cpu/ultimate-defi-research-base) | OffcierCia | Research + tools DeFi | | [DeFi-Developer-Road-Map](https://github.com/maux339-cpu/DeFi-Developer-Road-Map) | OffcierCia | Roadmap dev DeFi | | [non-typical-OSINT-guide](https://github.com/maux339-cpu/non-typical-OSINT-guide) | OffcierCia | Guia OSINT nao-tipico | | [awesome_osint_blockchain_analysis](https://github.com/maux339-cpu/awesome_osint_blockchain_analysis) | aaarghhh | Awesome OSINT blockchain | | [Legendary_Crypto](https://github.com/maux339-cpu/Legendary_Crypto) | K2SOsint | Crypto OSINT / AML / forensics | | [Legendary_OSINT](https://github.com/maux339-cpu/Legendary_OSINT) | K2SOsint | Meta-lista OSINT (CTI/AML/KYC) | | [Crypto-Asset-Tracing-Handbook](https://github.com/maux339-cpu/Crypto-Asset-Tracing-Handbook) | slowmist | Manual de tracing de ativos | | [Blockchain-dark-forest-selfguard-handbook](https://github.com/maux339-cpu/Blockchain-dark-forest-selfguard-handbook) | slowmist | Handbook dark forest / defesa | | [Knowledge-Base](https://github.com/maux339-cpu/Knowledge-Base) | slowmist | KB SlowMist |  ### Codigo / tools open (forensics + suporte)  | Fork | Upstream | Funcao | |------|----------|--------| | [metasuites](https://github.com/maux339-cpu/metasuites) | blocksecteam | Extensao browser (labels em explorers) Ã”Ã‡Ã¶ stack Zach | | [metasleuth_resources](https://github.com/maux339-cpu/metasleuth_resources) | blocksecteam | Reports/resources MetaSleuth (core SaaS) | | [Phalcon](https://github.com/maux339-cpu/Phalcon) | blocksecteam | Tx explorer / debug BlockSec | | [graphsense-dashboard](https://github.com/maux339-cpu/graphsense-dashboard) | graphsense | Dashboard forensics self-host | | [graphsense-lib](https://github.com/maux339-cpu/graphsense-lib) | graphsense | Backend/CLI GraphSense | | [graphsense-tagpacks](https://github.com/maux339-cpu/graphsense-tagpacks) | graphsense | TagPacks publicos (labels) | | [GraphSense-Maltego-transform](https://github.com/maux339-cpu/GraphSense-Maltego-transform) | INTERPOL-Innovation-Centre | Transform Maltego + GraphSense | | [impersonator](https://github.com/maux339-cpu/impersonator) | impersonator-eth | Spoof login dApp (lab) Ã”Ã‡Ã¶ stack Zach | | [impersonator-extension](https://github.com/maux339-cpu/impersonator-extension) | impersonator-eth | Extensao Impersonator | | [Orbit](https://github.com/maux339-cpu/Orbit) | s0md3v | Graph BTC / OSINT on-chain | | [trueblocks-core](https://github.com/maux339-cpu/trueblocks-core) | TrueBlocks | Indexador ETH local / forensics offline | | [rolod0x](https://github.com/maux339-cpu/rolod0x) | rolod0x | Address book privado multi-site | | [etherscan-labels](https://github.com/maux339-cpu/etherscan-labels) | brianleect | Dump labels EVM (CSV/JSON) | | [helius-sdk](https://github.com/maux339-cpu/helius-sdk) | helius-labs | SDK Solana (API surveillance) | | [xray](https://github.com/maux339-cpu/xray) | helius-labs | Explorer SOL human-readable | | [a_TON_of_privacy](https://github.com/maux339-cpu/a_TON_of_privacy) | aaarghhh | OSINT/investigacao TON | | [atop_maltego](https://github.com/maux339-cpu/atop_maltego) | aaarghhh | Maltego transforms TON |  ### SaaS / enterprise **sem** fork (nao tem codigo publico util)  TRM â”¬Ã€ Chainalysis â”¬Ã€ Elliptic â”¬Ã€ Arkham â”¬Ã€ Cielo â”¬Ã€ Nansen â”¬Ã€ Breadcrumbs (produto) â”¬Ã€ MetaSleuth core â”¬Ã€ MistTrack â”¬Ã€ Snusbase â”¬Ã€ IntelX â”¬Ã€ LeakPeek â”¬Ã€ OSINT Industries â”¬Ã€ Spur â”¬Ã€ Cavalier â”¬Ã€ ZachXBT (0 public repos) â”¬Ã€ wallet-scanner.app (claim sem repo confiavel)  ---  
| 6.1 | 2026-07-16 | **Offensive agent/DeFi AI skills** — 10 forks + 4 OFF skills |
---

## Wave 5 â€” OSINT agent skills (SKILL.md) â€” soh no GitHub

**Politica desta wave:**
- Forks **apenas no GitHub** (`maux339-cpu`) â€” **nao instalados** em `~/.claude/skills`, `~/.grok/skills` nem copiados para disco local.
- Skills de terceiros podem ser **maliciosas** (SkillCloak / supply-chain). **Escanear e ler `SKILL.md` antes de qualquer install.**
- Uso: **escopo autorizado** / bug bounty / audit. Nao e kit de crime.

### Checklist antes de instalar (em outra maquina / quando autorizar)

1. Ler `SKILL.md` + scripts embutidos (sem executar cegamente)
2. Preferir repos com stars, historico e licenca clara
3. Rodar scanner de skills se disponivel (SkillSpector / agent-scan / review manual)
4. Instalar so o necessario; preferir copia seletiva de skills
5. Nunca carregar skill em alvos sem autorizacao escrita

### Forks novos Wave 5 (13) â€” cada repo tem descricao `[Wave5 ...]`

| Fork | Upstream | O que e | Risco / nota |
|------|----------|---------|--------------|
| [Claude-OSINT](https://github.com/maux339-cpu/Claude-OSINT) | elementalsouls | **Top** OSINT recon: 90+ modulos, dorks, secrets regex (SKILL.md) | Revisar; escopo autorizado |
| [cti-expert](https://github.com/maux339-cpu/cti-expert) | 7onez | CTI + OSINT skill Claude (67+ cmds) | Revisar |
| [Claude-BugHunter](https://github.com/maux339-cpu/Claude-BugHunter) | elementalsouls | 51 skills BB + recon (irmas do Claude-OSINT) | Ofensivo externo; autorizado only |
| [Claude-Red](https://github.com/maux339-cpu/Claude-Red) | SnailSploit | 50+ skills red team (incl. OSINT) | **Alto impacto** â€” so lab/autorizado |
| [recon-skills](https://github.com/maux339-cpu/recon-skills) | uphiago | 144 skills recon/pentest | Revisar |
| [ctf-skills](https://github.com/maux339-cpu/ctf-skills) | ljagiello | Agent skills CTF incl. OSINT | CTF/lab |
| [investigate-journalism-skills](https://github.com/maux339-cpu/investigate-journalism-skills) | patricksavalle | Jornalismo + OSINT (Claude/Gemini/Grok) | Baixo risco relativo |
| [osint-skill](https://github.com/maux339-cpu/osint-skill) | smixs | Dossie OSINT multi-agent | Cuidado PII/legal |
| [aircraft-research-claude-skill](https://github.com/maux339-cpu/aircraft-research-claude-skill) | wptk | GEOINT aeronaves | Uso legal only |
| [OnionClaw](https://github.com/maux339-cpu/OnionClaw) | christinminor459 | Tor + LLM para agents | Dark web; legal only |
| [pentest-agents](https://github.com/maux339-cpu/pentest-agents) | H-mmer | 50 agents Claude (incl. OSINT) | Revisar cada agent |
| [openskills](https://github.com/maux339-cpu/openskills) | numman-ali | Infra: porta SKILL.md Claude â†’ Cursor/Codex | Tool de install â€” usar com cautela |
| [Awesome-AI-Hacking-Agents](https://github.com/maux339-cpu/Awesome-AI-Hacking-Agents) | EvanThomasLuke | Lista/curadoria de agents | Indice (nao pack unico) |

### Ja existiam (cross-ref Wave 1â€“4 / arsenal) â€” relevantes a OSINT agentic

| Fork | Papel |
|------|--------|
| [OpenOSINT](https://github.com/maux339-cpu/OpenOSINT) | MCP/agent tools reais (anti-alucinacao) |
| [robin](https://github.com/maux339-cpu/robin) | Dark web OSINT + LLM |
| [awesome-osint-arsenal](https://github.com/maux339-cpu/awesome-osint-arsenal) | Curadoria 750+ tools |
| [pentest-ai-agents](https://github.com/maux339-cpu/pentest-ai-agents) | Agents ofensivos (0xSteph) |
| [maigret](https://github.com/maux339-cpu/maigret) / [sherlock](https://github.com/maux339-cpu/sherlock) / [holehe](https://github.com/maux339-cpu/holehe) | Identity pivot (tools, nao SKILL.md) |
| [On-Chain-Investigations-Tools-List](https://github.com/maux339-cpu/On-Chain-Investigations-Tools-List) | Crypto OSINT (lista) |

### Stack sugerida (quando for instalar de proposito)

```text
Cerebro:  Claude-OSINT  +  cti-expert
BB:       Claude-BugHunter  (recon ja alinhado)
Ofensivo: Claude-Red / recon-skills  (so autorizado)
Maos:     OpenOSINT (MCP)
Dark:     robin + OnionClaw
Infra:    openskills (so se precisar Cursor/Codex)
```

### O que NAO foi forkado

- Skills **claramente maliciosas** / drainers / dumps ilegais
- Claims sem repo GitHub confiavel
- SaaS fechados sem codigo

## Wave 3 Ã”Ã‡Ã¶ Crypto / SC ofensivo + pentest avancado  ### Smart contract / DeFi (audit + lab)  | Fork | Upstream | Funcao | |------|----------|--------| | [mythril](https://github.com/maux339-cpu/mythril) | ConsenSysDiligence | Symbolic execution EVM | | [heimdall-rs](https://github.com/maux339-cpu/heimdall-rs) | Jon-Becker | Decompile / disasm bytecode | | [halmos](https://github.com/maux339-cpu/halmos) | a16z | Symbolic testing / properties | | [halmos-cheatcodes](https://github.com/maux339-cpu/halmos-cheatcodes) | a16z | Cheatcodes Halmos | | [aderyn](https://github.com/maux339-cpu/aderyn) | Cyfrin | Static analyzer moderno (+ MCP) | | [4naly3er](https://github.com/maux339-cpu/4naly3er) | Picodes | Static analyzer estilo C4 | | [smart-contract-vulnerabilities](https://github.com/maux339-cpu/smart-contract-vulnerabilities) | kadenzipfel | Catalogo de vulns (AI agents) | | [damn-vulnerable-defi](https://github.com/maux339-cpu/damn-vulnerable-defi) | OpenZeppelin | Lab ofensivo DeFi | | [damn-vulnerable-defi-foundry](https://github.com/maux339-cpu/damn-vulnerable-defi-foundry) | nicolasgarcia214 | DVD em Foundry | | [damn-vulnerable-defi-v4-solutions](https://github.com/maux339-cpu/damn-vulnerable-defi-v4-solutions) | SunWeb3Sec | Solucoes DVD v4 | | [solodit_content](https://github.com/maux339-cpu/solodit_content) | solodit | Conteudo / findings Solodit | | [claudit](https://github.com/maux339-cpu/claudit) | marchev | MCP search Solodit findings | | [not-so-smart-contracts](https://github.com/maux339-cpu/not-so-smart-contracts) | crytic | Exemplos de bugs classicos |  ### AI pentest / red team / web payloads  | Fork | Upstream | Funcao | |------|----------|--------| | [pentagi](https://github.com/maux339-cpu/pentagi) | vxcontrol | AI multi-agent pentest autonomo (~20k) | | [PentestGPT](https://github.com/maux339-cpu/PentestGPT) | GreyDGL | LLM pentest framework | | [pentest-ai](https://github.com/maux339-cpu/pentest-ai) | 0xSteph | MCP 205 tools + agents OWASP | | [pentest-ai-agents](https://github.com/maux339-cpu/pentest-ai-agents) | 0xSteph | Subagents Claude Code ofensivos | | [PayloadsAllTheThings](https://github.com/maux339-cpu/PayloadsAllTheThings) | swisskyrepo | Biblia de payloads web | | [awesome-pentest](https://github.com/maux339-cpu/awesome-pentest) | enaqx | Meta-lista pentest | | [promptfoo](https://github.com/maux339-cpu/promptfoo) | promptfoo | Red team LLM / agents |  ---  ## Wave 2 Ã”Ã‡Ã¶ OSINT (gaps X)  | Fork | Upstream | |------|----------| | [web-check](https://github.com/maux339-cpu/web-check) | lissy93 | | [GHunt](https://github.com/maux339-cpu/GHunt) | mxrch | | [ghunt_companion](https://github.com/maux339-cpu/ghunt_companion) | mxrch | | [social-analyzer](https://github.com/maux339-cpu/social-analyzer) | qeeqbox | | [Osintgram](https://github.com/maux339-cpu/Osintgram) | Datalux | | [toutatis](https://github.com/maux339-cpu/toutatis) | megadose | | [robin](https://github.com/maux339-cpu/robin) | apurvsinghgautam | | [dark-web-osint-tools](https://github.com/maux339-cpu/dark-web-osint-tools) | apurvsinghgautam | | [recon-ng](https://github.com/maux339-cpu/recon-ng) | lanmaster53 | | [sn0int](https://github.com/maux339-cpu/sn0int) | kpcyrd | | [OSINT-Cheat-sheet](https://github.com/maux339-cpu/OSINT-Cheat-sheet) | Jieyab89 | | [awesome-osint-arsenal](https://github.com/maux339-cpu/awesome-osint-arsenal) | rawfilejson | | [OpenOSINT](https://github.com/maux339-cpu/OpenOSINT) | OpenOSINT | | [MetaDetective](https://github.com/maux339-cpu/MetaDetective) | franckferman | | [GitSint](https://github.com/maux339-cpu/GitSint) | N0rz3 |  ---  ## Wave 1 Ã”Ã‡Ã¶ OSINT core + recon + DeFi base  ### OSINT  [awesome-osint](https://github.com/maux339-cpu/awesome-osint) â”¬Ã€ [osint_stuff_tool_collection](https://github.com/maux339-cpu/osint_stuff_tool_collection) â”¬Ã€ [OSINT-BIBLE](https://github.com/maux339-cpu/OSINT-BIBLE) â”¬Ã€ [sherlock](https://github.com/maux339-cpu/sherlock) â”¬Ã€ [maigret](https://github.com/maux339-cpu/maigret) â”¬Ã€ [socid-extractor](https://github.com/maux339-cpu/socid-extractor) â”¬Ã€ [blackbird](https://github.com/maux339-cpu/blackbird) â”¬Ã€ [holehe](https://github.com/maux339-cpu/holehe) â”¬Ã€ [h8mail](https://github.com/maux339-cpu/h8mail) â”¬Ã€ [phoneinfoga](https://github.com/maux339-cpu/phoneinfoga) â”¬Ã€ [theHarvester](https://github.com/maux339-cpu/theHarvester) â”¬Ã€ [spiderfoot](https://github.com/maux339-cpu/spiderfoot) â”¬Ã€ [Photon](https://github.com/maux339-cpu/Photon) â”¬Ã€ [H4X-Tools](https://github.com/maux339-cpu/H4X-Tools) â”¬Ã€ [trufflehog](https://github.com/maux339-cpu/trufflehog)  ### Recon web  [amass](https://github.com/maux339-cpu/amass) â”¬Ã€ [subfinder](https://github.com/maux339-cpu/subfinder) â”¬Ã€ [httpx](https://github.com/maux339-cpu/httpx) â”¬Ã€ [katana](https://github.com/maux339-cpu/katana) â”¬Ã€ [nuclei](https://github.com/maux339-cpu/nuclei) â”¬Ã€ [nuclei-templates](https://github.com/maux339-cpu/nuclei-templates) â”¬Ã€ [reconftw](https://github.com/maux339-cpu/reconftw)  ### DeFi base  [DeFiHackLabs](https://github.com/maux339-cpu/DeFiHackLabs) â”¬Ã€ [foundry](https://github.com/maux339-cpu/foundry) â”¬Ã€ [slither](https://github.com/maux339-cpu/slither) â”¬Ã€ [echidna](https://github.com/maux339-cpu/echidna) â”¬Ã€ [medusa](https://github.com/maux339-cpu/medusa) â”¬Ã€ [building-secure-contracts](https://github.com/maux339-cpu/building-secure-contracts) â”¬Ã€ [smart-contract-attack-vectors](https://github.com/maux339-cpu/smart-contract-attack-vectors) â”¬Ã€ [web3-security-resources](https://github.com/maux339-cpu/web3-security-resources) â”¬Ã€ [smart-contract-vulndb](https://github.com/maux339-cpu/smart-contract-vulndb) â”¬Ã€ [web3-bug-bounty-hunting-ai-skills](https://github.com/maux339-cpu/web3-bug-bounty-hunting-ai-skills) â”¬Ã€ [.context](https://github.com/maux339-cpu/.context)  ### AI pentest (wave 1)  [hexstrike-ai](https://github.com/maux339-cpu/hexstrike-ai) â”¬Ã€ [pentestagent](https://github.com/maux339-cpu/pentestagent) â”¬Ã€ [xalgorix](https://github.com/maux339-cpu/xalgorix) â”¬Ã€ [hexstrike-ai-private](https://github.com/maux339-cpu/hexstrike-ai-private) â”¬Ã€ [pombocyber-skills-cybersec](https://github.com/maux339-cpu/pombocyber-skills-cybersec)  ---  ## Pipelines sugeridos  ### Audit / PoC DeFi (avancado)  ```text aderyn | slither | 4naly3er     -> static mythril | halmos                -> symbolic / formal-ish foundry fork + echidna/medusa   -> fuzz + invariant heimdall-rs                     -> bytecode nao verificado DeFiHackLabs + DVD              -> patterns reais + lab solodit / claudit + vulns list  -> research de findings ```  ### On-chain investigation (fund flow / attribution)  ```text 1. Explorer nativo (Etherscan/Solscan/Tronscan) + metasuites 2. Grafo: MetaSleuth (SaaS) | graphsense-* (self-host) | Orbit (BTC) 3. Labels: etherscan-labels + Arkham (SaaS) + graphsense-tagpacks 4. Bridges / timing / CEX hot (metodologia On-Chain-Investigations-Tools-List) 5. Lab phishing: impersonator (+ extension) 6. ETH offline: trueblocks-core 7. SOL: helius-sdk + xray 8. Case file: Obsidian (local) + Crypto-Asset-Tracing-Handbook 9. Off-chain OSINT: GHunt | holehe | maigret | spiderfoot (waves 1-2) 10. Endpoint: Tether freeze / oficio CEX (nao e repo) ```  ### OSINT  ```text GHunt | holehe | h8mail | maigret | social-analyzer web-check | GitSint | MetaDetective | OpenOSINT Legendary_OSINT + awesome_osint_blockchain_analysis ```  ### Pentest web / bug bounty  ```text reconftw | amass | nuclei | PayloadsAllTheThings pentagi | PentestGPT | pentest-ai | hexstrike-ai | pentestagent ```  ### Ops / leaks (crypto)  ```text trufflehog  -> keys/seeds em repos e deps ```  ---  ## Fora de proposito  - Wallet drainers / seed crackers / malware SEO - MEV bots shillers - Reuploads duvidosos (sempre preferir upstream canonico) - Claims "Chainalysis free no browser" sem repo/validacao publica  ---  ## Sync  ```bash gh repo sync maux339-cpu/NOME -b BRANCH ```  ### Sync batch Wave 4 (on-chain)  ```bash for r in On-Chain-Investigations-Tools-List Crypto-OpSec-SelfGuard-RoadMap ultimate-defi-research-base DeFi-Developer-Road-Map non-typical-OSINT-guide awesome_osint_blockchain_analysis Legendary_Crypto Legendary_OSINT Crypto-Asset-Tracing-Handbook Blockchain-dark-forest-selfguard-handbook Knowledge-Base metasuites metasleuth_resources Phalcon graphsense-dashboard graphsense-lib graphsense-tagpacks GraphSense-Maltego-transform impersonator impersonator-extension Orbit trueblocks-core rolod0x etherscan-labels helius-sdk xray a_TON_of_privacy atop_maltego; do   gh repo sync "maux339-cpu/$r" || true done ```  Indice: este repo â”¬Ã€ Conta: **maux339-cpu** â”¬Ã€ Waves: **1–6.1**

