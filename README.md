# SPL Token Storage Repository

## Project Overview

This repository serves as a centralized storage for SPL (Solana Program Library) token metadata and related assets. It provides a curated collection of token information for various utility tokens on the Solana blockchain, including their metadata, logos, and chain-specific details.

The repository is designed to be a reliable and easily accessible resource for developers, traders, and blockchain enthusiasts who need accurate token information for integration, research, or reference purposes.

## Features / Capabilities

- Comprehensive token metadata for multiple SPL tokens
- High-resolution token logos and icons
- Supports tokens with chainId 101 (Solana Mainnet)
- Metadata includes key token details:
  - Token address
  - Decimal places
  - Token name and symbol
  - Description
  - Logo URI
  - Token tags

## Tokens Currently Supported

The repository includes metadata for the following tokens:
1. REM (Utility Token)
2. OceanFIRE (OFIRE)
3. UMARU
4. KSTORAGE (KST) - Koii Storage SDK Token
5. USDC
6. USDK

## Project Structure

```
spl-token-storage/
│
├── icons/                  # Token logo images
│   ├── Ht53KGDqK6ToC8NraYYUi7zob47wHDXUzaF222W4kCJo.jpg
│   ├── FJG2aEPtertCXoedgteCCMmgngSZo1Zd715oNBzR7xpR.png
│   ├── umaru.png
│   └── koii-storage.png
│
├── metadata.json           # Comprehensive token metadata
├── package.json            # Project configuration
└── .prettierrc             # Code formatting configuration
```

## Technologies Used

- JSON (for metadata storage)
- Prettier (for code formatting)
- Husky (for git hooks and pre-commit checks)

## Development Setup

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```

3. Formatting and Linting:
   - Format metadata: `npm run format`
   - Lint metadata: `npm run lint`

## Contributing

If you want to add or update token metadata:
1. Update the `metadata.json` file
2. Ensure your changes pass the Prettier formatting checks
3. Add corresponding token logos to the `icons/` directory

## License

This project is open-source. Please refer to the LICENSE file for detailed information.

## Disclaimer

Token information is provided as-is. Always verify token details from official sources before making any financial decisions.