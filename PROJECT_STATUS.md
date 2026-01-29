# Project Status: Collections

> [!IMPORTANT]
> **Operational Rules** (Read this first!)
>
> 1.  **Version Control**: `jj` (Jujutsu) ONLY.
> 2.  **Runtime**: `node` / `npm` (Adobe Standard).
> 3.  **Content Source**: **DA -> Manual Download**.
>     - **SYNC WARNING**: The DA->GitHub link is BROKEN. The bot is installed but not pushing.
>     - **Workaround**: If you change content in DA, you must manually download `index.md` again (or configure a new sync).
>     - `fstab.yaml` MUST remain deleted/absent.

## Architecture

- **Repo**: `collections`
- **Mode**: Headless / Developer
- **Current State**: Local files manually synced from Live.

## Status

- [x] Dependencies installed (`npm install`).
- [x] `fstab.yaml` removed.
- [x] Local Preview Verified (`aem up` works).
- [!] **Bot Sync Failed**: Manual intervention required for content updates.
