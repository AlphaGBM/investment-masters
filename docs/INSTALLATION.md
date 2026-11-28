# Install and get a first result / 安装与首次使用

This is one Skill with 15 local profiles, not 15 separately installed skills. No account, market-data key or paid API is included. Method comparisons can use only the package and your authorized materials.

## Codex / Claude Code / Cursor

Use a new project directory for first setup. Inspect/back up existing skills and custom edits before any upgrade; the installer may replace a same-name copy. Do not run this blindly over an existing installation.

```sh
npx skills@1.9.0 add https://github.com/AlphaGBM/investment-masters/tree/onboarding-v1 --skill investment-masters --agent codex --copy -y
```

Replace `codex` with `claude-code` or `cursor` as needed. This pinned installer uses project `.agents/skills/` for Codex/Cursor and `.claude/skills/` for Claude Code. Do not omit `--agent` in non-interactive setup. Keep the full package, including `catalog.json` and `masters/`; copying only `SKILL.md` loses its evidence lenses. Record the installed commit from `skills-lock.json` and reload skills as your host requires. Disk installation is not proof of automatic activation or current market-data access.

## WorkBuddy / CodeBuddy directory setup

Only use this when your actual host confirms `~/.codebuddy/skills/` is its skill directory. These Linux/macOS commands use a new checkout and refuse to overwrite an existing skill or dangling symlink:

```sh
set -eu
source_dir=$(mktemp -d)
git clone --branch onboarding-v1 --depth 1 https://github.com/AlphaGBM/investment-masters.git "$source_dir/source"
git -C "$source_dir/source" rev-parse HEAD
target="$HOME/.codebuddy/skills/investment-masters"
if [ -e "$target" ] || [ -L "$target" ]; then
  printf '%s\n' 'Existing skill found: review and back up before upgrading.' >&2
  exit 1
fi
mkdir -p "$HOME/.codebuddy/skills"
mkdir "$target"
cp "$source_dir/source/SKILL.md" "$source_dir/source/catalog.json" "$source_dir/source/LICENSE" "$target/"
cp -R "$source_dir/source/masters" "$target/masters"
```

Then explicitly select/load `investment-masters` using the host's actual skill mechanism. File copying is not evidence of host loading. Prior WorkBuddy acceptance for the separate Stock Research package does not certify this package; automatic/cross-session activation remains host-dependent. Never disable TLS checks to repair a download.

## Doubao / file workflow

Get the self-contained [method ZIP](https://github.com/AlphaGBM/investment-masters/releases/download/onboarding-v1/investment-masters.zip) and matching [manifest](https://github.com/AlphaGBM/investment-masters/releases/download/onboarding-v1/investment-masters.manifest.json), or use the complete source checkout. Verify the archive SHA256 against the manifest and inspect its paths before extraction. Use a new directory; keep the root `SKILL.md`, `catalog.json` and all 15 `masters/*.md` profiles together.

Ask your file-capable host:

> 请读取 investment-masters 的 SKILL.md，用本包巴菲特与马克斯两份方法画像检查我给的观点。先给一句结论和最多三条分歧，再给出处和待核问题；不联网、不调用收费接口、不扮演本人。没有材料时先比较方法，不要编造公司数据。

This is a file workflow unless your client actually confirms native import/activation. Ordinary chat without file-reading tools is not equivalent. No other AI client is required. If a method file is missing, request that file rather than pretending it was read.

## Upgrade and feedback

`onboarding-v1` is the fixed source version for these instructions. Existing installs never update automatically. Preserve private notes/custom edits, inspect the new copy and activate it through your host; do not publish private materials as feedback. See [result examples](EXPERIENCE.md). Usage questions go to the shared [Skills Q&A](https://github.com/AlphaGBM/skills/discussions/categories/q-a); bugs use the [issue forms](https://github.com/AlphaGBM/skills/issues/new/choose), mentioning `investment-masters`.
