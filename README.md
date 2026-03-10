# OpenClaw Skills

Custom or improved original skills for OpenClaw that I use.

## gog

Improved standard `gog` skill.

- Support of `SecretRef` via `GOG_KEYRING_PASSWORD`.
- Added Tasks guidance.

## groq-whisper-api

Transcribe audio via Groq Automatic Speech Recognition (ASR) models (Whisper), ~10x cheaper than via built-in OpenAI's `openai-whisper-api`.

- Straight replacement of `openai-whisper-api`.
- Published on [https://clawhub.ai/maxceem/groq-whisper-api](https://clawhub.ai/maxceem/groq-whisper-api).

## notion

Improved standard `notion` skill.

- Support of `SecretRef` via `NOTION_SECRET`.
- Added comments guidance.

## tavily

Improved [https://clawhub.ai/arun-8687/tavily-search](tavily-search) from clawhub.

- Fixed metadata namespace from `clawbot` to `openclaw` otherwise `SecretRef` doesn't work.
- Renamed folder to `tavily` to match skill `name`.

## License

[MIT](./LICENSE)
