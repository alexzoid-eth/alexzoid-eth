# AlexZoid · Formal Verification for DeFi

I build formal specifications for complex DeFi protocols using the Certora Prover.

- 🏆 #1 on the Certora Community Contest [leaderboard](https://certora.com/leaderboard)
- A single FV property caught a [Critical bug](#hl-2025-08-valid-state-crit) missed by manual review
- 25 formal verification engagements since 2023 across EVM, Stellar and Solana
- Protocols verified: Morpho, Uniswap v4, Euler v2, Aave, Silo v2

DM [x.com/alexzoid](https://x.com/alexzoid) for engagements

[Full track record](https://github.com/alexzoid-eth/fv-track-record/blob/main/README.md#engagements) · [Highlights](#highlights) · [How an engagement runs](#how-an-engagement-runs) · [Methodology](#methodology)

## Track record

| Date | Specification | Chain | Engagement | Report |
|------|---------|----------|----------|-----|
| 2026 Jun | [Tenor](https://github.com/tenor-labs/tenor-contracts/tree/main/certora) | EVM | [Tenor](https://x.com/TenorFinance) [💬](https://github.com/alexzoid-eth/fv-track-record/blob/main/README.md#hl-2026-07-tenor) | [PDF](https://github.com/alexzoid-eth/fv-track-record/blob/main/pdf/2026_06_tenor_fv_report_alexzoid.pdf) |
| 2026 May | [Morpho Midnight](https://github.com/alexzoid-eth/morpho-midnight-fv/tree/main/certora) | EVM | [Tenor](https://x.com/TenorFinance) | [PDF](https://github.com/alexzoid-eth/fv-track-record/blob/main/pdf/2026_05_morpho_midnight_fv_report_alexzoid.pdf) |
| 2026 Apr | Vault aggregator | EVM | [Cyfrin](https://x.com/Cyfrin) [💬](https://github.com/alexzoid-eth/fv-track-record/blob/main/README.md#hl-2026-07-cyfrin-vault-aggregator) | - |
| 2026 Mar | [Morpho Blue](https://github.com/alexzoid-eth/morpho-blue-fv/tree/main/certora) | EVM | [Tenor](https://x.com/TenorFinance) | [PDF](https://github.com/alexzoid-eth/fv-track-record/blob/main/pdf/2026_03_morpho_blue_fv_report_alexzoid.pdf) |
| 2026 Feb | Parallel | EVM | [Cyfrin](https://x.com/Cyfrin) | [PDF](https://github.com/alexzoid-eth/fv-track-record/blob/main/pdf/2026_02_parallel_fv_report_cyfrin_alexzoid.pdf) |
| 2026 Jan | predict.fun | EVM | [Cyfrin](https://x.com/Cyfrin) [💬](https://github.com/alexzoid-eth/fv-track-record/blob/main/README.md#hl-2026-02-predictdotfun) | [PDF](https://github.com/alexzoid-eth/fv-track-record/blob/main/pdf/2026_01_predict_dot_fun_fv_report_cyfrin_alexzoid.pdf) |
| 2025 Nov | Deriverse | Solana | [Cyfrin](https://x.com/Cyfrin) [💬](https://github.com/alexzoid-eth/fv-track-record/blob/main/README.md#hl-2025-12-cyfrin-solana-dex) | [PDF](https://github.com/alexzoid-eth/fv-track-record/blob/main/pdf/2025_11_deriverse_fv_report_cyfrin_alexzoid.pdf) |
| 2025 Oct | Accountable | EVM | [Cyfrin](https://x.com/Cyfrin) [💬](https://github.com/alexzoid-eth/fv-track-record/blob/main/README.md#hl-2025-10-accountable) | [PDF](https://github.com/alexzoid-eth/fv-track-record/blob/main/pdf/2025_10_accountable_fv_report_cyfrin_alexzoid.pdf) |
| 2025 Sep | l2-angstrom | EVM | [Cyfrin](https://x.com/Cyfrin) [💬](https://github.com/alexzoid-eth/fv-track-record/blob/main/README.md#hl-2025-10-cyfrin-sorella-angstrom) | [PDF](https://github.com/alexzoid-eth/fv-track-record/blob/main/pdf/2025_09_sorella_l2_angstrom_fv_report_cyfrin_alexzoid.pdf) |
| 2025 Aug | [Licredity](https://github.com/alexzoid-eth/licredity-v1-core-fv/tree/cyfrin-formal-verification/certora) | EVM | [Cyfrin](https://x.com/Cyfrin) [💬](https://github.com/alexzoid-eth/fv-track-record/blob/main/README.md#hl-2025-09-licredity) | [PDF](https://github.com/alexzoid-eth/fv-track-record/blob/main/pdf/2025_08_licredity_fv_report_cyfrin_alexzoid.pdf) |
| ... | [more engagements in the full table →](https://github.com/alexzoid-eth/fv-track-record/blob/main/README.md#engagements) | | | |

## Highlights

<a name="hl-2026-07-tenor"></a>[2026 Jul](https://x.com/TenorFinance/status/2077385238729121900) · Tenor credits my key FV contributions to security

<a href="https://x.com/TenorFinance/status/2077385238729121900"><img src="https://raw.githubusercontent.com/alexzoid-eth/fv-track-record/main/assets/2026-07-15-tenor-testing-fuzzing-fv.png" width="400" alt="Tenor (@TenorFinance): Testing, Fuzzing, &amp; Formal Verification. Beyond design, Tenor's contracts have undergone unit and integration testing, as well as fuzzing. Key properties of the contracts have also been formally verified using the Certora Prover. Thanks to Alex Zoid for key contributions on Formal Verification."></a>

<a href="https://x.com/TenorFinance/status/2077385238729121900"><img src="https://raw.githubusercontent.com/alexzoid-eth/fv-track-record/main/assets/2026-07-15-tenor-special-thanks.png" width="400" alt="Tenor: Special thanks. We're grateful to every team that helped us get here: the researchers at Blackthorn, Cantina, Guardian, Obsidian, and TrustSec, as well as Alex Zoid. Also, thank you to the Morpho protocol team for their support."></a>

---

<a name="hl-2025-08-valid-state-crit"></a>[2025 Aug](https://x.com/alexzoid/status/1960987430426747273) · My FV property caught a Critical bug missed by manual review

<a href="https://x.com/alexzoid/status/1960987430426747273"><img src="https://raw.githubusercontent.com/alexzoid-eth/fv-track-record/main/assets/2025-08-28-alexzoid-valid-state-crit.png" width="400" alt="AlexZoid FV (@alexzoid): Thanks for the kind words! It was an absolute pleasure wizarding @certora Formal Verification with you @cyfrin folks! Quoting Dacian (@DevDacian): this was in a recent Cyfrin private audit, great stuff @alexzoid! Original post by @alexzoid: In a past private engagement with auditors, my @certora Formal Verification valid state property caught a CRIT in the assembly of a complex lending protocol, missed by manual reviews. Clear proof of FV's value in complementing fuzzing and classic audits."></a>

---

<a name="hl-2025-05-certora-leaderboard"></a>[2025 May](https://x.com/alexzoid/status/1922710720015147309) · Moved up to 🏆 #1 on the Certora all-time [leaderboard](https://certora.com/leaderboard)

<a href="https://x.com/alexzoid/status/1922710720015147309"><img src="https://raw.githubusercontent.com/alexzoid-eth/fv-track-record/main/assets/2025-05-14-certora-leaderboard-1st.png" width="400" alt="AlexZoid (@alexzoid): hit #1 rank on @certora all-time leaderboard with my past @SiloFinance FV contest work! Certora leaderboard: rank 1, alexzoid-eth, reward 59,132 USD, 10 contests"></a>

---

... [more highlights in the full list →](https://github.com/alexzoid-eth/fv-track-record/blob/main/README.md#highlights)

## How an engagement runs

1. **Scene plan.** Before any rule is written, I draw a schematic plan of verification scenes: what is verified, which contracts are compiled together, which are modelled in CVL, and what stays out of scope. You know what you will get before the work starts.
2. **Delivered scene by scene.** Specs, report sections and the developer guide grow as properties are proved, so you follow the progress instead of waiting for a final drop.
3. **You get:**
   - **Specification suite**: a self-contained `certora/` folder you copy into your repo root as is, with CVL specs, confs, harnesses, models, mutants and the commands to reproduce every result. See it [in Tenor's repo](https://github.com/tenor-labs/tenor-contracts/tree/main/certora).
   - **Report** in Markdown and PDF: scope, scenes, assumptions, and one row per property with its status and the mutants it catches.
   - **Developer guide**, internal and written for your team: how the suite is built and the mindset behind it, shown on your own code, so your developers can extend the specification on their own.
   - **Your invariants**: come with your own list and, on top of my own properties, I also go through every item, linking each proved one to its rule (a good [example](https://github.com/tenor-labs/tenor-contracts/blob/main/certora/PROPERTIES.md) of such a list).

## Methodology

- **Scenes.** A scene is the set of contracts compiled for one verification run. The contract under verification is real bytecode; a neighbour is either a lightweight CVL model or, when a property must see both sides of a call, compiled and linked alongside it.
- **Valid state first.** Constraints on storage are proved as invariants and reused through `requireInvariant`, instead of piling unproved `require`s into every rule.
- **Tagged assumptions.** Every `require` says why it is allowed: `SAFE` excludes nothing reachable · `SCOPE` narrows a rule to the logic it checks · `UNSAFE` knowingly drops reachable states · `TRUSTED` relies on a party outside the scene · `PROVED` restates a fact proved elsewhere · `ASSERT` mirrors a revert of the real code.
- **Property categories.** Certora's [categories](https://github.com/Certora/Tutorials/blob/master/06.Lesson_ThinkingProperties/Categorizing_Properties.pdf) (Valid State, State Transitions, Variable Transitions, High Level, Unit Tests), plus Reverts, Reachability, Access Control and EIP Compliance. Parametric rules call an arbitrary function, so functions added later are covered without rewriting the rule.
- **Quality checks.** A passing rule is not evidence on its own, so every proved rule has its own mutation, a fault planted in the source, which the rule catches to prove that it works.

---

[FV resources](https://github.com/alexzoid-eth/fv-resources) · [alexzoid.com](https://alexzoid.com)
