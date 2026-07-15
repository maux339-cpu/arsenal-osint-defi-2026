# Arsenal OSINT + DeFi + Pentest (2026)

Inventario dos **forks** na conta [maux339-cpu](https://github.com/maux339-cpu).
Pesquisa autorizada / bug bounty / audit. **Nao e kit de crime.**

| Wave | Data | Foco |
|------|------|------|
| 1 | 2026-07-15 | OSINT core + recon + DeFi base + HexStrike |
| 2 | 2026-07-15 | Gaps OSINT (web-check, GHunt, social-analyzer...) |
| 3 | 2026-07-15 | Crypto audit avancado + AI pentest + payloads |
| 4 | 2026-07-15 | **On-chain investigations** (Zach stack + GraphSense + lists) — 28 forks |

---

## Wave 4 — On-chain investigations / blockchain forensics

Fonte: varredura X (lista ZachXBT + OffcierCia + SlowMist + GraphSense + BlockSec) + check de repos publicos no GitHub.
**28 forks novos** (nenhum duplicado com waves 1–3).

### Listas / handbooks (metodologia)

| Fork | Upstream | Funcao |
|------|----------|--------|
| [On-Chain-Investigations-Tools-List](https://github.com/maux339-cpu/On-Chain-Investigations-Tools-List) | OffcierCia | Catalogo canonico de tools de investigacao on-chain |
| [Crypto-OpSec-SelfGuard-RoadMap](https://github.com/maux339-cpu/Crypto-OpSec-SelfGuard-RoadMap) | OffcierCia | OpSec crypto / self-guard |
| [ultimate-defi-research-base](https://github.com/maux339-cpu/ultimate-defi-research-base) | OffcierCia | Research + tools DeFi |
| [DeFi-Developer-Road-Map](https://github.com/maux339-cpu/DeFi-Developer-Road-Map) | OffcierCia | Roadmap dev DeFi |
| [non-typical-OSINT-guide](https://github.com/maux339-cpu/non-typical-OSINT-guide) | OffcierCia | Guia OSINT nao-tipico |
| [awesome_osint_blockchain_analysis](https://github.com/maux339-cpu/awesome_osint_blockchain_analysis) | aaarghhh | Awesome OSINT blockchain |
| [Legendary_Crypto](https://github.com/maux339-cpu/Legendary_Crypto) | K2SOsint | Crypto OSINT / AML / forensics |
| [Legendary_OSINT](https://github.com/maux339-cpu/Legendary_OSINT) | K2SOsint | Meta-lista OSINT (CTI/AML/KYC) |
| [Crypto-Asset-Tracing-Handbook](https://github.com/maux339-cpu/Crypto-Asset-Tracing-Handbook) | slowmist | Manual de tracing de ativos |
| [Blockchain-dark-forest-selfguard-handbook](https://github.com/maux339-cpu/Blockchain-dark-forest-selfguard-handbook) | slowmist | Handbook dark forest / defesa |
| [Knowledge-Base](https://github.com/maux339-cpu/Knowledge-Base) | slowmist | KB SlowMist |

### Codigo / tools open (forensics + suporte)

| Fork | Upstream | Funcao |
|------|----------|--------|
| [metasuites](https://github.com/maux339-cpu/metasuites) | blocksecteam | Extensao browser (labels em explorers) — stack Zach |
| [metasleuth_resources](https://github.com/maux339-cpu/metasleuth_resources) | blocksecteam | Reports/resources MetaSleuth (core SaaS) |
| [Phalcon](https://github.com/maux339-cpu/Phalcon) | blocksecteam | Tx explorer / debug BlockSec |
| [graphsense-dashboard](https://github.com/maux339-cpu/graphsense-dashboard) | graphsense | Dashboard forensics self-host |
| [graphsense-lib](https://github.com/maux339-cpu/graphsense-lib) | graphsense | Backend/CLI GraphSense |
| [graphsense-tagpacks](https://github.com/maux339-cpu/graphsense-tagpacks) | graphsense | TagPacks publicos (labels) |
| [GraphSense-Maltego-transform](https://github.com/maux339-cpu/GraphSense-Maltego-transform) | INTERPOL-Innovation-Centre | Transform Maltego + GraphSense |
| [impersonator](https://github.com/maux339-cpu/impersonator) | impersonator-eth | Spoof login dApp (lab) — stack Zach |
| [impersonator-extension](https://github.com/maux339-cpu/impersonator-extension) | impersonator-eth | Extensao Impersonator |
| [Orbit](https://github.com/maux339-cpu/Orbit) | s0md3v | Graph BTC / OSINT on-chain |
| [trueblocks-core](https://github.com/maux339-cpu/trueblocks-core) | TrueBlocks | Indexador ETH local / forensics offline |
| [rolod0x](https://github.com/maux339-cpu/rolod0x) | rolod0x | Address book privado multi-site |
| [etherscan-labels](https://github.com/maux339-cpu/etherscan-labels) | brianleect | Dump labels EVM (CSV/JSON) |
| [helius-sdk](https://github.com/maux339-cpu/helius-sdk) | helius-labs | SDK Solana (API surveillance) |
| [xray](https://github.com/maux339-cpu/xray) | helius-labs | Explorer SOL human-readable |
| [a_TON_of_privacy](https://github.com/maux339-cpu/a_TON_of_privacy) | aaarghhh | OSINT/investigacao TON |
| [atop_maltego](https://github.com/maux339-cpu/atop_maltego) | aaarghhh | Maltego transforms TON |

### SaaS / enterprise **sem** fork (nao tem codigo publico util)

TRM · Chainalysis · Elliptic · Arkham · Cielo · Nansen · Breadcrumbs (produto) · MetaSleuth core · MistTrack · Snusbase · IntelX · LeakPeek · OSINT Industries · Spur · Cavalier · ZachXBT (0 public repos) · wallet-scanner.app (claim sem repo confiavel)

---

## Wave 3 — Crypto / SC ofensivo + pentest avancado

### Smart contract / DeFi (audit + lab)

| Fork | Upstream | Funcao |
|------|----------|--------|
| [mythril](https://github.com/maux339-cpu/mythril) | ConsenSysDiligence | Symbolic execution EVM |
| [heimdall-rs](https://github.com/maux339-cpu/heimdall-rs) | Jon-Becker | Decompile / disasm bytecode |
| [halmos](https://github.com/maux339-cpu/halmos) | a16z | Symbolic testing / properties |
| [halmos-cheatcodes](https://github.com/maux339-cpu/halmos-cheatcodes) | a16z | Cheatcodes Halmos |
| [aderyn](https://github.com/maux339-cpu/aderyn) | Cyfrin | Static analyzer moderno (+ MCP) |
| [4naly3er](https://github.com/maux339-cpu/4naly3er) | Picodes | Static analyzer estilo C4 |
| [smart-contract-vulnerabilities](https://github.com/maux339-cpu/smart-contract-vulnerabilities) | kadenzipfel | Catalogo de vulns (AI agents) |
| [damn-vulnerable-defi](https://github.com/maux339-cpu/damn-vulnerable-defi) | OpenZeppelin | Lab ofensivo DeFi |
| [damn-vulnerable-defi-foundry](https://github.com/maux339-cpu/damn-vulnerable-defi-foundry) | nicolasgarcia214 | DVD em Foundry |
| [damn-vulnerable-defi-v4-solutions](https://github.com/maux339-cpu/damn-vulnerable-defi-v4-solutions) | SunWeb3Sec | Solucoes DVD v4 |
| [solodit_content](https://github.com/maux339-cpu/solodit_content) | solodit | Conteudo / findings Solodit |
| [claudit](https://github.com/maux339-cpu/claudit) | marchev | MCP search Solodit findings |
| [not-so-smart-contracts](https://github.com/maux339-cpu/not-so-smart-contracts) | crytic | Exemplos de bugs classicos |

### AI pentest / red team / web payloads

| Fork | Upstream | Funcao |
|------|----------|--------|
| [pentagi](https://github.com/maux339-cpu/pentagi) | vxcontrol | AI multi-agent pentest autonomo (~20k) |
| [PentestGPT](https://github.com/maux339-cpu/PentestGPT) | GreyDGL | LLM pentest framework |
| [pentest-ai](https://github.com/maux339-cpu/pentest-ai) | 0xSteph | MCP 205 tools + agents OWASP |
| [pentest-ai-agents](https://github.com/maux339-cpu/pentest-ai-agents) | 0xSteph | Subagents Claude Code ofensivos |
| [PayloadsAllTheThings](https://github.com/maux339-cpu/PayloadsAllTheThings) | swisskyrepo | Biblia de payloads web |
| [awesome-pentest](https://github.com/maux339-cpu/awesome-pentest) | enaqx | Meta-lista pentest |
| [promptfoo](https://github.com/maux339-cpu/promptfoo) | promptfoo | Red team LLM / agents |

---

## Wave 2 — OSINT (gaps X)

| Fork | Upstream |
|------|----------|
| [web-check](https://github.com/maux339-cpu/web-check) | lissy93 |
| [GHunt](https://github.com/maux339-cpu/GHunt) | mxrch |
| [ghunt_companion](https://github.com/maux339-cpu/ghunt_companion) | mxrch |
| [social-analyzer](https://github.com/maux339-cpu/social-analyzer) | qeeqbox |
| [Osintgram](https://github.com/maux339-cpu/Osintgram) | Datalux |
| [toutatis](https://github.com/maux339-cpu/toutatis) | megadose |
| [robin](https://github.com/maux339-cpu/robin) | apurvsinghgautam |
| [dark-web-osint-tools](https://github.com/maux339-cpu/dark-web-osint-tools) | apurvsinghgautam |
| [recon-ng](https://github.com/maux339-cpu/recon-ng) | lanmaster53 |
| [sn0int](https://github.com/maux339-cpu/sn0int) | kpcyrd |
| [OSINT-Cheat-sheet](https://github.com/maux339-cpu/OSINT-Cheat-sheet) | Jieyab89 |
| [awesome-osint-arsenal](https://github.com/maux339-cpu/awesome-osint-arsenal) | rawfilejson |
| [OpenOSINT](https://github.com/maux339-cpu/OpenOSINT) | OpenOSINT |
| [MetaDetective](https://github.com/maux339-cpu/MetaDetective) | franckferman |
| [GitSint](https://github.com/maux339-cpu/GitSint) | N0rz3 |

---

## Wave 1 — OSINT core + recon + DeFi base

### OSINT

[awesome-osint](https://github.com/maux339-cpu/awesome-osint) · [osint_stuff_tool_collection](https://github.com/maux339-cpu/osint_stuff_tool_collection) · [OSINT-BIBLE](https://github.com/maux339-cpu/OSINT-BIBLE) · [sherlock](https://github.com/maux339-cpu/sherlock) · [maigret](https://github.com/maux339-cpu/maigret) · [socid-extractor](https://github.com/maux339-cpu/socid-extractor) · [blackbird](https://github.com/maux339-cpu/blackbird) · [holehe](https://github.com/maux339-cpu/holehe) · [h8mail](https://github.com/maux339-cpu/h8mail) · [phoneinfoga](https://github.com/maux339-cpu/phoneinfoga) · [theHarvester](https://github.com/maux339-cpu/theHarvester) · [spiderfoot](https://github.com/maux339-cpu/spiderfoot) · [Photon](https://github.com/maux339-cpu/Photon) · [H4X-Tools](https://github.com/maux339-cpu/H4X-Tools) · [trufflehog](https://github.com/maux339-cpu/trufflehog)

### Recon web

[amass](https://github.com/maux339-cpu/amass) · [subfinder](https://github.com/maux339-cpu/subfinder) · [httpx](https://github.com/maux339-cpu/httpx) · [katana](https://github.com/maux339-cpu/katana) · [nuclei](https://github.com/maux339-cpu/nuclei) · [nuclei-templates](https://github.com/maux339-cpu/nuclei-templates) · [reconftw](https://github.com/maux339-cpu/reconftw)

### DeFi base

[DeFiHackLabs](https://github.com/maux339-cpu/DeFiHackLabs) · [foundry](https://github.com/maux339-cpu/foundry) · [slither](https://github.com/maux339-cpu/slither) · [echidna](https://github.com/maux339-cpu/echidna) · [medusa](https://github.com/maux339-cpu/medusa) · [building-secure-contracts](https://github.com/maux339-cpu/building-secure-contracts) · [smart-contract-attack-vectors](https://github.com/maux339-cpu/smart-contract-attack-vectors) · [web3-security-resources](https://github.com/maux339-cpu/web3-security-resources) · [smart-contract-vulndb](https://github.com/maux339-cpu/smart-contract-vulndb) · [web3-bug-bounty-hunting-ai-skills](https://github.com/maux339-cpu/web3-bug-bounty-hunting-ai-skills) · [.context](https://github.com/maux339-cpu/.context)

### AI pentest (wave 1)

[hexstrike-ai](https://github.com/maux339-cpu/hexstrike-ai) · [pentestagent](https://github.com/maux339-cpu/pentestagent) · [xalgorix](https://github.com/maux339-cpu/xalgorix) · [hexstrike-ai-private](https://github.com/maux339-cpu/hexstrike-ai-private) · [pombocyber-skills-cybersec](https://github.com/maux339-cpu/pombocyber-skills-cybersec)

---

## Pipelines sugeridos

### Audit / PoC DeFi (avancado)

```text
aderyn | slither | 4naly3er     -> static
mythril | halmos                -> symbolic / formal-ish
foundry fork + echidna/medusa   -> fuzz + invariant
heimdall-rs                     -> bytecode nao verificado
DeFiHackLabs + DVD              -> patterns reais + lab
solodit / claudit + vulns list  -> research de findings
```

### On-chain investigation (fund flow / attribution)

```text
1. Explorer nativo (Etherscan/Solscan/Tronscan) + metasuites
2. Grafo: MetaSleuth (SaaS) | graphsense-* (self-host) | Orbit (BTC)
3. Labels: etherscan-labels + Arkham (SaaS) + graphsense-tagpacks
4. Bridges / timing / CEX hot (metodologia On-Chain-Investigations-Tools-List)
5. Lab phishing: impersonator (+ extension)
6. ETH offline: trueblocks-core
7. SOL: helius-sdk + xray
8. Case file: Obsidian (local) + Crypto-Asset-Tracing-Handbook
9. Off-chain OSINT: GHunt | holehe | maigret | spiderfoot (waves 1-2)
10. Endpoint: Tether freeze / oficio CEX (nao e repo)
```

### OSINT

```text
GHunt | holehe | h8mail | maigret | social-analyzer
web-check | GitSint | MetaDetective | OpenOSINT
Legendary_OSINT + awesome_osint_blockchain_analysis
```

### Pentest web / bug bounty

```text
reconftw | amass | nuclei | PayloadsAllTheThings
pentagi | PentestGPT | pentest-ai | hexstrike-ai | pentestagent
```

### Ops / leaks (crypto)

```text
trufflehog  -> keys/seeds em repos e deps
```

---

## Fora de proposito

- Wallet drainers / seed crackers / malware SEO
- MEV bots shillers
- Reuploads duvidosos (sempre preferir upstream canonico)
- Claims "Chainalysis free no browser" sem repo/validacao publica

---

## Sync

```bash
gh repo sync maux339-cpu/NOME -b BRANCH
```

### Sync batch Wave 4 (on-chain)

```bash
for r in On-Chain-Investigations-Tools-List Crypto-OpSec-SelfGuard-RoadMap ultimate-defi-research-base DeFi-Developer-Road-Map non-typical-OSINT-guide awesome_osint_blockchain_analysis Legendary_Crypto Legendary_OSINT Crypto-Asset-Tracing-Handbook Blockchain-dark-forest-selfguard-handbook Knowledge-Base metasuites metasleuth_resources Phalcon graphsense-dashboard graphsense-lib graphsense-tagpacks GraphSense-Maltego-transform impersonator impersonator-extension Orbit trueblocks-core rolod0x etherscan-labels helius-sdk xray a_TON_of_privacy atop_maltego; do
  gh repo sync "maux339-cpu/$r" || true
done
```

Indice: este repo · Conta: **maux339-cpu** · Waves: **1–4**
