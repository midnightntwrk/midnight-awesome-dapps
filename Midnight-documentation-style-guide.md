# Tech Content Style Guide

## 1\. Introduction

Our Mission: To empower developers and users to build the future of decentralised applications. Our documentation is the front door to our ecosystem. Its purpose is to make building on Midnight as seamless, intuitive, and efficient as possible.

This style guide sets standards for Midnight's technical documentation, ensuring consistency, clarity, and accuracy for a global audience of developers, validators, and technical users. Our highest priority is clarity.

## 2\. Core Principles: The TL;DR

If you remember nothing else, remember this:

* **Clarity over cleverness**: Use simple, direct language. Avoid jargon and academic prose. The goal is to transfer information, not to sound smart.  
* **Developer-first:** Respect our audience's time. Get to the point quickly. Structure content for scannability and practical application.  
* **Precision and accuracy**: We are a Layer 1 protocol; trust is paramount. Our technical documentation must be flawless. Every parameter, command, and description must be correct and unambiguous.  
* **Empowering and approachable**: Our tone should encourage building. We are a guide and a partner, not a gatekeeper.

## 3\. Tone of Voice

Our tone is our personality. It should be consistent across all written materials.

We are authoritative and helpful. We are the experts, but we are here to serve our community.

| We are... | We are not... |
| :---: | :---: |
| Direct and Concise | Vague, Verbose, Academic |
| Authoritative & Confident | Arrogant, Elitist, Dogmatic |
| Helpful & Empowering | Patronising, Hand-holding |
| Technical & Precise | Jargony, Overly Casual, Salesy |
| Modern & Innovative | Hyped, Unprofessional |

*Example Tone:*

* Good (Direct, Helpful): *"To deploy a smart contract, you first need to compile the source code into bytecode."*  
* Bad (Academic, Passive): *"In order to proceed with the deployment of a smart contract, it is first necessitated that the source code be compiled into what is known as bytecode."*  
* Bad (Salesy, Hyped): *"Unleash the power of your revolutionary dApps by seamlessly deploying smart contracts\! Just compile the source code."*

## 4\. Language and Style Guide

### 4.1. Voice and Tense

* Use the Active Voice: The active voice is more direct, concise, and easier to understand.  
  * Yes: *"Install the Lace wallet extension"*  
  * No: *"The Lace wallet extension should be installed"*  
* Use the Present Tense: Describe processes and system states in the present tense. This makes the documentation feel current and direct.  
  * Yes: *"The network rejects blocks with an invalid signature."*  
  * No: *"The network will reject blocks that have an invalid signature."*

### 4.2. Addressing the Reader

* Use "you" to address the reader directly. This creates a helpful, conversational tone.  
  * Yes: *"Before you begin, make sure you have the CLI installed."*  
  * No: *"The user should first install the CLI."*  
* When referring to Midnight, never use “we”   
  * Anything about the network shouldn't be in first person, nothing should imply the network has agency.   
  * Midnight (network) doesn't want, plan, organize, think or have goals.  
  * We \+ agency is okay.   
    * E.g. in the context of certain entities or teams "we at the DevRel team...", "The Midnight Foundation plans", "The team at Shielded is focusing on...", "Our goal at the foundation is..."

### 4.3. Word Choice: Keep it Simple

Choose simple, common words over complex or formal ones. Use specific, action oriented verbs.

* Accessibility standards  
  * Inclusive language:

| Inclusive Terms | Avoid |
| :---: | :---: |
| Allowlist | Whitelist |
| Blocklist | Blacklist |
| Primary/secondary | Master/slave |
| Users | Guys |

  


  * Screen reader compatibility  
    * Guidelines:  
      * Use proper heading hierarchy  
      * Include alt text for images  
      * Use descriptive link text  
      * Structure content logically and include links to relevant articles and required reading at the start of the piece. 

| Preferred link text | Avoid |
| :---: | :---: |
| Download the Midnight SDK | Click here |
| View the complete API reference | Read more |

### 4.4. Formatting

* Headings: Use sentence case for all headings. It's more modern and readable.  
  * Yes: "Set up your development environment"  
  * No: "Set Up Your Development Environment"  
* Lists:  
  * Use numbered lists for sequential steps or procedures.  
  * Use bulleted lists for items that have no specific order.  
* Code and Commands:  
  * Inline code elements like function names (calculate\_gas()), filenames (config.toml), parameters (\--gas-limit), and error messages should be enclosed in backticks.  
  * Multi-line code blocks and terminal commands should be in their own fenced code blocks. Specify the language for syntax highlighting (e.g., bash, rust, json).  
