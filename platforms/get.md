<div align="center">
  <img src="media/get-logo-circular.png" width="250" alt="GET circular cyberpunk logo"/>
</div>

# GET - Gall & Etos Technology

[Back to all platforms](../profile/README.md)

**This guide describes GET's hiring process and technology stack. It does not
apply to other platforms in this organization.**

GET builds the software behind [Etos](https://www.etos.nl) and
[Gall & Gall](https://www.gall.nl), part of Ahold Delhaize.

If you are reading this, you have been invited to do a technical case with us.
Thank you for your time and interest; we're looking forward to building something
together.

This page explains how the interview works, what to do before it and what happens
on the day. The case itself appears in your private repository on the day of the
interview.

## Who we are

Etos and Gall & Gall have hundreds of stores across the Netherlands, plus webshops
and apps. GET is the tech organisation behind them: product teams that build and
run the services for products, prices, promotions, stores, suppliers and the tools
our colleagues use every day.

We combine the stability of a large enterprise with the pace of two smaller
retailers. Teams own their services end to end, from idea to production.

| Area | What we use |
| --- | --- |
| Backend | Python, FastAPI, Strawberry GraphQL, SQLAlchemy, `uv` |
| Frontend | React, Vite, Next.js, Tailwind, shadcn/ui |
| Data & events | PostgreSQL, Redis, Kafka |
| Platform | Docker, Kubernetes, Azure, GitHub Actions, Grafana |

You don't need to know all of these. We care much more about how you work than
about which tools you have used.

## How the interview works

The interview is a single day of about 2.5 hours, in three parts with a short break
between each:

| Part | Duration | What happens |
| --- | --- | --- |
| 1 | 45 min | **Getting to know each other.** A conversation about you, how you work and how we work. |
| | 5 min | **Break.** Grab a coffee while we push the case to your repository. |
| 2 | ~1h05 | **Working case.** You build on a small, realistic application from our retail domain, on your own. |
| | 5 min | **Break.** Commit and push your work, then stretch your legs while we have a first look. |
| 3 | 30 min | **Joint review.** We look at what you built together and talk about your choices. |

### Before the interview

1. **Read this page.** It tells you who we are, what we build with and how the day
   works. There is nothing else to study: the case itself only appears on the day.
2. **Accept your invitation.** We create a private repository in this organisation
   just for you and invite you to it. Accept the invitation from your email or from
   [github.com/notifications](https://github.com/notifications), then clone the
   repository. It only holds a placeholder README for now; that's expected.
3. **Get your machine ready.** On the machine you will use for the interview, make
   sure you have:

   - [ ] Git, and access to your repository on GitHub
   - [ ] [Docker](https://docs.docker.com/get-docker/) with Compose **v2.22 or newer**
     (`docker compose version`), running and able to start containers
     (`docker run --rm hello-world`)
   - [ ] Ports `3000`, `5432`, `8000` and `8080` free
   - [ ] Your favourite editor or IDE, set up the way you like it
   - [ ] An AI coding agent (harness), installed, logged in and tried out on a
     small task

   We build with AI every day, and we expect you to use an AI coding agent during
   the case: a tool that can read your repository, run commands and make changes
   for you. If you don't have a favourite yet, pick one of these:

   - [Claude Code](https://claude.com/product/claude-code)
   - [Codex](https://github.com/openai/codex)
   - [GitHub Copilot app](https://docs.github.com/en/copilot/concepts/copilot-surfaces/github-copilot-app)

If anything on this list doesn't work, let us know before the interview so we can
sort it out together.

### On the day

1. **Getting to know each other (45 min).** We start with a conversation, no laptop
   needed.
2. **Break (5 min).** Grab a coffee. Meanwhile, we push a commit with the case to
   your repository.
3. **Working case (~1h05).** Pull the case, read the README and start the stack as
   described there. The first start builds a few containers, so give it a couple of
   minutes. We tell you which phases of the case to focus on, and then it's over
   to you.
   Work the way you normally would, with your own editor and your AI coding agent.
   Nobody watches over your shoulder, but you are not on your own: an engineer is
   available throughout, so message them whenever you have a question or get
   stuck. Asking questions is part of the job.
   **We don't expect you to finish everything.** Doing a few phases well is better
   than rushing through all of them.
4. **Break (5 min).** Commit and push your work, so we can have a first look at it
   before the review.
5. **Joint review (30 min).** We look at what you built together and talk through
   your choices. This is a conversation, not a defence. Make sure you understand
   what your agent produced: we will ask you about it.

## Good to know

- Your case repository is private. Ask your hiring contact if you have questions
  about who has access.
- Please don't share the case or publish your solution.
- We remove your access to the repository after the interview.

## Questions and contact

Contact the GET recruiter or engineer who arranged your interview if you have any
questions or need help preparing.

---

Good luck, and above all: have fun building!
