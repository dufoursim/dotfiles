# dotfiles

Mes fichiers de configuration pour GitHub Codespaces.

## EdgePulse

`install.sh` installe EdgePulse dans chaque nouveau Codespace :

- `edgepulse/statusline.py` : ligne d'état de Claude Code qui garde les limites d'utilisation;
- `edgepulse/relay.py` : relais local qui les sert sur `http://127.0.0.1:4747/usage`.

VS Code redirige le port 4747 vers le PC, où le widget iCUE EdgePulse lit les données.
