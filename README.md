# SourceHut (sourcehut)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Privacy-focused software development platform with GraphQL APIs for managing Git and Mercurial repositories, mailing lists, issue trackers, CI build services, wikis, paste, and static web hosting. All services expose OAuth 2.0-authenticated GraphQL endpoints with webhook support.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/sourcehut/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sourcehut/refs/heads/main/apis.yml)

## Tags

- Git
- Mercurial
- Source Control
- Continuous Integration
- Mailing Lists
- Issue Tracking
- Developer Tools
- Open Source
- Privacy
- GraphQL

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### git.sr.ht GraphQL API

GraphQL API for managing Git repositories, branches, commits, tags, artifacts, access control lists, and repository webhooks on SourceHut.

- **Human URL:** [https://docs.sourcehut.org/git.sr.ht/](https://docs.sourcehut.org/git.sr.ht/)
- **Base URL:** `https://git.sr.ht/graphql`

#### Tags

- Git
- Repositories
- Source Control
- Webhooks
- GraphQL

#### Properties

- [Documentation](https://docs.sourcehut.org/git.sr.ht/)
- [Graph Q L](https://git.sr.ht/graphql)
- [Graph Q L](graphql/sourcehut-graphql.md)

### hg.sr.ht GraphQL API

GraphQL API for managing Mercurial repositories on SourceHut, including repository operations, webhooks, and access control.

- **Human URL:** [https://docs.sourcehut.org/hg.sr.ht/](https://docs.sourcehut.org/hg.sr.ht/)
- **Base URL:** `https://hg.sr.ht/graphql`

#### Tags

- Mercurial
- Repositories
- Source Control
- GraphQL

#### Properties

- [Documentation](https://docs.sourcehut.org/hg.sr.ht/)
- [Graph Q L](https://hg.sr.ht/graphql)

### builds.sr.ht GraphQL API

GraphQL API for submitting and managing continuous integration build jobs across Linux distributions and BSDs on SourceHut.

- **Human URL:** [https://docs.sourcehut.org/builds.sr.ht/](https://docs.sourcehut.org/builds.sr.ht/)
- **Base URL:** `https://builds.sr.ht/graphql`

#### Tags

- Continuous Integration
- Build Automation
- CI/CD
- GraphQL

#### Properties

- [Documentation](https://docs.sourcehut.org/builds.sr.ht/)
- [Graph Q L](https://builds.sr.ht/graphql)

### todo.sr.ht GraphQL API

GraphQL API for managing bug trackers and ticket systems for software projects on SourceHut.

- **Human URL:** [https://docs.sourcehut.org/todo.sr.ht/](https://docs.sourcehut.org/todo.sr.ht/)
- **Base URL:** `https://todo.sr.ht/graphql`

#### Tags

- Issue Tracking
- Bug Tracker
- Project Management
- GraphQL

#### Properties

- [Documentation](https://docs.sourcehut.org/todo.sr.ht/)
- [Graph Q L](https://todo.sr.ht/graphql)

### lists.sr.ht GraphQL API

GraphQL API for managing mailing lists and email-based code review workflows on SourceHut, powered by git send-email conventions.

- **Human URL:** [https://docs.sourcehut.org/lists.sr.ht/](https://docs.sourcehut.org/lists.sr.ht/)
- **Base URL:** `https://lists.sr.ht/graphql`

#### Tags

- Mailing Lists
- Email
- Code Review
- GraphQL

#### Properties

- [Documentation](https://docs.sourcehut.org/lists.sr.ht/)
- [Graph Q L](https://lists.sr.ht/graphql)

### meta.sr.ht GraphQL API

GraphQL API for account management, OAuth 2.0 token and client administration, SSH keys, PGP keys, and user profile operations on SourceHut.

- **Human URL:** [https://man.sr.ht/meta.sr.ht/](https://man.sr.ht/meta.sr.ht/)
- **Base URL:** `https://meta.sr.ht/graphql`

#### Tags

- Account Management
- OAuth
- Authentication
- GraphQL

#### Properties

- [Documentation](https://man.sr.ht/meta.sr.ht/)
- [Graph Q L](https://meta.sr.ht/graphql)

### paste.sr.ht GraphQL API

GraphQL API for creating and managing text pastes on SourceHut.

- **Human URL:** [https://docs.sourcehut.org/paste.sr.ht/](https://docs.sourcehut.org/paste.sr.ht/)
- **Base URL:** `https://paste.sr.ht/graphql`

#### Tags

- Paste
- Text Sharing
- GraphQL

#### Properties

- [Documentation](https://docs.sourcehut.org/paste.sr.ht/)
- [Graph Q L](https://paste.sr.ht/graphql)

### man.sr.ht GraphQL API

GraphQL API for creating and managing wiki and manual pages hosted on SourceHut using git-backed Markdown content.

- **Human URL:** [https://docs.sourcehut.org/man.sr.ht/](https://docs.sourcehut.org/man.sr.ht/)
- **Base URL:** `https://man.sr.ht/graphql`

#### Tags

- Wiki
- Documentation
- Markdown
- GraphQL

#### Properties

- [Documentation](https://docs.sourcehut.org/man.sr.ht/)
- [Graph Q L](https://man.sr.ht/graphql)

### pages.sr.ht GraphQL API

GraphQL API for managing static web hosting on SourceHut, deploying sites to srht.site domains.

- **Human URL:** [https://docs.sourcehut.org/pages.sr.ht/](https://docs.sourcehut.org/pages.sr.ht/)
- **Base URL:** `https://pages.sr.ht/graphql`

#### Tags

- Static Hosting
- Web Pages
- GraphQL

#### Properties

- [Documentation](https://docs.sourcehut.org/pages.sr.ht/)
- [Graph Q L](https://pages.sr.ht/graphql)

## Common Properties

- [Website](https://sourcehut.org)
- [Documentation](https://man.sr.ht)
- [Blog](https://sourcehut.org/blog/)
- [Pricing](https://sourcehut.org/pricing/)
- [Status Page](https://status.sr.ht)
- [Git Hub Org](https://git.sr.ht/~sircmpwn)
- [Plans](https://raw.githubusercontent.com/api-evangelist/sourcehut/refs/heads/main/plans/sourcehut-plans-pricing.yml)
- [Rate Limits](https://raw.githubusercontent.com/api-evangelist/sourcehut/refs/heads/main/rate-limits/sourcehut-rate-limits.yml)
- [Fin Ops](https://raw.githubusercontent.com/api-evangelist/sourcehut/refs/heads/main/finops/sourcehut-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
