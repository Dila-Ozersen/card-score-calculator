# Card Score Calculator

A **JavaScript and React** application for collecting cards, building teams, and calculating team totals using data from **Love Live! School Idol Festival All Stars**.

Independently programmed by **Dila Ozersen** for UMass Amherst's **COMPSCI 326 Web Programming** course in **Summer 2024**.

**Repository:** https://github.com/Dila-Ozersen/card-score-calculator

**Original repository (preserved):** https://github.com/DilaOzersen/card-score-calculator

## Features

Dila confirms that the class application supported:

- Account registration and login.
- Random card pulls using a gacha mechanism.
- Adding pulled cards to a saved inventory.
- Selecting cards from the inventory for a team.
- Calculating team totals across three card-stat categories.

These are Dila's reported implementation results, not a new runtime test of the public repository.

## Scoring

The three categories are:

- **Appeal**
- **Stamina**
- **Technique**

The confirmed scoring description is simple aggregation of stored values across the selected cards:

```text
Team Appeal    = sum of selected cards' Appeal values
Team Stamina   = sum of selected cards' Stamina values
Team Technique = sum of selected cards' Technique values
```

This is not a claim of complete game simulation or comprehensive reproduction of the game's scoring rules.

### Leader Skill limitation

Cards also have a Leader Skill associated with the leader slot. Dila recalls displaying the skill but does not believe its effect was applied to final scores; she is unsure about the final implementation.

**Leader Skill scoring remains unconfirmed.** Do not assume displayed Leader Skills affect the calculated totals. No additional bonus, weighting, or optimization rule is asserted here.

## Account and inventory behavior

Dila recalls creating a username/password account and logging in with those credentials. Registration, saved inventory, and gacha/card pulls are confirmed in her report. No two-factor authentication was built.

The exact authentication/session mechanism and password-storage implementation have not been established. No production-security claim is made.

## Technology stack

Dila confirmed the technologies named in the earlier README:

- JavaScript
- React
- Node.js
- Express.js
- PouchDB

Exact versions, package locations, and database initialization details remain undocumented in her latest answers.

## Getting the source

```bash
git clone https://github.com/Dila-Ozersen/card-score-calculator.git
cd card-score-calculator
```

This obtains the source only.

### Installation and running

Dila states that working instructions exist if dependencies are downloaded properly, but did not provide a link or the exact installation/startup commands in her answers. The older README's incomplete clone/directory instructions and previously unverified setup steps have not been established as reproducible.

**A complete setup guide remains unresolved:** required versions, package working directories, configuration, card-data initialization, startup commands, and local URLs still need to be documented from the implementation. This README does not invent commands or claim a successful clean-checkout run.

## Data source and attribution

Dila identifies [Kach Again's SIFAS card database](https://kachagain.com/sifas/cards.php) as the source of all card data used in the project.

The source and usage terms for any card images have not been separately confirmed. Data attribution does not establish ownership or redistribution permission; applicable usage terms and third-party credits remain unresolved.

## Testing and known limitations

- No specific checked scoring example, automated test command, test result, or clean-checkout verification was supplied.
- Leader Skill scoring is uncertain and must not be treated as implemented.
- Duplicate-card rules, team-size limits, empty-team handling, invalid/missing-value handling, and current update behavior after changing a team have not been confirmed.
- Current runtime reproducibility, deployment, and a screenshot/demo link remain unverified.

These are documentation/evidence gaps, not claims that every listed behavior is broken or absent.

## Author

**Dila Ozersen**

- [Current GitHub account](https://github.com/Dila-Ozersen)
- [Older account hosting the original project](https://github.com/DilaOzersen)
- [LinkedIn](https://www.linkedin.com/in/dila-ozersen-b50a88326/)

## License

No project license was identified in the latest answers. This document does not assign one or grant rights to third-party card data/images.

## Documentation basis

Finalized October 20, 2026, using Dila's completed essential README questionnaire dated October 20, the October 19 career profile, and the prior README review. Game identity, category names, inventory/gacha features, and the backend/database stack are now confirmed by Dila's report. Implementation and runtime were not independently audited. Published in a copy under Dila-Ozersen with the original Git history preserved. The school-account repository and original local career documents remain unchanged.
