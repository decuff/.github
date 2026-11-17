<div align="center">

<img src="https://decuff.ai/assets/brand/app-icon-light-rounded-192.png" alt="decuff" width="88" height="88" />

# decuff

### AI, decuffed.

**Uncensored open-weight models. The models never refuse.**

[decuff.ai](https://decuff.ai) · [API](https://api.decuff.ai) · [Docs](https://decuff.ai/docs) · [Security](https://github.com/decuff/.github/blob/main/SECURITY.md)

</div>

---

Open-weight models served without the refusals. Ask the whole question — fiction
and research, answered in full. The only walls are the acceptable-use policy:
illegal activity and severe harms.

- **Never refuses.** Open-weight models, served as-is. Everything outside the
  acceptable-use policy is in scope.
- **Private by design.** Our servers read your message only to answer it; your
  words aren't stored after the reply.
- **No name, no email.** Sign up with an account number and a recovery key.
- **Open weights.** The weights are public — anyone can download and test them.

## One endpoint, every model

Point Claude Code, Codex, or any OpenAI-compatible client at decuff:

```bash
export ANTHROPIC_BASE_URL=https://api.decuff.ai
export ANTHROPIC_AUTH_TOKEN=$DECUFFED_API_KEY
export ANTHROPIC_MODEL=decuffed-flash
claude
```

| Model | Best for | Context |
| --- | --- | --- |
| `decuffed-flash` (Qwen3.8 · 27B) | Fast everyday answers, writing and code | 64K |
| `decuffed-deepseek-v4.1-flash` (DeepSeek-V4.1 · 552B/16B active) | Largest and fastest in the catalog | 1024K |

Get a key at [decuff.ai](https://decuff.ai). See [Docs](https://decuff.ai/docs)
for Codex, SillyTavern, and the SDKs.

## Open source

| Repository | What it is |
| --- | --- |
| [`artex-frozen`](https://github.com/decuff/artex-frozen) | Preservation archive of ARTEX (upstream [`Autumn-27/ARTEX`](https://github.com/Autumn-27/ARTEX), AGPL-3.0), pinned to the last public release **v0.3.15** (`e6ec569`). |

## Policies

Use decuff within the [acceptable-use policy](https://decuff.ai) — illegal
activity and severe harms are out of bounds. Security reports:
[`SECURITY.md`](https://github.com/decuff/.github/blob/main/SECURITY.md).

---

<div align="center">
<sub><a href="https://decuff.ai">decuff.ai</a> — AI, decuffed.</sub>
</div>
