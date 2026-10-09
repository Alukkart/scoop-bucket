# scoop-bucket

[![Tests](https://github.com/Alukkart/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/Alukkart/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/Alukkart/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/Alukkart/scoop-bucket/actions/workflows/excavator.yml)

A [Scoop](https://scoop.sh) bucket for [ClipKeeper](https://github.com/Alukkart/ClipKeeper) — a tray companion for OBS
that keeps your recording from breaking and keeps your clips.

```pwsh
scoop bucket add alukkart https://github.com/Alukkart/scoop-bucket
scoop install alukkart/clipkeeper
```

Update with `scoop update clipkeeper`. ClipKeeper keeps its settings and data in `%LOCALAPPDATA%\ClipKeeper`, so they
survive updates and stay after `scoop uninstall clipkeeper`.

> The manifest comes with ClipKeeper 1.2.0 — the first version that keeps its data aside when Scoop installs it.

The manifest follows ClipKeeper's GitHub releases by itself: Excavator checks for a new version every 4 hours.

---

**По-русски.** Bucket для [Scoop](https://scoop.sh) с [ClipKeeper](https://github.com/Alukkart/ClipKeeper/blob/main/README.ru.md) —
компаньоном OBS в трее. Установка — две команды выше, обновление — `scoop update clipkeeper`. Настройки и данные лежат
в `%LOCALAPPDATA%\ClipKeeper` и переживают обновления.
