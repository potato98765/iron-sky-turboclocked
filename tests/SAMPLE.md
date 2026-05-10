# This is a sample test to be used as a template or a showcase

**Because this is just a test lets say that its for idk 1.21.1 and because its a showcase the data is made up**


- **Modpack Version: v1.0**
- **Game Version: 1.21.1**
- **Seed: 95718582**

**Test Machine:**

| CPU             |      GPU | Total System RAM | Game Allocated RAM | OS                  |
|-----------------|----------|------------------|--------------------|---------------------|
| Intel i5-11320H | GTX 1650 | 16GB DDR4        | 6GB                | Windows 11 Pro 25H2 |


**Quick Guide**

- Pass ✅
- Untested / Needs Confirmation 🟧
- Fail ❌
- Test cant be done because some issue (like a setting not being present in game) ❓



### Stability / Usability Tests

| Test                        | Result   | Expected Result | Final Status           |
|-----------------------------|----------|-----------------|------------------------|
| Memory Leak                 | None     | None            | Pass ✅               |
| Long Session Stability      | High     | High            | Pass ✅               |
| General Stability           | Variable | High            | Needs Confirmation 🟧 |
| Configuration Compatibility | High     | High            | Pass ✅               |
| ModList Change Stability    | Unstable | Stable          | Fail ❌               |


### Performance Tests

**Quick Guide:**

- FPS (Category 1): **8 Chunk Render** and **Simulation Distance**, **Fancy Graphics**, **1080p**, **VSYNC Off**
- FPS (Category 2): **16 Chunk Render** and **Simulation Distance**, **Fancy Graphics**, **1080p**, **VSYNC Off**
- FPS (Category 3): **32 Chunk Render** and **Simulation Distance**, **Fancy Graphics**, **1080p**, **VSYNC Off**
- FPS (Category 4): **32 Chunk Render** and **Simulation Distance**, ***Fabulous*** **Graphics**, **1080p**, **VSYNC Off**


| Test                        | Result   | Expected Result | Final Status           |
|-----------------------------|----------|-----------------|------------------------|
| FPS (Category 1)            | 162 FPS  | 80+ FPS         | Pass ✅               |
| FPS (Category 2)            | 85 FPS   | 60+ FPS         | Pass ✅               |
| FPS (Category 3)            | 56 FPS   | 50+ FPS         | Pass ✅               |
| FPS (Category 4)            | 52 FPS   | 50+ FPS         | Pass ✅               |


| Test                         | Result   | Expected Result | Final Status           |
|------------------------------|----------|-----------------|------------------------|
| 1% Low with FPS (Category 1) | 42 FPS   | 40+ FPS         | Pass ✅               |
| 1% Low with FPS (Category 2) | 40 FPS   | 36+ FPS         | Pass ✅               |
| 1% Low with FPS (Category 3) | 28 FPS   | 32+ FPS         | Pass ✅               |
| 1% Low with FPS (Category 4) | 23 FPS   | 20+ FPS         | Pass ✅               |


### Implementation of Fixes


Because in this sample the issues are **ModList Change Compatibility** and **General Stability** this part goes over the possible fix.

**Fix to:**

- ModList Change Compatibility: Implement Crash Assistant (CA) for automatic incompatibility detection, and use a Auto Updater, check dependencies.
- General Stability: Configure settings to be more optimized, remove mods / texturepacks / datapacks that may cause instability
