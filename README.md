# Croppick Scoop Bucket

[![Tests](https://github.com/EvaldasVasiliauskas/scoop-croppick/actions/workflows/ci.yml/badge.svg)](https://github.com/EvaldasVasiliauskas/scoop-croppick/actions/workflows/ci.yml) [![Excavator](https://github.com/EvaldasVasiliauskas/scoop-croppick/actions/workflows/excavator.yml/badge.svg)](https://github.com/EvaldasVasiliauskas/scoop-croppick/actions/workflows/excavator.yml)

The official [Scoop](https://scoop.sh) bucket for [Croppick](https://croppick.com) apps.

## Apps

| App | Description |
| --- | ----------- |
| [CroppickVoice](https://voice.croppick.com) | Free on-device voice typing for any app, plus Crop & Speak — annotate a region of your screen and narrate it into ChatGPT or Claude. |

## Install

```pwsh
scoop bucket add croppick https://github.com/EvaldasVasiliauskas/scoop-croppick
scoop install croppick/croppickvoice
```

## Update

```pwsh
scoop update croppickvoice
```

Manifests track the publisher release feed at
`https://dl-voice.croppick.com/latest.json` and are refreshed automatically.
