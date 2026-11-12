# Do you really need an agent?

[Spanish](README.md) · [English](README.en.md)

**Traduciendo la IA · Adrián Espés · Microsoft MVP · M365 Copilot**

An interactive, orientation-only tool to help you think before building an agent. It accompanies the carousel *The first mistake when creating an agent*.

> First the need. Then the agent. And only then, the tool.

## Open the tool

**[Start "Do you really need an agent?"](https://aespese29.github.io/ia-toolbox/recursos/evaluaciones/necesitas-un-agente/)**

It opens straight in the browser via GitHub Pages — nothing to install, no sign-in. You can also [look at the `index.html` source](./index.html) and open it locally: it is a single self-contained file, with the logo and the illustration embedded as base64.

## Privacy by design

- Runs **in the browser only**. No server, no analytics, no cookies, no local storage.
- **Nothing is stored or sent.** Closing or reloading the page clears everything.
- **No free-text fields**: every answer is a closed option.
- **No confidential information requested**: only the minimum needed to give the orientation.
- The result is **guidance to help you think**, not a definitive recommendation. It never names specific products.

## Questions (9, closed options)

| # | Question | Options |
|---|---|---|
| 1 | Which task do you want to improve? | Find or look up information · Answer recurring questions · Summarise or analyse content · Guide someone through a process · Take action in other systems · I'm not sure yet |
| 2 | Who performs that task today? | Me · My team · Other areas or many people · I don't know |
| 3 | How often does it repeat? | Several times a day · Several times a week · Occasionally · I don't know |
| 4 | Does it need to look up specific information? | Yes · No · I don't know |
| 5 | Does that information change often? | Yes · No · I don't know |
| 6 | Does it need to hold a conversation with the user? | Yes · No · I don't know |
| 7 | Must it take action in other systems? | Yes · No · I don't know |
| 8 | What outcome do you expect? | Save time · More consistent answers · Fewer mistakes · Wider access to information · I don't know |
| 9 | How would you measure its usefulness? | Time spent on the task · Queries or tasks resolved · Quality or number of errors · User satisfaction · I don't know |

## Orientation logic (in this order)

1. **The need is not defined clearly enough yet**: if Q1 is "I'm not sure yet", or Q8 or Q9 is "I don't know".
2. **The need points to an agent with actions or integrations**: if Q7 is "Yes" or Q1 is "Take action".
3. **The need points to a knowledge-centred agent**: if Q4 is "Yes".
4. **A good reusable prompt may be enough**: if Q6 is "Yes".
5. **Improving the process or using a template may be enough**: in every other case.

An extra **"Data, permissions and governance"** notice is added to any result when:

- Q5 is "Yes" (the information changes often);
- it must take action in other systems;
- Q2 is "Other areas or many people".

If Q4, Q6 or Q7 are answered "I don't know", the result says so and recommends clarifying them.

## Result screen

- The orientation, with its label and a short explanation.
- **Why this orientation?**: the answers that triggered it.
- The data, permissions and governance notice, when it applies.
- **The next question worth asking yourself**.
- The closing line: *First the need. Then the agent. And only then, the tool.*

## Design and accessibility

- Brand colours: `#075E63` petrol · `#F2544B` coral · `#123238` night blue · `#FAFBF9` background.
- Typography: Manrope (headings) and Inter (body) when installed; otherwise the system font. No external resources are loaded.
- One question per screen, progress bar, "Previous" and "Next" buttons, and "Review answers" from the result.
- Native controls (radio buttons), keyboard navigable, visible focus, `aria-live` on changes, mobile-ready (from 320 px) and respects `prefers-reduced-motion`.

## Related resources

- 🧭 [Prompt, agent or skill?](../../prompt-agente-skill/) — once the need is clear and you want to generate the artifact.
- 🧩 [SKILL.md template in 6 blocks](../../plantilla-skill-md/) — to define the task after choosing the approach.

---

**Adrián Espés** · Microsoft MVP · M365 Copilot  
[adrianespes.com](https://adrianespes.com)

**Version:** 1.0
