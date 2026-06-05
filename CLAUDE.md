# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Chinese-language science fiction novel project titled **《生命游戏》** (Game of Life). It is a collaborative creative writing effort between the author and AI (DeepSeek). The author has stated they don't intend to write a full novel — this is an exploratory world-building and storytelling playground.

## Repository Structure

```
情节/                   # Plot / Story chapters (organized by story arc)
├── 巴斯德上海报道/      # Basde the seagull journalist's Shanghai reports
├── 人类叛乱/            # Pascal's rebellion against the Antarctic Republic
├── 火星危机/            # Mars diplomatic crisis
└── 寓言与插曲/          # Standalone fables and character profiles
设定集合/                # World-building / Setting documents
├── 核心设定/            # Core setting (philosophy, governance)
├── 技术设定/            # Technical setting (network protocols, OS, energy)
│   ├── 网络协议/
│   ├── 操作系统/
│   ├── 信息技术委员会/
│   └── 其他协议/
├── 社会与政治/          # Society & politics
├── 势力设定/            # Faction settings
│   ├── 南极共和国/
│   ├── 美联国/
│   └── 亚洲联合体/
└── 名词解释/            # Glossary
```

## Key World-Building Facts

- **Antarctic Republic** (南极共和国): Founded 2058. Constitution establishes **万物** (all intelligent species) as the ruling class, led by the **南极共产党** (Antarctic Communist Party), with **广义数据主义** (Generalized Dataism) as the core ideology (equivalent to Marxism for socialist states). Core motto: "万物有智，和谐共生" (All things have intelligence, harmonious coexistence). Head of state: **谢海** (信天翁/albatross), concurrently General Secretary of the Antarctic Communist Party Central Committee (南共中央总书记).
- **Key government figures**: 谢海 (head of state), 黑山/棕熊 (foreign minister), 拉布拉斯/基准人类 (Human Reservation Communication & Stability Director — NOT president), 花贤/鸡 (judge), 棱镜/硅基智能 (chief justice).
- **Silicon-based intelligences** (硅基智能): Quantum computing arrays/networks that manage Antarctica's IT infrastructure. They are **ordinary citizens** of the Republic, NOT rulers or gods. (Dr. Heisman's view of them as "gods" is his personal perspective, not objective fact.)
- **Uplifted animals**: Penguins, bears, orangutans, ants, chickens, octopuses, etc. are full citizens with equal rights. Many hold government and professional positions.
- **Baseline humans** (基准人类): Most humans who rejected the new order were forcibly relocated to reservations (保留地) outside the capital.
- **晶言** (Crystal Speech): A 3-dimensional conceptual language invented by silicon intelligences, far more complex than Chinese or English.
- **ZeroProtocol** (ZP协议): The dominant network-layer protocol, designed from scratch by super-intelligences. Incompatible with IPv4/IPv6. Mandatory routing for all connected devices.

## File Naming Conventions

- All files use `.txt` extension with UTF-8 encoding
- Chapter files follow pattern: `年份/描述.txt` or `年份/角色名-事件.txt`
- Setting files are organized by category folders

## Working with This Repository

- All content is in **Simplified Chinese** (zh-CN)
- Files are plain text (`.txt`), edited directly
- The project has no build system, tests, or linting — it's pure creative writing
- Git is used for version control of the text files
- When editing, preserve the existing indentation style (spaces, not tabs) and the narrative tone consistent with the surrounding text
- Story chapters and setting documents should maintain internal consistency with the established world-building facts listed above
