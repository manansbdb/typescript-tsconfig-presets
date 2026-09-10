<p align="center">
  <img src="docs/banner.svg" alt="TypeScript tsconfig Presets banner" width="100%" />
</p>

<h1 align="center">typescript-tsconfig-presets</h1>

<p align="center">
  <strong>EN</strong> Strict tsconfig bases for Node & general TS<br/>
  <strong>PT</strong> Bases de tsconfig strict para Node e TypeScript geral
</p>

<p align="center">
  <a href="https://github.com/manansbdb/typescript-tsconfig-presets/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-22c55e?style=for-the-badge" alt="MIT" /></a>
  <img src="https://img.shields.io/badge/lang-EN%20%7C%20PT-3b82f6?style=for-the-badge" alt="EN PT" />
  <img src="https://img.shields.io/badge/topic-TypeScript-3178c6?style=for-the-badge" alt="TypeScript" />
  <a href="#support--apoio"><img src="https://img.shields.io/badge/donate-BTC-f59e0b?style=for-the-badge" alt="Donate BTC" /></a>
</p>

---

## What it does / Para que serve

| English | Português |
|---------|-----------|
| **Strict `tsconfig` presets** you can extend from — Node and general/strict bases. | **Presets `tsconfig` strict** para estender — bases Node e geral/strict. |
| Copy a preset and set `"extends"` in your project `tsconfig.json`. | Copia um preset e usa `"extends"` no `tsconfig.json` do projeto. |

```mermaid
flowchart LR
  A["📦 Preset JSON"] --> B["📄 tsconfig.json extends"]
  B --> C["🔍 tsc --strict"]
  C --> D["✅ Safer builds"]
  style A fill:#3178c6,stroke:#1e40af,color:#fff
  style B fill:#f59e0b,stroke:#b45309,color:#fff
  style C fill:#235a97,stroke:#1e3a5f,color:#fff
  style D fill:#22c55e,stroke:#15803d,color:#fff
```

---

## Install / Instalação

### 1) Clone / Clona

```bash
git clone https://github.com/manansbdb/typescript-tsconfig-presets.git
cd typescript-tsconfig-presets
```

### 2) Copy presets / Copia presets

```bash
mkdir -p /path/to/your-project/tsconfig
cp tsconfig.strict.json /path/to/your-project/tsconfig/
cp tsconfig.node.json /path/to/your-project/tsconfig/
```

### 3) Extend / Estende

```json
{
  "extends": "./tsconfig/tsconfig.strict.json",
  "include": ["src"]
}
```

### Requirements / Requisitos

- TypeScript installed in the target project
- `git`

---

## Quick start / Início rápido

```bash
git clone https://github.com/manansbdb/typescript-tsconfig-presets.git
cp typescript-tsconfig-presets/tsconfig.strict.json ./tsconfig.strict.json
# point your tsconfig.json "extends" at it
```

---

## Contents / Conteúdos

| Path | Purpose / Função |
|------|------------------|
| `tsconfig.strict.json` | Strict base |
| `tsconfig.node.json` | Node-oriented base |
| `notes.md` | Usage notes |
| `SUPPORT.md` | Donations / Doações |

---

## Project layout / Estrutura

```text
typescript-tsconfig-presets/
├── docs/banner.svg
├── tsconfig.strict.json
├── tsconfig.node.json
├── notes.md
├── SUPPORT.md
└── README.md
```

---

## Support / Apoio

Bitcoin donations welcome / Doações em Bitcoin bem-vindas:

```
bc1q0qfnlnxyum9u45stzxe0a7jnhtj4j0usfkqdjw
```

See [SUPPORT.md](./SUPPORT.md).

---

## License / Licença

[MIT](./LICENSE) © 2026 manansbdb
