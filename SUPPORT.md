# Support
For build support, see the project's `README.md`.  For additional _system arthiceture metadata_, see the projects `sam.yaml` file.  

Other technical documentation may be found in the project's GitHub Wiki and/or [Confluence Technical Service directory](https://im-kb.internal.towerswatson.com/x/AYbyCw).

### Contents
- [Communication](#communication) & [OKRs](#objectives--key-results)
- [SDLC](#software-development-life-cycle) & [Audit Evidence](#audit-evidence)
- [Bug Magagement](#bug-management)
- [Standards](#standards--guidelines) & [Architecture](#architecture)
- [Decision Records](#decision-records)

## Communication
> See [WE Communication KB](https://im-kb.internal.towerswatson.com/x/TBJGCg) for additional details

## Objectives & Key Results
The product family defines yearly product level objectives.  The teams within generate quarterly objectives that cascade up to product level key results.
> See [Objectives & Key Results KB](https://im-kb.internal.towerswatson.com/x/OK1oCQ) for a list of objectives and key results

---
# Software Development Life Cycle
Units of work are prioritized against a backlog in our [WE Jira Project](https://im-jira.internal.towerswatson.com/secure/RapidBoard.jspa?rapidView=665) by [Product Owners](https://im-kb.internal.towerswatson.com/x/5bNaCg) and owning teams.

In most cases, changes are implemented in a [Feature Branch git Workflow](https://im-kb.internal.towerswatson.com/x/T58QEg) style, generating a [Pull Request](https://im-kb.internal.towerswatson.com/x/UTWwCg) that is reviewed by a [technical attestor](https://im-kb.internal.towerswatson.com/x/2gZmEQ).

[Production changes](https://im-kb.internal.towerswatson.com/x/5AZmEQ) are merged into the repo's `master` branch, built & tested in CI and cleared in an _integrated environment_ prior to deployment. 

Every [release artifact](https://im-kb.internal.towerswatson.com/x/nQepEQ) is cleared by a [Technical, QA and Stakeholder attestation](https://im-kb.internal.towerswatson.com/x/2gZmEQ), certifing that the changes satsify our [Definition of Confidence](https://im-kb.internal.towerswatson.com/x/jcFaCg) & [proof of testing](https://im-kb.internal.towerswatson.com/x/fwcnEg).

> See [WE Software Development Life Cycle KB](https://im-kb.internal.towerswatson.com/x/p4Q9D) for more details

## Audit Evidence
Parts of our [Software Development Lifecycle](https://im-kb.internal.towerswatson.com/x/p4Q9D) process deviates from our service line's current [SDLC Process](https://im-kb.internal.towerswatson.com/x/3oMnEQ).

We are responsible in providing such evidence that satisfies our [SDLC Policy](https://im-kb.internal.towerswatson.com/x/4IMnEQ) & [Audit Controls](https://im-kb.internal.towerswatson.com/x/5oMnEQ) for those changes we deploy to production.

GitHub [Pull Request](https://im-kb.internal.towerswatson.com/x/UTWwCg), reviewed by a [technical attestor](https://im-kb.internal.towerswatson.com/x/i4hAEQ), acts as the [Technical Attestation](https://im-kb.internal.towerswatson.com/x/2gZmEQ) required by our [SDLC Policy](https://im-kb.internal.towerswatson.com/x/4IMnEQ).

> See [WE: Audit Evidence KB](https://im-kb.internal.towerswatson.com/x/kYGBD) for additional details around our the audit evidence we provide

## Bug Management
Using a form of [Zero Bugs Policy](https://im-kb.internal.towerswatson.com/x/wSyGCQ), bugs & security issues are first brought to the attention of the _Product Manage_ who, in turn, assess and evaluates if its priority and severity.

Bugs are filed in the [WE: Jira Project](https://im-kb.internal.towerswatson.com/x/EBCGCQ) referncing the [technical service](https://im-kb.internal.towerswatson.com/x/5AZmEQ) by a _JIRA Component_.

> See [WE: Bug Management](https://im-kb.internal.towerswatson.com/x/wSyGCQ) for details

---
## Standards & Guidelines
Defined product family standards, strategies, guidelines and various solutions for both functional and non-functional practices.

- [Architecture & Coding Standards](https://im-kb.internal.towerswatson.com/x/LYUWD)
- [Infrastructure Standards](https://im-kb.internal.towerswatson.com/x/IwApCw)
- [UI Standards](https://im-kb.internal.towerswatson.com/x/Uo-7Cg)
- [Analytical Standards](https://im-kb.internal.towerswatson.com/x/KyOwCg)
- [Automated Testing Standards](https://im-kb.internal.towerswatson.com/x/5RuwCg)

## Architecture
The architectural strategy follows the patterns and processes from our architecture strategy team. We approach all our stories and items we’re validating by determining what bounded context the work best fits into. From there we either begin the process of creating the new bounded context services or we start the work in the existing bounded context.

- Build steps - `README.md`
- System Architecture Metadata - `sam.yaml`
- [Taxonomy](https://im-kb.internal.towerswatson.com/x/dByUCg)
- [Site Composition](https://im-kb.internal.towerswatson.com/x/DZcYCg)
- [Infrastructure](https://im-kb.internal.towerswatson.com/x/NZ3XCg)

> See [WE: Architecture Guidelines KB](https://im-kb.internal.towerswatson.com/x/861oCQ) for additional details around our architecture and its taxonomy

### Decision Records
An [Architectural Decision Record (ADR)](https://im-kb.internal.towerswatson.com/x/Sg_GCQ) tracks an architecture design choice, patterns to use, infrastructure to provision, standards to adopt.

- **Service-line level**: recorded within the [GitHub Master Architecture Plan](http://github.extendhealth.com/extend-health/master-architecture-plan/tree/master/Implementation%20Decisions)
- **Product family level**: recorded within the [WE: Architecture Decision Records](https://im-kb.internal.towerswatson.com/x/Sg_GCQ)
- **Deployable entity level**: recorded either in the `/docs` decisions folder in it's GitHub repo or in Confluence under its [technical documentation](https://im-kb.internal.towerswatson.com/x/AYbyCw)

> A _UML Diagram_ also acts as an ADR
