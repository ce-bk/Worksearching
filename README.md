# Job search skills for Claude

Four Claude skills for running a product management job search, from networking and tailoring a CV through interview prep to salary negotiation. They're generic on purpose: each one asks for your own base profile the first time you use it, so anyone can use them.

| Skill | What it does |
|---|---|
| [`job-search-cv-tailor`](skills/job-search-cv-tailor/SKILL.md) | Builds a base profile and personas, scores a job description against it, and produces a one-page ATS-friendly CV and a cover letter. |
| [`pm-interview-prep`](skills/pm-interview-prep/SKILL.md) | Coaches STAR behavioural answers, structures product sense answers, and plans a pitch deck or case study. |
| [`pm-networking-outreach`](skills/pm-networking-outreach/SKILL.md) | Maps your network against target companies, drafts warm and cold messages and referral asks, preps coffee chats, and keeps follow-ups on track. |
| [`job-search-tracker`](skills/job-search-tracker/SKILL.md) | Keeps an application log, calculates interview and offer rates, finds where the funnel leaks, and prepares salary negotiation. |

## How to install

Each skill is a folder containing a `SKILL.md` file. Install whichever ones you need.

**Claude Code:** copy the folders into your skills directory.

```bash
git clone https://github.com/ce-bk/Worksearching.git
cp -r Worksearching/skills/* ~/.claude/skills/
```

**Claude.ai and the desktop app:** zip an individual skill folder (for example `job-search-cv-tailor/`) and add it as a custom skill in your settings.

## How to use

Start with `job-search-cv-tailor` on your first run. It will ask you questions one at a time and build your base profile. Keep that profile in a document you can attach to future sessions. Nothing in this repo should contain your personal details.

Then:

- Share a job description to get a match score, a gap analysis, a tailored CV and a cover letter.
- Use `pm-networking-outreach` to find a way into target companies before you apply.
- Practise with `pm-interview-prep` before interviews.
- Log each application with `job-search-tracker` so you can see what's working.

## Good practice

- Read any skill before installing it. These are instructions Claude will follow, so treat them like code you're running.
- Always check that every line of a generated CV is true before you send it. The skills are built not to invent experience, but you're the one who signs your name to it.

## Credits

The structure draws on public work from the product community, including Product Manager Skills by Dean Peters (https://github.com/deanpeters/Product-Manager-Skills) and interview frameworks from community sessions. Adapt them to your own experience.
