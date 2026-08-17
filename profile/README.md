<p align="center">
  <img src="https://raw.githubusercontent.com/aave-dao/.github/main/assets/aave-logo.jpg" alt="Aave DAO"  width="600">
</p>

<h1 align="center">Aave DAO tech</h1>

<table>
<thead>
  <tr>
    <th width="220">Repository</th>
    <th>Description</th>
  </tr>
</thead>
<tbody>
  <tr><td colspan="2"><h3>Core Protocol</h3></td></tr>
  <tr>
    <td><a href="https://github.com/aave-dao/aave-v3-origin">aave-v3-origin</a></td>
    <td>Core codebase for Aave V3.1–3.x protocol contracts.</td>
  </tr>
  <tr><td colspan="2"><h3>GHO</h3></td></tr>
  <tr>
    <td><a href="https://github.com/aave-dao/gho-origin">gho-origin</a></td>
    <td>Core smart contracts for GHO.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/aave-dao/GhoDirectMinter">GhoDirectMinter</a></td>
    <td>GHO facilitator that mints and supplies GHO directly into Aave pools.</td>
  </tr>
  <tr><td colspan="2"><h3>Governance</h3></td></tr>
  <tr>
    <td><a href="https://github.com/aave-dao/aave-governance-v3">aave-governance-v3</a></td>
    <td>Multi-chain governance system for creating, voting on, and executing Aave proposals.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/aave-dao/aave-delivery-infrastructure">aave-delivery-infrastructure</a></td>
    <td>Cross-chain messaging layer for delivering Aave governance actions across networks.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/aave-dao/adi-deploy">adi-deploy</a></td>
    <td>Deployment and maintenance tooling for a.DI infrastructure.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/aave-dao/adi-dashboard">adi-dashboard</a></td>
    <td>Monitoring dashboard for a.DI cross-chain envelope delivery, bridge adapters, and linked governance proposals.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/aave-dao/aave-governance-cache">aave-governance-cache</a></td>
    <td>Cache layer that indexes on-chain governance data into static JSON for the governance frontend.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/aave-dao/aave-governance-interface">aave-governance-interface</a></td>
    <td>Frontend for browsing proposals, casting votes, and interacting with Aave governance.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/aave-dao/aave-proposals-v3">aave-proposals-v3</a></td>
    <td>Monorepo for building, testing, and submitting Aave governance proposals.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/aave-dao/aave-proposals-reports">aave-proposals-reports</a></td>
    <td>Security review reports for Aave governance proposals.</td>
  </tr>
  <tr><td colspan="2"><h3>Umbrella</h3></td></tr>
  <tr>
    <td><a href="https://github.com/aave-dao/aave-umbrella">aave-umbrella</a></td>
    <td>Staking-based deficit coverage system backed by Aave pool assets.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/aave-dao/aave-umbrella-ui">aave-umbrella-ui</a></td>
    <td>DAO-owned frontend for staking, rewards, and position management in Aave Umbrella.</td>
  </tr>
  <tr><td colspan="2"><h3>Tooling</h3></td></tr>
  <tr>
    <td><a href="https://github.com/aave-dao/aave-helpers">aave-helpers</a></td>
    <td>Shared toolkit for Aave proposal development and testing.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/aave-dao/aave-rewards-configuration">aave-rewards-configuration</a></td>
    <td>CLI toolkit for generating, testing, and simulating Umbrella rewards and Aave liquidity mining configurations.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/aave-dao/aave-address-book">aave-address-book</a></td>
    <td>Registry of deployed Aave ecosystem contract addresses.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/aave-dao/aave-permissions-book">aave-permissions-book</a></td>
    <td>Index of permissions, roles, and upgrade authority across the Aave contract system.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/aave-dao/permissions-search">permissions-search</a></td>
    <td>Web app for searching and visualizing permissions, roles, and Safe wallets across the Aave ecosystem.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/aave-dao/aave-price-feeds">aave-price-feeds</a></td>
    <td>Custom oracle adapters that add price caps and safety bounds on top of Chainlink feeds.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/aave-dao/aave-proof-of-reserve">aave-proof-of-reserve</a></td>
    <td>Smart contracts integrating Chainlink Proof of Reserve to verify asset backing and freeze undercollateralized reserves.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/aave-dao/aave-v3-risk-stewards">aave-v3-risk-stewards</a></td>
    <td>Constrained steward contracts for bounded Aave V3.x risk parameter updates.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/aave-dao/aave-risk-agents">aave-risk-agents</a></td>
    <td>Contracts for validating and applying risk parameter updates from the Risk Oracle into Aave protocol.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/aave-dao/aave-risk-stewards">aave-risk-stewards</a></td>
    <td><b>[Archived]</b> Legacy tooling for executing updates through the original Risk Steward workflow.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/aave-dao/seatbelt-gov-v3">seatbelt-gov-v3</a></td>
    <td>Simulation and verification tool for reviewing Aave governance proposals before execution.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/aave-dao/bgdash">bgdash</a></td>
    <td>RPC-based explorer for Aave reserve, E-Mode, and Umbrella data across pools and chains.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/aave-dao/toolkit">toolkit</a></td>
    <td>Collection of web3 developer tools, ABIs, and shared utilities.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/aave-dao/github-workflows">github-workflows</a></td>
    <td>Reusable GitHub Actions workflows shared across Aave repositories.</td>
  </tr>
  <tr><td colspan="2"><h3>Misc resources & documentation</h3></td></tr>
  <tr>
    <td><a href="https://github.com/aave-dao/aave-brand-kit">aave-brand-kit</a></td>
    <td>Official Aave brand assets and visual identity guidelines.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/aave-dao/bored-guides">bored-guides</a></td>
    <td>Operational guides for repeatable Aave ecosystem workflows.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/aave-dao/aave-robots-list">aave-robots-list</a></td>
    <td>List of all automation robots used by the Aave protocol.</td>
  </tr>
  <tr>
    <td><a href="https://github.com/aave-dao/aave-robots-cre">aave-robots-cre</a></td>
    <td>Onchain contracts and offchain Chainlink Runtime Environment (CRE) workflows for Aave DAO automations.</td>
  </tr>
</tbody>
</table>
