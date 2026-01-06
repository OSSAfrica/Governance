# OSSAfrica GitHub Issue Label Taxonomy

Version: 1.0  
Status: Active  
Last Updated: 2026-01-06   
Scope: Organization-wide

## Purpose

This document defines the **authorit ative GitHub issue label taxonomy** for OSSAfrica.
All repositories under the OSSAfrica GitHub organization SHOULD align with this taxonomy unless explicitly exempted.

The taxonomy is designed to:

* Enable consistent triage and prioritization
* Support automation and GitHub Projects
* Improve contributor clarity and onboarding
* Scale across multiple repositories and initiatives

### Label Categories Overview

Labels are grouped into the following categories:

1. Type
2. Status
3. Priority
4. Area / Domain
5. Community & Governance
6. Security
7. Effort & Difficulty
8. Meta / Process

### 2.1 Type Labels

| Label                | Color     | Description                                           |
| -- |  | -- |
| `type:bug`           | `#d73a4a` | A defect or unintended behavior                       |
| `type:feature`       | `#0e8a16` | New functionality or capability                       |
| `type:enhancement`   | `#a2eeef` | Improvement to existing functionality                 |
| `type:documentation` | `#0075ca` | Documentation-related work                            |
| `type:refactor`      | `#cfd3d7` | Code or structure improvement without behavior change |
| `type:question`      | `#d876e3` | Clarification or inquiry                              |

### 2.2 Status Labels

| Label                | Color     | Description                       |
| -- |  |  |
| `status:triage`      | `#fbca04` | Awaiting initial review           |
| `status:accepted`    | `#0e8a16` | Approved and ready for work       |
| `status:in-progress` | `#0052cc` | Actively being worked on          |
| `status:blocked`     | `#b60205` | Blocked by dependency or decision |
| `status:needs-info`  | `#e99695` | More information required         |
| `status:completed`   | `#5319e7` | Work completed                    |

### 2.3 Priority Labels

| Label               | Color     | Description                  |
| - |  | - |
| `priority:critical` | `#b60205` | Immediate attention required |
| `priority:high`     | `#d93f0b` | High importance              |
| `priority:medium`   | `#fbca04` | Standard priority            |
| `priority:low`      | `#c2e0c6` | Nice-to-have                 |

### 2.4 Area / Domain Labels

| Label                 | Color     | Description                      |
|  |  | -- |
| `area:governance`     | `#1d76db` | Governance, policy, structure    |
| `area:community`      | `#0e8a16` | Community engagement and growth  |
| `area:education`      | `#a2eeef` | Training, learning, curriculum   |
| `area:security`       | `#b60205` | Security-related topics          |
| `area:infrastructure` | `#5319e7` | CI, tooling, platforms           |
| `area:events`         | `#f9d0c4` | Calls, conferences, meetups      |
| `area:communications` | `#bfd4f2` | Messaging, website, social media |

### 2.5 Community & Governance Labels

| Label                        | Color     | Description                   |
| - |  | -- |
| `community:good-first-issue` | `#7057ff` | Suitable for new contributors |
| `community:help-wanted`      | `#008672` | Actively seeking contributors |
| `governance:decision-needed` | `#d876e3` | Requires formal decision      |
| `governance:proposal`        | `#1d76db` | Policy or structural proposal |

### 2.6 Security Labels

| Label              | Color     | Description                    |
|  |  |  |
| `security:report`  | `#b60205` | Security-related issue         |
| `security:policy`  | `#e99695` | Security policy or process     |
| `security:private` | `#000000` | Sensitive; restricted handling |

### 2.7 Effort & Difficulty Labels

| Label           | Color     | Description        |
|  |  |  |
| `effort:small`  | `#c2e0c6` | Low effort         |
| `effort:medium` | `#fbca04` | Moderate effort    |
| `effort:large`  | `#d93f0b` | Significant effort |

### 2.8 Meta / Process Labels

| Label             | Color     | Description                |
| -- |  | -- |
| `meta:tracking`   | `#ededed` | Tracking or umbrella issue |
| `meta:automation` | `#bfd4f2` | Automation-related         |
| `meta:discussion` | `#d876e3` | Discussion-focused issue   |

## 3. Change Management Process

### Authority

This taxonomy is governed by the **OSSAfrica Core Team**, operating under oversight from the OpenSSF BEAR Working Group.

### Change Proposal Process

1. **Proposal Submission**

   * Any community member may propose changes via a GitHub issue labeled:

     * `governance:proposal`
     * `area:governance`

2. **Review**

   * Core Team reviews for:

     * Clarity
     * Duplication
     * Automation impact
     * Organization-wide implications

3. **Decision**

   * Minor changes: Core Team consensus
   * Major changes (new categories, removals): documented decision and review period

4. **Approval & Merge**

   * Approved changes are merged via PR
   * Version history preserved in Git

### Versioning

* The taxonomy document SHOULD include a version header.
* Changes SHOULD be summarized in a changelog section at the bottom of the file.

### Enforcement

* New repositories SHOULD adopt this taxonomy by default.
* Exceptions MUST be documented in the repository README or GOVERNANCE file.
* Automation MAY be used to sync labels across repositories.

## Changelog

### v1.0 — 2026-01-06
- Initial release of the organization-wide GitHub issue label taxonomy
- Defined standard label categories, naming conventions, and color coding
- Established governance and change management process for label updates
  
