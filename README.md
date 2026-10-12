# Skills for Agents

Previously, I put together a repo called [_Renaissance Man_](https://github.com/willswire/renaissance-man), which housed several skills that were intended to be "layered" upon one another to help guide an agent's approach in writing code. This seemed to work for the most part, but as the number of skills I wish to write increased, the layering paradigm no longer seemed to make sense. Also, I initially used an agent to help build the repository, which I now regret. I'm already conflicted about the role of AI in engineering, but I'm growing even more uncomfortable using AI to guide AI. [_"How perverse!"_](https://tenor.com/view/star-wars-c3p0-r2d2-machines-factory-gif-25340301)

Head to the [`skills/`](./skills/) directory to review available skills.

Please refer to the [`CONTRIBUTING.md`](./CONTRIBUTING.md) document as guide for limitations on the of use of AI for this project.

## Getting started

To use these skills with your agent of choice, follow the instructions below:

<details>
<summary><strong>Anthropic - Claude Code</strong></summary>

```bash
claude plugin marketplace add willswire/skills
claude plugin install skills@willswire
```

</details>

<details>
<summary><strong>OpenAI - ChatGPT/Codex</strong></summary>

```bash
codex plugin marketplace add willswire/skills
codex plugin add skills@willswire
```

</details>

## Acknowledgements

When building this repo, I drew inspiration from the following:

* [Matt Pocock's Skills For Real Engineers](https://github.com/mattpocock/skills)
* [My previous plugin: _Renaissance Man_](https://github.com/willswire/renaissance-man)
