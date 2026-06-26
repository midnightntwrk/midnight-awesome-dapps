# Contributing to Awesome Midnight

Thank you for helping grow the Midnight ecosystem list. You can submit DApps, libraries, developer tools, templates, and educational projects.

Before you open a pull request, read this guide and follow the [Midnight documentation style guide](Midnight-documentation-style-guide.md) for your README entry, pull request text, and any other markdown you change in this repository.

> The repository name still uses "dApps" for historical reasons. This list covers more than DApps alone.

## Ecosystem attribution (complete before you open a PR)

Midnight is building a public record of ecosystem activity for industry reports and tools such as [Electric Capital](https://www.developerreport.com/). Repositories without the right metadata may not be counted, even when the work is active and high quality.

Complete these three steps on your **project repository** before you open a pull request to this list. Details are in [Get your project on the map](https://docs.midnight.network/blog/get-your-project-on-the-map).

1. **Add GitHub topics:** Required: `midnightntwrk`. Optional: `compact` if your project uses Compact.
2. **Add a README attribution sentence:** One exact sentence near the top of your project README (wording depends on project type).
3. **Open a pull request here:** Add your project to this awesome list (Step 3 in the blog; you are reading the guide for it now).

Pull requests are **not accepted** if Step 1 or Step 2 is missing on the submitted project repository.

The blog post also links to optional Zealy quests for each step. Completing Zealy quests is not required to merge a pull request here.

## Table of contents

- [Ecosystem attribution (complete before you open a PR)](#ecosystem-attribution-complete-before-you-open-a-pr)
- [Quick checklist](#quick-checklist)
- [Documentation style guide](#documentation-style-guide)
- [How to submit a pull request](#how-to-submit-a-pull-request)
- [Continuous integration (CI)](#continuous-integration-ci)
- [What to submit](#what-to-submit)
- [Where to add your project](#where-to-add-your-project)
- [Formatting your entry](#formatting-your-entry)
- [Review process](#review-process)
- [If your submission is not ready yet](#if-your-submission-is-not-ready-yet)
- [Updating or removing an entry](#updating-or-removing-an-entry)
- [Reporting issues](#reporting-issues)
- [License](#license)
- [Support and communication](#support-and-communication)

## Quick checklist

Before you open a pull request:

- [ ] Your project is not already listed in [README.md](README.md). If it is, open an issue to request an update instead of a duplicate entry.
- [ ] Your repository is public and open source.
- [ ] Your entry is in the correct section and in **alphabetical order** within that section.
- [ ] Your entry follows the format: `[Project Name](link) - One sentence description.`
- [ ] Your description is factual, concise, and non-promotional.
- [ ] Your pull request text and any markdown you change follow the [Midnight documentation style guide](Midnight-documentation-style-guide.md).
- [ ] Your project meets the [submission criteria](#what-to-submit) for its type (DApp, tool, library, template, or learning resource).
- [ ] **Step 1:** Your project repository has the required `midnightntwrk` GitHub topic ([instructions](#add-the-github-topic-required)).
- [ ] **Step 2:** Your project README includes the correct attribution sentence near the top, using [exact wording](#readme-attribution-sentence-required).
- [ ] **Step 3:** You are ready to open a pull request to this list (after Steps 1 and 2 are complete).
- [ ] You have filled out the [pull request template](.github/PULL_REQUEST_TEMPLATE/pull_request_template.md).

## Documentation style guide

Every submission must comply with the [Midnight documentation style guide](Midnight-documentation-style-guide.md) in this repository.

That guide covers:

- Tone and voice (direct, technical, non-promotional)
- Brand and terminology (for example, **DApp**, **Midnight Network**, **zero-knowledge proof** or **ZK**)
- Formatting and structure
- Inclusive language

Apply it to:

- Your one-line README entry description
- Your pull request title and description
- Any other markdown files you change in this repository

Reviewers treat style guide issues as **required changes** when they affect clarity, accuracy, or brand consistency.

## How to submit a pull request

You need a [GitHub account](https://github.com/join). If you are new to GitHub, see [First Contributions](https://github.com/firstcontributions/first-contributions) for a guided walkthrough.

### Option A: You have write access to this repository

If you are a collaborator or a member of the GitHub organization with push access to `midnightntwrk/midnight-awesome-dapps`:

1. Clone the repository and create a branch from `main`:
   ```bash
   git clone https://github.com/midnightntwrk/midnight-awesome-dapps.git
   cd midnight-awesome-dapps
   git checkout -b add-your-project-name
   ```
2. Edit [README.md](README.md): add your entry in the correct section, in alphabetical order.
3. Commit and push to the upstream repository:
   ```bash
   git add README.md
   git commit -m "Add [Project Name] to [section name]"
   git push origin add-your-project-name
   ```
4. Open a pull request on GitHub targeting `main`, or use the GitHub CLI:
   ```bash
   gh pr create --repo midnightntwrk/midnight-awesome-dapps --head add-your-project-name --base main --title "Add [Project Name] to [section name]" --body "Adds [Project Name] to the [section name] section."
   ```

### Option B: You are contributing from a fork (most external contributors)

1. **Fork** [midnightntwrk/midnight-awesome-dapps](https://github.com/midnightntwrk/midnight-awesome-dapps) on GitHub.
2. **Clone your fork** locally:
   ```bash
   git clone https://github.com/YOUR_USERNAME/midnight-awesome-dapps.git
   cd midnight-awesome-dapps
   ```
3. **Add upstream** as a remote (recommended, so you can stay in sync):
   ```bash
   git remote add upstream https://github.com/midnightntwrk/midnight-awesome-dapps.git
   git fetch upstream
   git checkout main
   git merge upstream/main
   ```
4. **Create a branch** for your change:
   ```bash
   git checkout -b add-your-project-name
   ```
5. **Edit** [README.md](README.md): add your entry in the correct section, in alphabetical order.
6. **Commit and push** to your fork:
   ```bash
   git add README.md
   git commit -m "Add [Project Name] to [section name]"
   git push origin add-your-project-name
   ```
7. **Open a pull request** on GitHub from your fork into `midnightntwrk/midnight-awesome-dapps` `main`.

### Option C: Edit directly on GitHub (small changes only)

For a single README line change, you can use GitHub's web editor:

1. Open [README.md](https://github.com/midnightntwrk/midnight-awesome-dapps/blob/main/README.md) on GitHub.
2. Click the pencil (Edit) icon.
3. Add your entry, then choose **Propose changes** and open a pull request.

This works well for simple additions. For larger changes, use a local clone (Option A or B).

## Continuous integration (CI)

When you open a pull request, automated checks run on GitHub Actions.

Whether a check blocks merging depends on branch protection settings for this repository.

| Check | What it does | Typically blocks merge? |
|-------|----------------|-------------------------|
| **scan** | Security scan of the repository | Yes, if it fails |
| **license/cla** | Contributor License Agreement | Yes, if not signed |
| **add-to-project** | Adds the PR to the DevRel tracking board | No (see below) |

Reviewers also check that your submission follows the [Midnight documentation style guide](Midnight-documentation-style-guide.md). Style guide issues are handled in review even when no automated Vale check runs on this repository.

### About the `add-to-project` check

The `add-to-project` workflow uses an organization secret (`DEVREL_TRACKER_TOKEN`) that **GitHub does not expose to pull requests from forks**. On fork-based pull requests, this check fails with an error like:

```
Input required and not supplied: github-token
```

**This failure is expected for fork-based PRs and does not mean your submission is rejected.** Reviewers can still review and merge your PR. The failure is a workflow limitation, not a problem with your change.

If you have write access to the upstream repository (Option A above), push your branch directly to `midnightntwrk/midnight-awesome-dapps` to avoid this failure.

## What to submit

All pull requests are reviewed before merging. Your submission must meet the criteria below.

### 1. The project works

Whatever you submit (DApp, library, developer tool, template, or learning resource) should do what your README says it does.

- **DApps and Compact-based projects:** The repository must contain **functional Compact code**. Scaffolding, stub files, or AI-generated placeholder code that does not run will not be accepted.
- **Tools, libraries, SDKs, and templates:** The repository must include a **working implementation**, not a plan or a README-only repository.
- **Learning resources:** Tutorials and educational content should be complete and usable, not placeholders.

Reviewers may run or inspect the code as part of review.

### 2. Credit upstream work

Your repository must credit any projects, libraries, or templates it builds on. Pull requests where that credit has been removed or is unclear will be returned for revision before merging.

This is separate from the [README attribution sentence](#6-required-readme-attribution-sentence) required for ecosystem tracking.

### 3. Real use case

The project should represent a genuine application, tool, or experiment built for Midnight Network. Test repositories, forks without meaningful changes, and near-duplicate submissions will not be accepted.

### 4. Open source

All submissions must be publicly accessible repositories with a clear open source license.

### 5. Required GitHub topic

Your project repository must include the `midnightntwrk` GitHub topic before you open a pull request. **Pull requests are not accepted if the topic is missing.**

This is required for ecosystem attribution and tracking. See [Get your project on the map](https://docs.midnight.network/blog/get-your-project-on-the-map) for setup steps and related README attribution guidance.

Do not use `midnight`, `midnight-network`, `midnight-compact`, or `midnight-ecosystem`. Those variants are not tracked. Add `compact` only if your project uses the Compact language.

### 6. Required README attribution sentence

Your project repository README must include **one attribution sentence near the top**, using **exact wording** from the table below. **Pull requests are not accepted if the sentence is missing or paraphrased.**

Ecosystem tracking tools scan README files for these phrases. Custom wording may prevent your repository from being associated with Midnight Network.

| Your project type | Attribution sentence (use exactly) |
|-------------------|-------------------------------------|
| DApps, contracts, or tooling that run directly on Midnight | This project is built on the Midnight Network. |
| SDKs, infrastructure, wallets, or services | This project integrates with the Midnight Network. |
| Developer tooling, frameworks, or libraries | This project extends the Midnight Network with additional developer tooling. |

**How to choose a row:**

- Most DApp sections (Finance & DeFi, Gaming, Identity & Privacy, Governance, Healthcare, Smart Contract Primitives): use the **built on** sentence.
- SDKs, wallets, indexers, explorers, infrastructure: use the **integrates with** sentence.
- CLIs, scaffolds, libraries, and developer tools in **Developer Tools** or **Starter Templates**: use the **extends** sentence when that best describes the project. If the project is primarily a DApp or contract repo, use **built on** instead.

See [Get your project on the map](https://docs.midnight.network/blog/get-your-project-on-the-map) for context.

### 7. Documentation style guide compliance

Your submission must follow the [Midnight documentation style guide](Midnight-documentation-style-guide.md). This applies to README entry descriptions, pull request text, and any other markdown you change.

Common issues reviewers flag:

- Promotional language ("best", "revolutionary", "seamless")
- Incorrect terminology (`dapp` instead of **DApp**, `zk proof` instead of **ZK** or **zero-knowledge proof**)
- Passive voice or third-person phrasing where second person ("you") is clearer

### 8. One project per pull request (recommended)

Submit **one new entry per pull request** when possible. This makes review faster and easier to track. If you are adding several related projects from the same maintainer, mention that in the PR description.

## Where to add your project

Add your entry under the section that best matches your project. If you are unsure, pick the closest fit. Reviewers can suggest a better section during review.

| Section | What belongs here |
|---------|-------------------|
| **Example DApps (Start Here)** | Official Midnight team projects for education and onboarding only. Community submissions do not go here. |
| **Smart Contract Primitives** | Reusable contract building blocks (tokens, standards, shared libraries). |
| **Starter Templates** | Boilerplates, scaffolds, and project templates for new Midnight builds. |
| **Developer Tools** | CLIs, SDKs, compilers, indexers, explorers, wallets, MCP servers, and other tools that help developers build, test, deploy, or index. |
| **Finance & DeFi** | Payments, escrow, DEX, staking, tokenization, and other financial applications. |
| **Identity & Privacy** | Credentials, KYC, selective disclosure, and privacy-preserving identity systems. |
| **Gaming** | Games and interactive experiences on Midnight. |
| **Governance** | Voting, crowdfunding, and community governance. |
| **Healthcare** | Health-related applications using Midnight. |
| **Dormant Projects** | Do not add new projects here. See [Updating or removing an entry](#updating-or-removing-an-entry). |
| **Learning Resources** | Tutorials, courses, documentation, and community-created educational content. |
| **Community** | Official community channels, forums, ambassador programs, and fellowship links. Ask maintainers before adding or changing official links. |

Official ecosystem partners may use the 🔹 marker. Hackathon winners may use 🏆 where applicable. Do not add these markers unless your project qualifies.

## Formatting your entry

Follow the [Midnight documentation style guide](Midnight-documentation-style-guide.md) for wording, terminology, and tone.

- Add your project in **alphabetical order** within the appropriate section (by project name, not URL).
- Use this format:
  ```markdown
  - [Project Name](https://github.com/org/repo) - Brief description of what it does.
  ```
- Keep descriptions factual, one sentence, and non-promotional. End with a period.
- Link to the **primary repository** or canonical project URL.
- Avoid marketing language ("best", "revolutionary", "seamless", and similar superlatives).

### Description examples

**Avoid (promotional):**

```markdown
- [MyProject](https://github.com/org/repo) - The ultimate, revolutionary privacy solution for Midnight.
```

**Prefer (factual):**

```markdown
- [MyProject](https://github.com/org/repo) - CLI for deploying Compact smart contracts to Midnight Testnet.
```

Optional: add secondary links on the same line after the description, for example npm or a live demo:

```markdown
- [Project Name](https://github.com/org/repo) - Short description. - [npm](https://www.npmjs.com/package/example)
```

### Good example

```markdown
- [Midnight Escrow](https://github.com/example/midnight-escrow) - Privacy-preserving escrow contract with conditional payments using zero-knowledge proofs on Midnight.
```

### Common mistakes

| Mistake | Fix |
|---------|-----|
| Entry not in alphabetical order | Sort by project name within the section |
| Promotional description | State what the project does in plain language |
| Style guide violations | See [Midnight documentation style guide](Midnight-documentation-style-guide.md) |
| Link goes to a fork or mirror | Use the canonical repository URL |
| Duplicate entry | Search README first; update the existing line instead |
| Wrong section | See [Where to add your project](#where-to-add-your-project) |
| Missing `midnightntwrk` topic | Add the topic on your repo, then open or update your PR |
| Missing or paraphrased README attribution | Add the exact sentence from the [attribution table](#readme-attribution-sentence-required) near the top of your project README |

### Add the GitHub topic (required)

Every listed project must have the `midnightntwrk` topic on its repository. Reviewers will not merge pull requests for projects that have not added it.

1. Open your repository on GitHub.
2. In the right-hand sidebar, find the **About** section.
3. Click the gear icon next to **About**.
4. In **Topics**, add `midnightntwrk` (and `compact` if your project uses Compact).
5. Save changes.

Full context and attribution steps: [Get your project on the map](https://docs.midnight.network/blog/get-your-project-on-the-map).

**Do not use:** `midnight`, `midnight-network`, `midnight-compact`, or `midnight-ecosystem`. Those topics are not tracked for the Midnight ecosystem.

### README attribution sentence (required)

Add **one** of the sentences below near the top of your **project** README (not this awesome list README). Copy the sentence **exactly**. Do not rephrase it.

| Your project type | Attribution sentence (use exactly) |
|-------------------|-------------------------------------|
| DApps, contracts, or tooling that run directly on Midnight | This project is built on the Midnight Network. |
| SDKs, infrastructure, wallets, or services | This project integrates with the Midnight Network. |
| Developer tooling, frameworks, or libraries | This project extends the Midnight Network with additional developer tooling. |

Reviewers will not merge pull requests if the submitted repository README lacks the correct sentence for its project type.

## Review process

When you open a pull request, a reviewer from the developer relations team evaluates it against the criteria above. If a submission needs more time or broader team input, the reviewer tells you in the PR thread so you are not left wondering.

Review comments fall into two categories. The reviewer labels which category applies:

- **Required changes.** Items that must be addressed before merging, usually because they affect correctness, safety, style guide compliance, missing `midnightntwrk` topic, missing or incorrect README attribution sentence, or whether the submission meets the criteria above.
- **Suggestions.** Observations the reviewer thinks are useful for your project, offered as input rather than as merge conditions. You can take them or leave them.

Pull requests will not be merged with unresolved required changes. Suggestions will not block merging.

### What reviewers check

- Submission meets the [criteria](#what-to-submit) for its type
- Project repository has the `midnightntwrk` GitHub topic
- Project repository README includes the correct attribution sentence (verified via the link in the PR)
- Entry follows the [Midnight documentation style guide](Midnight-documentation-style-guide.md)
- Correct section and alphabetical order
- Canonical link and accurate one-line description
- CLA signed and required CI checks passing (where branch protection applies)

### Updating your pull request

If a reviewer asks for changes:

1. Push additional commits to the same branch on your fork (or upstream branch).
2. Reply in the PR thread when you have addressed the feedback.
3. Re-request review if the option is available on GitHub.

You do not need to open a new pull request for updates to the same submission.

## If your submission is not ready yet

If your project is early, still being built, or not yet in a state the list can include, the reviewer tells you specifically what to address before it is ready. You are welcome to return when those criteria are met.

A "not yet" is not a "no."

## Updating or removing an entry

- **Update a link or description:** Open a pull request that edits the existing line in [README.md](README.md). Mention what changed and why.
- **Move to dormant:** If a project is no longer maintained, open a pull request that moves it to [dormant_projects/README.md](dormant_projects/README.md) following the pattern used by existing dormant entries. Explain why (inactive repo, archived, builder confirmed sunset, and similar).
- **Remove:** Open a pull request that deletes the line and briefly states why (project removed, duplicate, no longer open source, and similar). Tag the original author with `@github-username` when possible so they are aware.

## Reporting issues

Open an [issue](https://github.com/midnightntwrk/midnight-awesome-dapps/issues) if you want to:

- Suggest a new category or structural change to the list
- Report a broken link or outdated entry
- Ask whether your project fits before you invest time in a pull request
- Discuss anything that could make this list more useful

Please do not open issues solely to request that your project be added. Use a pull request instead.

## License

This repository is maintained by Midnight Foundation and licensed under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0). By submitting a pull request, you agree that your contribution may be included under the same license.

## Support and communication

If you need help with Midnight, connect with the community on:

- [Discord](https://discord.com/invite/midnightnetwork)
- [Telegram](https://t.me/Midnight_Network_Official)
- [X](https://x.com/MidnightNtwrk)
- [Midnight Forum](https://forum.midnight.network) (technical Q&A)
- [Midnight Docs](https://docs.midnight.network/)

Thank you for contributing.
