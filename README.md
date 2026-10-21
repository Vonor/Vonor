# Hi, I'm Michael 👋

Platform Engineer · Tech Lead Infrastructure, based in the Rhine Valley, Germany. Linux since 1999. I make platforms **recoverable, reproducible and boring to operate**. My own skills run on a loop: learn it, build it, wipe it, rebuild it. Repeat.

## What I deliver

- **Recovery you can rely on.** Backup and restore frameworks for containerized applications, designed so that recovery is a rehearsed procedure and not an improvisation at 3 a.m.
- **One way to ship.** A central deployment framework behind our internal developer platform: every product is its own instance with its own configuration for the app, the backups and the Kubernetes deployment. 50+ products ship the same way, so teams stop re-solving the same pipeline problems.
- **Monitoring with ownership end to end.** Across 30+ servers and 50+ products I own the whole chain: from the first failed check to notification, fix, stakeholder communication, reporting and postmortem.
- **Platforms that outlive their first design.** I took a legacy on-prem platform to cloud-native Kubernetes on Azure, and moved the operational model (monitoring, backup, deployment) with it.
- **Better CI/CD in the teams around me.** I advise development leads on pipeline design and release practices.

## Config as code: Git is the single source of truth

I believe in one rule: the truth about a system lives in Git. If it isn't in the repo, it doesn't exist, and if the running system disagrees with the repo, the system is wrong.

- **Edit in Git, never on the host.** Config files are changed in the repo and rolled out by a workflow. Environments are derived from the repo and can be rebuilt on demand.
- **Generated from secrets and variables, never plain text in Git.** PII has no place in a repository, so it lives in secrets and variables and is injected when the config is generated. Take alerting contacts: people and groups, including email addresses and phone numbers, are generated from one structured source. A person is defined once, and every group membership and notification path resolves to that name.
- **Every change is a reviewed commit.** No late-night edits on a server: every change is a diff, reviewed before it ships and reverted when it's wrong.

## How I learn: build it, then defend it

Books don't work for me, and theory without a purpose bores me fast. I learn by doing: a real project, dirty hands, trying things out.

I learn and apply best practices, but I don't stop at repeating them. I want to understand a topic well enough to form an opinion and defend it: why this approach, what it costs, where it bites. Against any convenient alternative to config as code, "it's traceable" gets me nowhere, because the alternative can be taught to log that too. I want the arguments that survive that answer. If the other approach turns out better, I learn something. If mine is better, I have to be able to say exactly why.

My homelab is where that happens. I build infrastructure, try things out and tear it down again; before the current generation came many other stacks, from plain Linux to hypervisors, storage platforms and private clouds. The repos are public: [`kairos-configs`](https://github.com/fam-melcher/kairos-configs) and [`kairos-gitops`](https://github.com/fam-melcher/kairos-gitops). It's also why I'd rather walk people through a live repo than a slide deck: what we built, why, and a straight answer to "wouldn't it be simpler to...?"

## Stack

| | |
|---|---|
| **Platform** | ![Platform](https://go-skill-icons.vercel.app/api/icons?i=linux,docker,kubernetes,azure,helm) |
| **Delivery** | ![Delivery](https://go-skill-icons.vercel.app/api/icons?i=git,github,githubactions) |
| **Monitoring** | <img src="https://www.nagios.com/wp-content/uploads/2025/08/NCircleLogo_150_CoreBlackNCoreWhiteCircle.svg" height="48" alt="Nagios"> |
| **Web & docs** | ![Web and docs](https://go-skill-icons.vercel.app/api/icons?i=apache,nginx,astro) |
| **Daily drivers** | ![Daily drivers](https://go-skill-icons.vercel.app/api/icons?i=vscode,claude,githubcopilot) |
| **Programming** | ![Programming](https://go-skill-icons.vercel.app/api/icons?i=bash,python) |

## Connect

- LinkedIn: [linkedin.com/in/m-melcher](https://www.linkedin.com/in/m-melcher)
- Lab: [github.com/fam-melcher](https://github.com/fam-melcher)
