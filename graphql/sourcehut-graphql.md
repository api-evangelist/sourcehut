# Sourcehut GraphQL API

Sourcehut (sr.ht) exposes GraphQL APIs for each of its services, including Git repository hosting, Mercurial hosting, continuous integration builds, issue tracking, mailing lists, account management, paste, wikis, and static web hosting. Each service provides its own authenticated GraphQL endpoint under its subdomain. Authentication uses OAuth 2.0 access tokens or personal access tokens. The git.sr.ht GraphQL API covers repository management, git objects and references, access control lists, deploy keys, artifacts, code search, and webhook subscriptions.

**Endpoint:** https://git.sr.ht/api/graphql

**Documentation:** https://man.sr.ht/git.sr.ht/graphql.md

**References:**
- Documentation: https://man.sr.ht/git.sr.ht/graphql.md
- GettingStarted: https://man.sr.ht/graphql.md
- Schema Source: https://git.sr.ht/~sircmpwn/git.sr.ht/blob/master/api/graph/schema.graphqls
- Authentication: https://man.sr.ht/oauth.md
