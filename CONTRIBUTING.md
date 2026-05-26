# Contributing to Awesome Midnight

This list helps developers find what is being built on Midnight Network and gives builders visibility for their work. We welcome submissions from anyone building for the ecosystem: DApps, libraries, developer tools, templates, and educational projects are all in scope.

> **Note:** The repository name still uses "dApps" for historical reasons. In practice, we list a broader range of Midnight ecosystem projects than DApps alone.

## Table of contents

- [Quick checklist](#quick-checklist)
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

Before you open a pull request, confirm the following:

- [ ] Your project is not already listed in [README.md](README.md). If it is, open an issue to request an update instead of a duplicate entry.
- [ ] Your repository is public and open source.
- [ ] Your entry is in the correct section and in **alphabetical order** within that section.
- [ ] Your entry follows the format: `[Project Name](link) - One sentence description.`
- [ ] Your description is factual, concise, and non-promotional.
- [ ] Your project meets the [submission criteria](#what-to-submit) for its type (DApp, tool, library, template, or learning resource).
- [ ] You have added the `midnightntwrk` [GitHub topic](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/classifying-your-repository-with-topics) to your repository.
- [ ] You have filled out the [pull request template](.github/PULL_REQUEST_TEMPLATE/pull_request_template.md).

## How to submit a pull request

You need a [GitHub account](https://github.com/join). If you are new to GitHub, see [First Contributions](https://github.com/firstcontributions/first-contributions) for a guided walkthrough.

### Option A: You have write access to this repository

If you are a collaborator or org member with push access to `midnightntwrk/midnight-awesome-dapps`:

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
   gh pr create --repo midnightntwrk/midnight-awesome-dapps \
     --head add-your-project-name \
     --base main \
     --title "Add [Project Name] to [section name]" \
     --body "Adds [Project Name] to the [section name] section."
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

| Check | What it does | Blocks merge? |
|-------|----------------|---------------|
| **scan** | Security scan of the repository | Yes, if it fails |
| **license/cla** | Contributor License Agreement | Yes, if not signed |
| **add-to-project** | Adds the PR to the DevRel tracking board | No (see below) |

### About the `add-to-project` check

The `add-to-project` workflow uses an organization secret (`DEVREL_TRACKER_TOKEN`) that **GitHub does not expose to pull requests from forks**. If you open a PR from a fork, this check may fail with an error like:

```
Input required and not supplied: github-token
```

**This is expected for fork-based PRs and does not mean your submission is rejected.** Reviewers can still review and merge your PR. The failure is a workflow limitation, not a problem with your change.

If you have write access to the upstream repository (Option A above), pushing your branch directly to `midnightntwrk/midnight-awesome-dapps` avoids this failure.

## What to submit

All pull requests are reviewed before merging. Your submission must meet the criteria below.

### 1. The project works

Whatever you submit (DApp, library, developer tool, template, or learning resource) should do what your README says it does.

- **DApps and Compact-based projects:** The repository must contain **functional Compact code**. Scaffolding, stub files, or AI-generated placeholder code that does not run will not be accepted.
- **Tools, libraries, SDKs, and templates:** We look for a **working implementation**, not a plan or a README-only repository.
- **Learning resources:** Tutorials and educational content should be complete and usable, not placeholders.

Reviewers may run or inspect the code as part of review.

### 2. Proper attribution

Your repository must credit any projects, libraries, or templates it builds on. Pull requests where attribution has been removed or is unclear will be returned for revision before merging.

### 3. Real use case

The project should represent a genuine application, tool, or experiment built for Midnight Network. Test repositories, forks without meaningful changes, and near-duplicate submissions will not be accepted.

### 4. Open source

All submissions must be publicly accessible repositories with a clear open source license.

### 5. One project per pull request (recommended)

Submit **one new entry per pull request** when possible. This makes review faster and easier to track. If you are adding several related projects from the same maintainer, mention that in the PR description.

## Where to add your project

Add your entry under the section that best matches your project. If you are unsure, pick the closest fit. Reviewers can suggest a better section during review.

| Section | What belongs here |
|---------|-------------------|
| **Getting Started** | Official Midnight team projects for education and onboarding only. Community submissions do not go here. |
| **Smart Contract Primitives** | Reusable contract building blocks (tokens, standards, shared libraries). |
| **Starter Templates** | Boilerplates, scaffolds, and project templates for new Midnight builds. |
| **Developer Tools** | CLIs, SDKs, compilers, indexers, explorers, wallets, MCP servers, and other tools that help developers build, test, deploy, or index. |
| **Finance & DeFi** | Payments, escrow, DEX, staking, tokenization, and other financial applications. |
| **Identity & Privacy** | Credentials, KYC, selective disclosure, and privacy-preserving identity systems. |
| **Gaming** | Games and interactive experiences on Midnight. |
| **Governance** | Voting, crowdfunding, and community governance. |
| **Healthcare** | Health-related applications using Midnight. |
| **Learning Resources** | Tutorials, courses, documentation, and community-created educational content. |
| **Dormant Projects** | Do not add new projects here. See [Updating or removing an entry](#updating-or-removing-an-entry). |

Official ecosystem partners may use the 🔹 marker. Hackathon winners may use 🏆 where applicable. Do not add these markers unless your project qualifies.

## Formatting your entry

- Add your project in **alphabetical order** within the appropriate section (by project name, not URL).
- Use this format:
  ```markdown
  - [Project Name](https://github.com/org/repo) - Brief description of what it does.
  ```
- Keep descriptions **factual, concise, and one sentence**. End with a period.
- Link to the **primary repository** or canonical project URL.
- Avoid marketing language ("best", "revolutionary", "seamless", and similar superlatives).
- Optional: add secondary links on the same line after the description, for example npm or a live demo:
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
| Link goes to a fork or mirror | Use the canonical repository URL |
| Duplicate entry | Search README first; update the existing line instead |
| Wrong section | See [Where to add your project](#where-to-add-your-project) |

### Add the GitHub topic

Add `midnightntwrk` as a topic on your repository: **Settings > General > Topics**. This helps the ecosystem discover your project for future listings and events.

## Review process

When you open a pull request, a reviewer from the developer relations team evaluates it against the criteria above. If we need more time, or if a submission surfaces a question that needs broader team input, we will tell you in the PR thread so you are not left wondering.

Review comments fall into two categories. We will be clear about which is which:

- **Required changes.** Items that must be addressed before merging, usually because they affect correctness, safety, or whether the submission meets the criteria above.
- **Suggestions.** Observations we think are useful for your project, offered as input rather than as merge conditions. You can take them or leave them.

Pull requests will not be merged with unresolved required changes. Suggestions will not block merging.

### Updating your pull request

If a reviewer asks for changes:

1. Push additional commits to the same branch on your fork (or upstream branch).
2. Reply in the PR thread when you have addressed the feedback.
3. Re-request review if the option is available on GitHub.

You do not need to open a new pull request for updates to the same submission.

## If your submission is not ready yet

If your project is early, still being built, or not yet in a state we can list, we will tell you specifically what we would want to see before it is ready. We encourage you to come back when those criteria are met.

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

Ask anything about Midnight. Connect with the community on:

- [Discord](https://discord.com/invite/midnightnetwork)
- [Telegram](https://t.me/Midnight_Network_Official)
- [X](https://x.com/MidnightNtwrk)
- [Midnight Forum](https://forum.midnight.network) (technical Q&A)
- [Midnight Docs](https://docs.midnight.network/)

We appreciate your contributions.
