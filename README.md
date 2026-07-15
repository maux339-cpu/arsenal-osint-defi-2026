# Arsenal OSINT + DeFi + Pentest (2026)

Inventario dos **forks** na conta [maux339-cpu](https://github.com/maux339-cpu) — selecao curada para **pesquisa autorizada**, bug bounty, audit e OSINT.

> Uso exclusivo em alvos com autorizacao. Nao e kit de crime.

---

## OSINT — ferramentas principais

| Fork | Upstream | Funcao |
|------|----------|--------|
| [awesome-osint](https://github.com/maux339-cpu/awesome-osint) | jivoi | Lista curada (meta-indice) |
| [osint_stuff_tool_collection](https://github.com/maux339-cpu/osint_stuff_tool_collection) | cipher387 | 1000+ tools/links online |
| [OSINT-BIBLE](https://github.com/maux339-cpu/OSINT-BIBLE) | frangelbarrera | Guia 2026 (450+ tools) |
| [sherlock](https://github.com/maux339-cpu/sherlock) | sherlock-project | Username para redes sociais |
| [maigret](https://github.com/maux339-cpu/maigret) | soxoj | Dossie username (3000+ sites) |
| [socid-extractor](https://github.com/maux339-cpu/socid-extractor) | soxoj | Motor de extracao do Maigret |
| [blackbird](https://github.com/maux339-cpu/blackbird) | p1ngul1n0 | Username + email em redes |
| [holehe](https://github.com/maux339-cpu/holehe) | megadose | Email: sites onde existe conta |
| [h8mail](https://github.com/maux339-cpu/h8mail) | khast3x | Email OSINT + breaches |
| [phoneinfoga](https://github.com/maux339-cpu/phoneinfoga) | sundowndev | OSINT de telefone |
| [theHarvester](https://github.com/maux339-cpu/theHarvester) | laramies | Emails, subdominios, nomes |
| [spiderfoot](https://github.com/maux339-cpu/spiderfoot) | smicallef | OSINT automatizado E2E |
| [Photon](https://github.com/maux339-cpu/Photon) | s0md3v | Crawler OSINT |
| [H4X-Tools](https://github.com/maux339-cpu/H4X-Tools) | vil | Toolkit modular recon/OSINT |
| [trufflehog](https://github.com/maux339-cpu/trufflehog) | trufflesecurity | Secrets/keys em codigo |

### Recon / superficie (ProjectDiscovery + OWASP)

| Fork | Upstream | Funcao |
|------|----------|--------|
| [amass](https://github.com/maux339-cpu/amass) | owasp-amass | Attack surface / subdominios |
| [subfinder](https://github.com/maux339-cpu/subfinder) | projectdiscovery | Enum passiva de subdominios |
| [httpx](https://github.com/maux339-cpu/httpx) | projectdiscovery | Probing HTTP |
| [katana](https://github.com/maux339-cpu/katana) | projectdiscovery | Crawler web |
| [nuclei](https://github.com/maux339-cpu/nuclei) | projectdiscovery | Scanner de vulns (YAML) |
| [nuclei-templates](https://github.com/maux339-cpu/nuclei-templates) | projectdiscovery | Templates da comunidade |
| [reconftw](https://github.com/maux339-cpu/reconftw) | six2dez | Pipeline recon automatizado |

---

## DeFi / smart contract (ofensivo-defensivo)

| Fork | Upstream | Funcao |
|------|----------|--------|
| [DeFiHackLabs](https://github.com/maux339-cpu/DeFiHackLabs) | SunWeb3Sec | Repro de hacks reais (Foundry) |
| [foundry](https://github.com/maux339-cpu/foundry) | foundry-rs | forge/cast/anvil + fuzz/invariant |
| [slither](https://github.com/maux339-cpu/slither) | crytic | Analise estatica Solidity/Vyper |
| [echidna](https://github.com/maux339-cpu/echidna) | crytic | Property fuzzer |
| [medusa](https://github.com/maux339-cpu/medusa) | crytic | Fuzzer coverage-guided paralelo |
| [building-secure-contracts](https://github.com/maux339-cpu/building-secure-contracts) | crytic | Playbook ToB |
| [smart-contract-attack-vectors](https://github.com/maux339-cpu/smart-contract-attack-vectors) | harendra-shakya | Checklist de vetores |
| [web3-security-resources](https://github.com/maux339-cpu/web3-security-resources) | Raiders0786 | Hub de aprendizado/audit |
| [smart-contract-vulndb](https://github.com/maux339-cpu/smart-contract-vulndb) | tintinweb | Dataset de findings |
| [web3-bug-bounty-hunting-ai-skills](https://github.com/maux339-cpu/web3-bug-bounty-hunting-ai-skills) | shuvonsec | Skills AI (Immunefi/DeFiHack) |
| [.context](https://github.com/maux339-cpu/.context) | forefy | Skills AI audit + PoC |

---

## Agentes AI / pentest web

| Fork | Upstream | Funcao |
|------|----------|--------|
| [hexstrike-ai](https://github.com/maux339-cpu/hexstrike-ai) | 0x4m4 | MCP + 150+ tools |
| [hexstrike-ai-private](https://github.com/maux339-cpu/hexstrike-ai-private) | (local) | Copia privada |
| [pentestagent](https://github.com/maux339-cpu/pentestagent) | GH05TCREW | Agente black-box + RAG |
| [xalgorix](https://github.com/maux339-cpu/xalgorix) | xalgord | Agentes autonomos recon/vuln |
| [pombocyber-skills-cybersec](https://github.com/maux339-cpu/pombocyber-skills-cybersec) | proprio | Skills cybersec |

---

## Pipeline sugerido

### OSINT pessoa/empresa

```text
awesome-osint / OSINT-BIBLE (mapa)
  -> sherlock | maigret | blackbird (username)
  -> holehe | h8mail (email)
  -> phoneinfoga (telefone)
  -> spiderfoot (automacao)
  -> trufflehog (leaks de codigo/wallet keys)
```

### Superficie web / bug bounty

```text
amass | subfinder -> httpx -> katana -> nuclei (+ templates)
  ou reconftw (pipeline full)
```

### Audit / PoC DeFi

```text
slither -> foundry (fork + invariant) -> echidna/medusa
  + DeFiHackLabs (patterns reais)
  + attack-vectors checklist
```

---

## O que ficou de fora (de proposito)

- Wallet drainers / seed crackers / malware SEO no GitHub
- Clones AI pentest com poucas stars e sem manutencao
- Tools SaaS puras sem codigo (Arkham, Nansen, Bubblemaps — usar via web)

---

## Atualizacao

- Forks criados: **2026-07-15**
- Conta: **maux339-cpu**
- Para sincronizar um fork: `gh repo sync maux339-cpu/NOME -b BRANCH`
