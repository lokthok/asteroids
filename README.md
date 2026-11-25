# asteroids
Boot.dev


## Local command `runast`

`runast` starts the game. The command only applies to this machine, so it lives in `~/.zshrc.local` instead of `dotfiles`.

Append the command below to `~/.zshrc.local` and load it:

```bash
echo "alias runast='uv run --directory ~/codeforge/github/lokthok/asteroids main.py'" >> ~/.zshrc.local
source ~/.zshrc.local
```