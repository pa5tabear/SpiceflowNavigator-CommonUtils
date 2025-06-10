# SpiceflowNavigator-CommonUtils

**CommonUtils Agent** for SpiceflowNavigator

## Quick Start

```bash
# Clone with submodules (for agents)
git clone --recursive git@github.com:pa5tabear/SpiceflowNavigator-CommonUtils.git
cd SpiceflowNavigator-CommonUtils

# Install dependencies
make install

# Run tests
make test
```

## Agent Responsibilities

- 🔧 **Shared utilities and configurations**
- 🌐 **API clients (RunPod, etc.)**
- 📚 **Common data models and functions**
- 🔒 **Stable interfaces for all agents**

## Development Commands

```bash
make help          # Show all commands
make test          # Run tests
make install       # Install dependencies  
make dev           # Start development server
make clean         # Clean temporary files
```



## Related Repositories

- [Pipeline Agent](git@github.com:pa5tabear/SpiceflowNavigator-Pipeline) - End-to-end orchestration
- [Ingest Agent](git@github.com:pa5tabear/SpiceflowNavigator-Ingest) - RSS + transcription
- [Strategy Agent](git@github.com:pa5tabear/SpiceflowNavigator-Strategy) - Analysis + scoring
- [UI Agent](git@github.com:pa5tabear/SpiceflowNavigator-UI) - User interface
- [CommonUtils](git@github.com:pa5tabear/SpiceflowNavigator-CommonUtils) - Shared utilities

## Architecture

This repository is part of SpiceflowNavigator's **4-Agent Architecture**:

```
Pipeline ←→ Ingest
    ↓         ↓
Strategy ←→ CommonUtils ←→ UI
```

Each agent operates independently while sharing common utilities.

---
*Part of the SpiceflowNavigator 4-Agent Architecture*