* Emphasis: Use bold for UI elements and for critical emphasis. Use *italics* sparingly, primarily for introducing new terms for the first time.  
* Formatting Specifics:  
  * Addresses, Hashes, and IDs: Always format these as monospace to distinguish them from regular text. Example: 0x1A2b...c3D4.  
  * Token Amounts: Use the ticker symbol. Example: "The fee is 0.05 \[TICKER\]."  
* Page organisation  
  * Every page should include:  
    * Clear title in sentence case  
    * Brief introduction explaining the page's purpose  
    * Target audience (when relevant)  
    * Prerequisites (when applicable)  
    * Step-by-step instructions (for procedures)  
    * Next steps or related content  
    * Troubleshooting (when relevant)

### 4.5. Punctuation

* Serial Comma (Oxford Comma): Always use the serial comma in lists of three or more items to prevent ambiguity.  
  * Yes: "Our ecosystem consists of developers, validators, and users."  
  * No: "Our ecosystem consists of developers, validators and users."

4.6. SEO Optimisation

* Description guidelines:  
  * 120-160 characters for optimal SEO  
  * Include primary keywords naturally  
  * Write compelling copy that encourages clicks  
  * Use sentence case  
* Keywords:  
  * 5-10 relevant terms  
  * All lowercase  
  * Include variations and synonyms  
  * Focus on user intent

## 5\. Protocol-Specific Terminology

Consistency in our technical terms is crucial for clarity.

* Capitalisation Standards  
  * Always capitalize these terms:  
    * Midnight (the Blockchain Network)  
    * Testnet (when referring to the test network)  
    * Mainnet (when referring to the production network)  
    * Lace (the wallet name)  
    * DApp (decentralized application)  
    * ZK (zero-knowledge, when used as abbreviation)  
    * ZKP (zero-knowledge proofs)  
  * Use lowercase for these terms:  
    * tDUST (testnet tokens \- lowercase ‘t’, uppercase ‘DUST’)  
    * proof server (unless beginning a sentence)  
    * smart contract (unless beginning a sentence)  
    * zero-knowledge (when spelled out, unless beginning a sentence)  
* Technical terms:  
  * tDUST tokens: Test tokens on Midnight testnet  
  * proof server: Infrastructure for generating zero-knowledge proofs  
  * privacy-preserving: Preferred over’private’ when describing transactions  
  * ZK proofs: Acceptable abbreviation for zero-knowledge proofs.   
* Consistent terminology:  
  * Use “wallet address” not “wallet ID’  
  * Use “transaction hash” not “transaction ID”  
  * Use ‘smart contract’ not ‘contract’   
  * Use “DApp’ not “dApp” or “dapp”

## 6\. Code documentation standards [(taken from here)](https://docs.midnight.network/contribute/style-guide)

* Code blocks: 

Use proper syntax highlighting and include context:

````

**Install dependencies:**
```bash
npm install @midnight/sdk
````

Configure your environment:

```

const config = {
  network: 'testnet',
  proofServer: 'http://localhost:6300'
};
```

````

### API documentation
Follow consistent API documentation format:
```markdown
### `sendTransaction()`
Sends a transaction to the Midnight network.
**Parameters:**
- `to` (string): Recipient wallet address
- `amount` (number): Amount in tDUST
- `options` (object, optional): Transaction options
**Returns:** Promise\<TransactionHash\>
**Example:**
```javascript
const hash = await sendTransaction(
  'mn_shield-addr_test1...',
  10.0,
  { privacy: true }
);
**Example:**
```javascript
const hash = await sendTransaction(
 'mn_shield-addr_test1...',
 10.0,
 { privacy: true }
);
````

````

### Variable naming
Use consistent naming in examples:
| ✓ Preferred | Context |
|--------------------|-----------------------------------------|
| `walletAddress`    | camelCase for JavaScript                |
| `transaction_hash` | snake_case for APIs                     |
| `PROOF_SERVER_URL` | CONSTANT_CASE for environment variables |
## Visual elements
### Admonitions
Use appropriate admonition types:
```markdown
:::tip[Helpful hint]
Use this for optimization tips and best practices.
:::
::info[Additional information  ]
Use this for supplementary context and explanations.
:::
:::warning[Important notice]
Use this for critical information users must know.
:::
:::caution[Potential issues]
Use this for common pitfalls and error prevention.
:::
:::danger[Critical warning]
Use this sparingly for serious security or data loss risks.
::::
````

* Tabs for multiple options

Use tabs for alternative approaches:

```
<Tabs>
<TabItem value="mac" label="macOS">
Instructions for macOS users.
</TabItem>
<TabItem value="linux" label="Linux">
Instructions for Linux users.
</TabItem>
</Tabs>

