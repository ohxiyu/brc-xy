# BRC-XY Standard

Welcome to the repository for the BRC-XY Standard. This standard establishes a protocol for inscribing and summarizing NFT collections in ordinals.

## Overview

The BRC-XY Standard provides a uniform and consistent set of guidelines for creating, inscribing, and summarizing Non-Fungible Tokens (NFTs) collections. It is designed to increase transparency, interoperability, and efficiency in the NFT space.

## Example of Standard in JSON format

Here is an example of what the BRC-XY standard might look like in JSON format:

```json
{
  "p": "BRC-XY", // Required
  "op": "Collection Summary", // Required
  "name": "Project Name", // Required
  "supply": 1000, // Required
  "inscription": ["Inscription1", "Inscription2", "..."], // Required
  "rare_inscription": ["RareInscription1", "RareInscription2", "..."], // Optional
  "inscription_range": "100000-200000", // Optional
  "website": "https://www.projectname.com", // Optional
  "twitter": "@projectname" // Optional
}
```

In this JSON example:
- `p`: The protocol name, which is BRC-XY in this case. (Required)
- `op`: The operation, which is the Collection Summary. (Required)
- `name`: The name of the project. (Required)
- `supply`: The total supply of the project. (Required)
- `inscription`: An array of inscriptions related to the project. (Required)
- `rare_inscription`: An array of rare inscriptions related to the project. (Optional)
- `inscription_range`: The inscription range within the project. (Optional)
- `website`: The official website of the project. (Optional)
- `twitter`: The official Twitter handle of the project. (Optional)

## Usage

The BRC-XY Standard should be adhered to in all NFT creation and inscription processes within our organization. Compliance with this standard ensures the quality and consistency of our NFT collections.

For further information or any questions regarding the BRC-XY Standard, please don't hesitate to contact us.

