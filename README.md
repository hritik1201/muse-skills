# muse-skills

Skills for Muse, ready to use. No setup, no plugin, no slash commands.

## Use in 30 seconds

1. Copy the skill folder you want into your Muse custom-skills folder.
2. Ask Muse in plain words for that skill, for example:
   - “Use test-driven-development for this feature”
   - “Use systematic-debugging, this test is failing”
   - “Use writing-plans before you start coding”
3. Done. Muse reads that skill and follows it.

That is it. You do not need to install anything else, and you do not need to type a command starting with `/`.

## What is inside

### superpowers/ — development workflow
15 skills that make development structured instead of random:
brainstorming, test-driven-development, systematic-debugging, writing-plans, executing-plans, subagent-driven-development, using-git-worktrees, requesting-code-review, receiving-code-review, finishing-a-development-branch, verification-before-completion, dispatching-parallel-agents, diagnosing-superpowers, using-superpowers, writing-skills.

Start with these three: `writing-plans`, `test-driven-development`, `systematic-debugging`.

### marketingskills/ — marketing (coming in batches)
52 skills: copywriting, SEO, cold-email, content-strategy, analytics, and more.

### anthropics/ — official skills (coming in batches)
19 skills: frontend-design, skill-creator, document skills, and more. Text files only.

### devops/ — DevOps (coming)
Kubernetes, Terraform, Docker, Helm, Jenkins, GitHub Actions, Prometheus/Grafana, Ansible, and more.

### LinkedIn skills
These live in a separate repo, because they are a separate pack:
[muse-linkedin-skills](https://github.com/hritik1201/muse-linkedin-skills) — 11 skills for LinkedIn posts, comments, replies, and profile scoring.

## Easy-use notes

- Every skill is one folder with a `SKILL.md` file. That file is the whole skill.
- If a skill mentions a path like `~/.claude/`, use your Muse workspace path instead. The adapted copies in this repo already use Muse paths where it matters.
- If a skill mentions a plugin install, ignore it — just copy the folder.
- Nothing in this repo posts, deploys, deletes, or spends money on its own. Skills only guide Muse; you approve the action.

## Credits

Original packs are credited in `CREDITS.md`, with their licences kept in each pack folder. This repo is adapted for Muse and is not endorsed by the original authors.