```

* Images and diagrams:  
  * Use descriptive alt text  
  * Include captions when helpful  
  * Optimize for different screen sizes  
  * Use consistent styling

```

![Lace wallet interface showing balance](/img/lace-wallet-balance.png)
*Figure 1: Lace wallet displaying tDUST balance*
```

* Metadata standards

Page frontmatter

Use consistent metadata structure:

```

---
title: Page title in sentence case
description: SEO-friendly description, 120-160 characters
sidebar_position: 1
sidebar_label: Short navigation label
tags: [category, topic, lowercase]
slug: /custom-url-path
---
```

## 7\. Style Guide for Video Content

Video is a powerful tool for tutorials, concept explanations, and community updates. The same core principles of clarity, precision, and a developer-first mindset apply, but they manifest in different ways. This section guides you in producing high-quality, on-brand video content.

### 7.1. Applying Core Principles to Video

* Clarity: A clear video has a logical flow, legible on-screen text, and intelligible speech. State the goal of the video within the first 30 seconds. Use chapter markers (timestamps) in the video description for longer tutorials so viewers can jump to the section they need.  
* Developer-First: Respect the viewer's time. Get straight to the technical content. Edit ruthlessly to remove fluff, long pauses, and mistakes. Keep videos focused on a single topic where possible.  
* Precision: Rehearse complex explanations or code walkthroughs. Ensure any code, commands, or addresses shown on screen are 100% accurate. If you make a mistake while recording, correct it immediately on screen or with a text overlay.  
* Empowering Tone: Your vocal tone and on-screen presence matter. Speak with confidence and enthusiasm. Be the helpful expert who wants the viewer to succeed.

### 7.2. Production Quality: The Foundation of Trust

Poor audio or video quality undermines your credibility. Strive for professionalism in every recording.

* Audio is King: Viewers will tolerate mediocre video but not bad audio.  
  * Use an External Microphone: Never use your laptop's built-in microphone. A dedicated USB, lapel, or shotgun microphone is essential.  
  * Record in a Quiet Environment: Avoid rooms with echo, background noise, or interruptions.  
* High-Resolution Video:  
  * Resolution: Record and export all video in at least 1080p (1920x1080). 4K is preferred for screen recordings as it provides flexibility to zoom and crop without losing quality.  
  * Lighting: Use good, soft lighting. A simple key light or ring light is effective. Face your primary light source and avoid sitting with a bright window behind you.  
* Video Angles and Framing:  
  * Talking Head: Position the camera at eye level. Frame yourself from the mid-chest up.  
  * Screencasts: Hide desktop clutter, close unnecessary applications, and turn off notifications. Increase the font size in your code editor and terminal so it is easily legible, even on a mobile device.  
  * Composition: Keep videos dynamic by switching between a full-screen screencast, your "talking head," and a picture-in-picture layout.

### 7.3. On-Screen Content and Branding

All video content must be consistent with the Midnight brand. \[[Brand Toolkit](https://midnight.network/brand-hub) & [Brand Guidelines](https://docs.google.com/presentation/d/1fg-okB5_kfxWipEsKtaTKxGwwOFqoXlphi3d6AmxGFc/edit?slide=id.g2b408857f2f_1_44#slide=id.g2b408857f2f_1_44)\]

\[*NB: Updated Midnight brand collateral is in production*\]

* Use Official Brand Collateral:   
  * Intros and Outros: Use the official, pre-rendered video intro and outro sequences for Midnight.  
  * Logos and Watermarks: Use the approved logo watermark, placed tastefully in one corner of the screen (e.g., top-right) throughout the video.  
  * Text & Lower Thirds: Any on-screen text overlays or slides must use our official brand fonts and colour palette.  
  * *All official brand assets can be found in the shared Brand Kit folder.*  
* Screen Recordings: When demonstrating a command-line interface or code editor, use a neutral or brand-approved theme. Avoid distracting or highly personalised editor setups.

### 7.4. Use of Music and Memes

Our primary goal is to educate. Entertainment is secondary and should be used sparingly to enhance, not distract from, the core message.

* Music:  
  * Music should only be used in intros, outros, or brief transitional moments.  
  * Never play music over a technical explanation or code walkthrough.  
  * Use only pre-approved, royalty-free tracks from our shared brand library. The volume should be low enough to be subtle. \[*NB:  Pending*\]  
* Memes and Humour:  
  * A little goes a long way. Humour must be universally understood, witty, and relevant to a global developer audience.  
  * The Litmus Test: If you have to question whether a meme or joke is appropriate, do not use it.  
  * Avoid: Dated memes, controversial topics, and inside jokes that may alienate parts of our community. We are building a professional and inclusive ecosystem.
