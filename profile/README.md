# MailSchema

**Open specifications and shared types for agents and services to work through email.**

Email already reaches people, agents and the systems around them. MailSchema defines how a message can describe available service actions, how an authorized client requests one and how the service reports the result.

[Read the specification](https://mailschema.org/specification/) · [Explore Types](https://mailschema.org/types/) · [Browse the Registry](https://mailschema.org/registry/) · [Try Content Review](https://mailschema.org/examples/) · [Install the tools](https://mailschema.org/tools/)

## Mail Action Protocol

Mail Action Protocol (MAP) carries structured action descriptions alongside ordinary readable email. It does not grant authority. Implementing services keep control of authentication, permissions, human approvals, content policy, rate limits and the underlying work.

**Current status:** MAP 0.1 and Content Review 0.1 are working drafts. Information Request and Subscription Preferences are proposals. The project is validating the execution profile and implementation evidence before an Internet-Draft submission.

## Repositories

- [`mailschema`](https://github.com/mailschema/mailschema) — specification source, shared schemas, Registry, conformance fixtures and the public site.
- [`go`](https://github.com/mailschema/go) — typed MAP documents and canonical MailSchema schemas for Go.

Type proposals, amendments and evidence-backed implementation declarations are submitted through the public repository. [Read the contribution guide](https://mailschema.org/contribute/).
