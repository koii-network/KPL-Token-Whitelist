# SPL Token Storage Repository

## Project Overview

This repository is a curated collection of SPL (Solana Program Library) token metadata and icons for various utility tokens on the Solana blockchain. It provides a centralized storage and reference point for token information, including token addresses, decimals, names, symbols, descriptions, and logos.

## Features / Capabilities

- Comprehensive metadata for multiple utility tokens
- High-resolution token icons
- Standardized token information for easy integration
- Supports tokens on Solana Chain (ChainId: 101)

## Tokens Included

The repository currently contains metadata for the following tokens:

1. **REM (Utility Token)**
   - Symbol: REM
   - Address: `Ht53KGDqK6ToC8NraYYUi7zob47wHDXUzaF222W4kCJo`
   - Decimals: 9

2. **OceanFIRE (Utility Token)**
   - Symbol: OFIRE
   - Address: `FJG2aEPtertCXoedgteCCMmgngSZo1Zd715oNBzR7xpR`
   - Decimals: 9

3. **UMARU (Utility Token)**
   - Symbol: UMARU
   - Address: `7DPGC5wCPfV6Kgyd6eFaMK2md2bNiCehAyKJU9LK3yNb`
   - Decimals: 9

4. **KSTORAGE (Koii Storage Token)**
   - Symbol: KST
   - Address: `4HaXFJtwaq4R9ep74EDn6eZQcncudnBybufPu6cCCvmn`
   - Decimals: 9
   - Description: Koii Storage token for Koii Storage SDK

5. **USDC (Stablecoin)**
   - Symbol: USDC
   - Address: `EPjFWdd5AufqSSqeM2qN1xzybapC8G4wEGGkZwyTDt1v`
   - Decimals: 9

6. **USDK (Stablecoin)**
   - Symbol: USDK
   - Address: `DCyu3h5Y98fo1XBB7rJ6ZS3vToqFPNxnJn5NNSZjNDD7`
   - Decimals: 9

## Project Structure

```
spl-token-storage/
│
├── icons/                  # Token logo images
│   ├── FJG2aEPtertCXoedgteCCMmgngSZo1Zd715oNBzR7xpR.png
│   ├── Ht53KGDqK6ToC8NraYYUi7zob47wHDXUzaF222W4kCJo.jpg
│   ├── finnie-koi-logo.png
│   ├── koii-storage.png
│   └── umaru.png
│
├── metadata.json           # Comprehensive token metadata
├── package.json            # Project configuration
└── .prettierrc             # Code formatting configuration
```

## Technologies Used

- Node.js
- Prettier (Code Formatting)
- Husky (Git Hooks)
- JSON (Metadata Format)

## Development

### Setup

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```

### Scripts

- Format metadata: `npm run format`
- Lint metadata: `npm run lint`

## Usage

Developers can use the `metadata.json` file to quickly reference token information for integration into Solana-based applications, wallets, or exchanges.

## Contributing

Contributions to expand the token list or improve metadata are welcome. Please ensure adherence to the existing format and structure.

## License

The project is open-source. Please refer to the LICENSE file for more details.