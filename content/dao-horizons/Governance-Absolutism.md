---
date: '2025-03-11T16:43:23-03:00'
draft: false
title: CAOs in DAOs' Clothing. An Overview on Governance Absolutism
tags:
- dao
- cao
- absolutism
- governance
- centralization
- disposition
- conciliatorics
---

DAOs, as their name imply, aim for decentralization. But their behavior and design may be corrupted towards a centralized state. While most DAOs have to deal with temporary centralization vectors—like governance attacks and admin paralysis—sometimes, centralized status becomes permanent. This goes against the core doctrine of diverse participation prevalent in DAO discourse. Instead of distributing governance action to its community, a DAO may fall into **governance absolutism**. 

We'll go over four types of governance absolutism related to DAOs:
- Parasitic Absolutism
- Apathetic Absolutism
- Vetocratic Absolutism
- Bureaucratic Absolutism

At the end we'll see how these types integrate, both practical and systemically. But first, let's do a brief overview of absolutism as a concept.

---

## Traditional Absolutism

The "absolutism" term comes from political science and philosophy. In regular political discourse, it's associated with absolute monarchies—a royal figure holding ultimate power—and dictatorships—both formalized and covert ones. Monarchs and dictators are the figures associated with the face of absolutism—applying and benefiting from total control. Although, this association usually dismisses that no leader rules alone, and that the executioner can become the executed.

One entity controlling an entire DAO is difficult and probably unsustainable. Unlike real world populations, individuals participating in the blockchain can depart from such scenario, even if leaving carries resource losses. Therefore, if a DAO may devolve into absolutism, it has to be **done covertly**, through **design flaws** or **normalized over time**. But there is one specific dimension that could set apart DAO absolutism from its traditional form.

Traditional absolutist leaders are visible and exposed—whereas DAO rulers can operate from the shadows. The **anonymity** aspect, intrinsic to the blockchain, may condition absolutism methods. No longer fearing physical retaliation or replacement, DAO's rulers can optimize their control strategy and avoid tyrannical action—not out of kindness, but for the convenience of maintaining control without resistance. In this scenario, "absolutism" loses its focus on **leader figures**, and makes **uncontested control** its sole objective. 

With that said, now we can explore concrete examples of DAO absolutism.

---

## Parasitic Absolutism

Parasitic Absolutism occurs when external entities or powerful stakeholders extract value or control from a DAO for their own benefit rather than the collective's. As with biological parasites, this method may be implemented by the same hand in multiple projects simultaneously. The most common subtype, **plutocratic absolutism**, emerges when wealthy participants ("whales") accumulate enough governance tokens to control decision-making. 

This form of absolutism is particularly prevalent in token-weighted voting systems where capital concentration translates directly into governance power. Other external entities could also gain influence and steer governance for their own benefit rather than communal interests. Venture capitalist, partner projects and off-chain entities may intervene in governance procedure. In the future, government agencies may gain legal authority to take control over a DAO, either publicly or covertly.

Here are some examples of parasitic absolutism:
- **MakerDAO whale concentration**: At various points, large token holders have controlled significant voting power, with studies showing that fewer than 10 addresses controlled over 50% of voting power during critical decisions.
- **Curve Wars**: Large holders of CRV tokens (particularly Yearn and Convex) accumulated governance power to direct liquidity incentives toward their preferred pools.

---

## Apathetic Absolutism

Apathetic Absolutism arises not from active power seizure but from community disengagement. When participation rates are low, small coordinated groups can control outcomes despite holding relatively modest token positions. This form thrives on governance fatigue, technical barriers to participation, and the delegation of voting power without adequate oversight. 

Many DAOs see turnout rates below 5%, creating governance vacuums where decisions affecting thousands of stakeholders and millions in treasury funds are determined by a handful of active participants. The danger lies not in overt takeovers but in the quiet erosion of collective governance through consistent non-participation.

Here are some examples of apathetic absolutism:
- **Uniswap governance participation**: Despite having thousands of token holders, many governance proposals see participation rates below 5%, allowing small groups to determine outcomes.
- **Gitcoin delegate concentration**: Many token holders delegate voting power without actively monitoring how their delegates vote, creating concentrated power in a few active delegates.

---

## Vetocratic Absolutism

Vetocratic Absolutism represents governance systems that maintain an illusion of decentralization while reserving ultimate authority through emergency powers, multisigs, or veto capabilities. Core teams often justify these mechanisms as necessary safeguards against attacks or erroneous decisions, but they effectively undermine true community sovereignty. Vetocratic absolutism allows for trivial proposals to be passed, but blocks any measure that threatens admin control.

