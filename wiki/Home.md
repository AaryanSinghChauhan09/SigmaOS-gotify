# SigmaOS-gotify

SigmaOS integration component for **Gotify push notifications**.

## Commands

```bash
sigmaos-gotify install   # install package + deploy defaults
sigmaos-gotify deploy    # copy config templates to $HOME
sigmaos-gotify status    # binary/package/config report
sigmaos-gotify reset     # remove deployed config
sigmaos-gotify open      # launch the application
```

## Design

- Shell-based component manager (Omarchy-style per-app repos)
- Secure defaults; no secrets stored
- Deterministic `test.sh` with isolated `$HOME`
