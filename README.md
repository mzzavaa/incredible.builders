# incredible.builders: Practitioner & Open Source Community

**Domain:** incredible.builders
**Role:** Community · Practitioner and open source community for people who build
**Priority:** Phase 2
**Strategy doc:** internal, not linked from here

## Purpose
The hands-on layer of the Incredible portfolio. Where the group publishes working
artifacts: open source projects, runnable labs, build logs, architecture teardowns,
and a showcase of what people actually shipped. Credibility is earned with code and
running systems, not slides. Audience is engineers, solution architects, indie
builders, and hackathon participants.

## Key Features / Sections
- Open source projects index with a page per project
- Labs and hands-on tutorials, each runnable end to end
- Build logs: honest, dated notes from real builds
- Architecture teardowns of systems worth copying
- Showcase, the wall of builds submitted by the community
- Build challenges and hackathons
- The toolchain and stack we actually use
- Contributing guide, code of conduct, maintainer list
- GitHub and Discord entry points

## Monetization
Indirect. Talent pipeline, tool adoption, and top of funnel for
incredible.training and incredible-consulting.com. No paywalls on this domain.

## Content map
```
content/
  _index.md                         Homepage
  projects/                         Open source projects index
    _index.md
    agent-scaffold.md
    mcp-server-kit.md
    cost-guardrails.md
    usergroup-toolkit.md
  labs/                             Runnable hands-on tutorials
    _index.md
    first-agent-in-an-hour.md
    build-an-mcp-server.md
    serverless-rag-pipeline.md
    terraform-guardrails-lab.md
  build-logs/                       Dated notes from real builds
    _index.md
    write-a-build-log.md
    agent-cost-tuning.md
    migrating-to-agentcore.md
  teardowns/                        Architecture teardowns
    _index.md
    multi-agent-orchestration.md
    serverless-video-pipeline.md
    retrieval-layer.md
  showcase/                         Wall of builds
    _index.md
    submit.md
    criteria.md
  challenges/                       Build challenges and hackathons
    _index.md
    hackathon-playbook.md
    rules-and-judging.md
    run-your-own.md
  stack/                            Toolchain and reference architectures
    _index.md
    toolchain.md
    reference-architectures.md
    environments-and-cost.md
  contribute/                       How to contribute
    _index.md
    contributing-guide.md
    good-first-issues.md
    maintainers.md
    code-of-conduct.md
  join/                             Entry points
    _index.md
    github.md
    discord.md
    office-hours.md
  about/                            What this is
    _index.md
    what-we-build.md
    portfolio.md
    licensing.md

data/
  projects.yaml                     Schema for the projects index
  labs.yaml                         Schema for the labs catalogue
  showcase.yaml                     Schema for showcase submissions
  challenges.yaml                   Schema for challenges and hackathons
```

## Relationship to other Incredible domains
- **incredible-company.com** is the parent. This site links up to it in the footer
  and takes brand and legal pages from it rather than restating them.
- **incredible-consulting.com** is the canonical commercial consulting domain. When a
  reader wants paid delivery, send them there. Never quote day rates here.
- **incredible-consulting.org** owns the open methodology and public-good material.
  Method write-ups and frameworks belong there; this site links out rather than
  duplicating. Code artifacts referenced by a method live here.
- **incredibleconsulting.org** is a defensive typo-catch domain. No links needed.
- **incredible.community** owns people, events, membership, and chapters. Any event
  logistics, meetup listing, or membership tier lives there. This site only links to
  it from build challenges and office hours.
- **incredible.training** owns paid curriculum, cohorts, and certification. Labs here
  are free and self-serve; when a reader wants a guided path, hand off to training.