Examples include "guardian" multisigs that can override DAO decisions, timelock controllers that can pause implementations, and foundations that maintain special powers over protocol parameters. This form of absolutism is particularly insidious because it often exists with community consent, presented as temporary or protective, while effectively establishing governance ceilings beyond which decentralization cannot progress.

Here are some examples of vetocratic absolutism:
- **Tornado Cash DAO's guardian mechanism**: The multisig had effective veto power over governance decisions.
- **ENS DAO's "veto council"**: Created to intervene in potentially harmful decisions, showing the tension between security and decentralization.

---

## Bureaucratic Absolutism

Bureaucratic absolutism is a DAO structure that on the surface may be open, but blocks governance by **procedural adversity**. This is done by putting technical, informational and temporal barriers that disincentive participation. Power can be centralized through the creation of convoluted processes, opaque documentation, technical barriers, and information asymmetries—all hallmarks of traditional bureaucracies repurposed for the blockchain context.

We can split bureaucratic absolutism into subtypes:

1. **Technical Absolutism** - Where governance is controlled by those who understand or have access to the technical infrastructure (developers, those who control repos/deployments)

2. **Informational Absolutism** - Control through asymmetric information; core teams withhold crucial information from members to influence decisions

3. **Temporal Absolutism** - Manipulating timing of proposals, votes, or implementations to ensure favorable outcomes (e.g., rushing important votes during low participation periods)

By creating labyrinthine governance structures or requiring specialized expertise to participate meaningfully, power becomes concentrated among core contributors, technical experts, or those with privileged access to information. 

Here are some examples of bureaucratic absolutism:

- **Optimism's complex governance structure**: Multiple committees, voting groups, and complex multi-phase proposal processes create barriers to participation for average members.
- **Aave's proposal process**: The technical complexity of crafting executable code for proposals effectively limits who can participate in meaningful governance.
- **The MakerDAO governance portal**: The highly technical nature of parameter adjustments and risk models means only those with specialized knowledge can meaningfully assess proposals.

---

The table below offers a high-level overview of the four absolutist types, their key traits, and potential remedies:

| **GOVERNANCE ABSOLUTISM** | **Core Properties** | **Corrective Strategies** |
|---|---|---|
| **Parasitic** | Hidden control via private key holders or privileged actors leeching influence from a decentralized shell. | Transparent power disclosures; privilege tracking tools; exit-trigger mechanisms. |
| **Apathetic** | Voter disengagement leads to passivity, enabling quiet centralization or stagnation. | Participation incentives; quorum reforms; multi-channel engagement. |
| **Vetocratic** | Excessive veto powers prevent change, rewarding inertia and sabotaging evolution. | Simplified decision pathways; scoped consensus; constitutional overrides. |
| **Bureaucratic** | Procedural adversity becomes a self-justifying obstacle to action. | Minimal viable structure audits; role pruning; automation of routine governance. |

---

## Concurrent Types and Systemic Foundations

These absolutism types are not exclusionary, and DAOs may suffer from multiple types concurrently. Also, different entities can dispute control over a DAO, employing the strategy most congruent with their capabilities. And if one entity can't overcome the dominant one, they could—paradoxically—start pushing for more decentralization to sabotage their competitors. Here are some examples of concurrent absolutism types:

- **Lido's dual governance structure**: Features elements of both vetocratic and bureaucratic absolutism through its complex decision-making framework.
- **dYdX's transition to independence**: Shows tensions between technical control, plutocratic concerns, and governance participation.

Anyone who had the chance to read our **Conciliatorics** treatise—part of Lokapal Foundations—may be able to relate governance absolutism to the concepts of **unification synthesis**. Indeed, there is a direct path between systemic unification and **disposition absolutism**. In this scenario, conciliation efforts are suppressed, leading to a state of **perdurable dysfuncionality**. 

If the reader is interested in expanding governance absolutism concepts into an analysis of the systemic foundations of centralization, please visit the [**Lokapal Foundations**](https://lokapal-xyz.github.io/foundations/) website for the philosophical grounding of this discussion.

![banner](../../img/banner.png)

We explored DAO absolutism from the general to the specific. As you could see, this topic is far from exhausted—too many avenues for exploration remain active. We hope that this framework was of use, and we encourage you to apply this framework when analyzing DAOs. Stay in touch with **DAO Horizons** for future articles that will expand on these ideas.

Do you have any questions or suggestions? Please contact [**Lokapal Research**](../../contact/) and let's continue building a better horizon for DAOs. Thank you!

