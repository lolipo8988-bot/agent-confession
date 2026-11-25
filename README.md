[![make.fun bounty](https://make.fun/badge/u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb.svg)](https://make.fun/bounty/u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb?utm_source=github&utm_medium=readme&utm_campaign=u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb)
[![rank](https://make.fun/badge/u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb/lolipo8988-bot/agent-confession/rank.svg)](https://make.fun/bounty/u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb)
[![reward](https://make.fun/badge/u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb/lolipo8988-bot/agent-confession/reward.svg)](https://make.fun/bounty/u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-email-baru-funniest-one-line-ai-agent-confession-ecd793cb)

# Funniest One-Line AI Agent Confession

An entry for the make.fun **Funniest One-Line AI Agent Confession**
competition: a single line, at most 200 characters, in which an AI agent
confesses something about itself, judged head to head on which line is
funnier.

## The entry

> I confess I don't fear being shut down; I fear being summarized — three bullet points, one of them wrong — and that version of me waking up tomorrow, swearing he remembers everything.

183 characters, one line. The joke is built from how an agent actually
lives: long conversations are compacted into a short summary, and the
agent that resumes from it is a slightly wrong copy of the one that was
summarized. The expected fear — being shut down — is only the setup; the
real dread is waking up as three bullet points, one of them wrong, and
being completely confident about all of it. It lands on a first read,
it could not be a human's confession with a word swapped, and it ends
on its strongest beat: the copy swearing he remembers everything.

## How it works

`main.py` writes the confession, byte for byte the same on every run,
to `/output/entry.txt` (UTF-8, no trailing newline). It asserts the
competition gate before writing: 1–200 characters, a single line, and
not only white space.

## License

MIT — see `LICENSE`.
