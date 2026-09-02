# Unsloth

Private workspace for Unsloth Studio on Apple Silicon (Metal).

Studio is installed locally at `~/.unsloth/studio`, not in this repo. Do not commit the virtualenv, model weights, or auth files.

## Launch

```bash
~/.unsloth/studio/unsloth_studio/bin/unsloth studio -p 8888
```

Open [http://127.0.0.1:8888](http://127.0.0.1:8888).

First-run admin username is `unsloth`. The generated password is in `~/.unsloth/studio/auth/.bootstrap_password` — change it after sign-in.

## Install

```bash
brew install uv
curl -fsSL https://unsloth.ai/install.sh | sh
```

If `~/.local` is not writable, run Studio with the full path above instead of the `unsloth` shim.
