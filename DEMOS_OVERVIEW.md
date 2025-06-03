# 📊 Overview of Nightingale Demos

| Demo Name              | GitHub Repository (New)                                        | Old Repository Name(s)                   | Contact(s)       | Status        |
|------------------------|---------------------------------------------------------------|------------------------------------------|------------------|----------------|
| AI WhatIf              | [nightingale-aiwhatif](https://github.com/curatimeXai/nightingale-aiwhatif) | ai-whatif-v2-frontend, ai-whatif-v2-backend |         | ✅ Stable      |
| Pollution Map          | [healthmap-pollutionmap](https://github.com/curatimeXai/healthmap-pollutionmap) | pollutionmap                            | Dalia, Antoine, Lorenzo, Nidhal, Carina, Ali   | 🛠️ In Progress |
| World Heart Map        | [healthmap-worldhealthmap](https://github.com/curatimeXai/healthmap-worldhealthmap) | CardioVascular (branch `dalia`)         | Dalia            | ✅ Stable      |
| Cardiomegaly CNN       | [healthview-cardiomegaly-cnn](https://github.com/curatimeXai/healthview-cardiomegaly-cnn) | cardiovascular_cnn_backend_alt, ...frontend_alt | —      | 🛠️ In Progress |
| HeartCluster           | [nightingale-heart-cluster](https://github.com/curatimeXai/nightingale-heart-cluster) | Heart_clusters_backend, ..._frontend    | Axel M. (code)   | ✅ Stable      |
| Heart Quiz             | [healthview-echogame](https://github.com/curatimeXai/healthview-echogame) | quiz_game                                | Intisar, Shevin           | ✅ Stable      |
| HarmoniaHealthAI       | [nightingale-harmoniahealth](https://github.com/curatimeXai/nightingale-harmoniahealth) | HarmoniaHealthAI_backend, ...frontend   | —                | ✅ Stable      |
| Echo Explore           | [healthview-echoexplore](https://github.com/curatimeXai/healthview-echoexplore) | echoexplore-backend, ...frontend, ...computation | —     | ✅ Stable      |
| Lifesaver              | [nightingale-lifesaver-cpr](https://github.com/curatimeXai/nightingale-lifesaver-cpr) | cpr-chatbot series                      | —                | ❓ Unknown     |
| Bogalusa               | [nightingale-bogalusa](https://github.com/curatimeXai/nightingale-bogalusa) | XAI-heart-disease                        | —                | ❓ Unknown     |

---

> ℹ️ Repository names have been migrated to the standard `nightingale-[demo-name]` format.  
> The original names are kept in a separate column during the transition for reference.

## 🗃️ Migration Summary

As of June 2025, all legacy repositories have been centralized and archived under the [`old`](https://github.com/curatimeXai/old) repository. Active demos have been renamed for clarity and consistency.

### ✔️ Key Changes

- All obsolete repos (e.g. `DemoPage`, `Healthmap`, `ai_musicotherapy_chatbot_backend`) have been moved into the `old/` archive as subfolders.
- Historical git links (submodules) were removed to preserve a clean structure.
- A single centralized README and structured folder layout now documents legacy content.
- The repository `resources/` now holds all documentation, utility scripts, and setup guides.
- All demos follow the naming structure:
  - `nightingale-*` → core Nightingale demos
  - `healthmap-*` → environmental/air quality demos
  - `healthview-*` → cardiology/imaging demos
  - `other-*` → data tools, CSV uploaders, benchmarks

For full traceability, all renamed and migrated items are tracked inside this document.
