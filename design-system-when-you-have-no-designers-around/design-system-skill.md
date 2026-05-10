## Skill Prompt

Save the following prompt in a markdown (.md) file and feed it to your Claude, Codex or Gemini.

Claude Opus 4.7 works best.

---

```markdown
Build a complete CSS design system for a React Native mobile app for a {{business_type}} business.

Color palette: {{color_palette}}

Guiding principles:
- Taste Skill — https://github.com/leonxlnx/taste-skill
- UI/UX Pro Max Skill — https://ui-ux-pro-max-skill.nextlevelbuilder.io/
- Design for Developers — https://css-tricks.com/design-principles-for-developers-processes-and-css-tips-for-better-web-design/

Deliver:
1. Design tokens (color, space, type, shadow, radius)
2. Typography (font stack, scale, utility classes)
3. Components (buttons, cards, inputs — tokens only)

Rules: 8px grid, modern sans-serif, light + dark mode.
Output: single HTML file.

Important: you will run out of output tokens before completing the file.
Do not attempt to generate everything in one pass.
Break the output into batches, pause, and wait for confirmation before continuing.

Phase 1 ingest and generate the HTML skeleton.
Phase 2 generate and insert the design tokens in the HTML skeleton file.
Phase 3 generate and insert the typography in the HTML skeleton file.
Phase 4 generate and insert the components in the HTML skeleton file.
```


---

## Variables Prompt

This is what you paste inside your prompt window.

```markdown
business_type: brico depot
color_palette: https://coolors.co/e30612-323232-757575-f4f4f6-ffffff
```


---

### How it works

| Variable | Description | Example value |
|---|---|---|
| `{{business_type}}` | The type or name of the business | `brico depot`, `coffee shop`, `fintech startup` |
| `{{color_palette}}` | A Coolors URL or a list of hex codes | `https://coolors.co/...` or `#FF5733, #C70039` |

Swap the values in the variables prompt each time you want to reuse the skill for a different project.

[Check out the demo output](./design-system.html)

> P.S: Make sure you use an IDE like [VScode](https://code.visualstudio.com/download), [Antigravity](https://antigravity.google/download) or [Webstorm](https://www.jetbrains.com/webstorm/) for a streamlined experience. I use Webstorm.
