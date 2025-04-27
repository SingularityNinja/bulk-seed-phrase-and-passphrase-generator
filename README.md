# Bulk Seed Phrase and Passphrase Generator

This is a free, open-source tool for generating multiple **BIP-39 seed phrases** (12 or 24 words) and optional random passphrases (up to 200 characters). It is designed for **cryptocurrency users** creating secure wallet backups and **security enthusiasts** needing offline passphrase generation. For maximum security, use this tool on an **airgapped (permanently offline) machine**. Released under the MIT License. **Use of this tool is entirely at the user’s own risk.**

## Features

- **BIP-39 Seed Phrases**:
  - Generate 12 or 24-word seed phrases with a checksum for integrity (per BIP-39).
  - Uses the standard English BIP-39 wordlist (included in the code).

- **Optional Passphrases**:
  - Generate random passphrases up to 200 characters.
  - Choose between hexadecimal (0–9, a–f) or standard ASCII characters (33–126).

- **User-Friendly Interface**:
  - Toggle between **dark** and **light** modes.
  - Adjust text size with a slider.
  - Copy seed phrases and passphrases to the clipboard.
  - View phrases character-by-character or word-by-word in a modal.

- **Offline Operation**:
  - Runs entirely offline with no external dependencies—ideal for airgapped use.

## Example Output
- **12-Word Seed Phrase**: `apple banana cherry dog elephant fox grape hotel ink joy kite lemon`
- **24-Word Seed Phrase**: `abandon ability able about above absent absorb abstract absurd abuse access accident account accuse achieve acid acoustic acquire across act action actor actress actual`
- **Passphrase (30 chars, hex)**: `a1b2c3d4e5f67890abcdef1234567890`

## Setup and Usage

1. **Download the Tool**:
   - Download or clone this repository to your local machine.

2. **Open the Application**:
   - Open `bulk-seed-phrase-and-passphrase-generator.html` in a modern browser (e.g., Chrome 66+, Firefox 57+, Safari 11+, Edge 79+).
   - No installation or build steps are required—the tool is a single HTML file.

3. **Adjust Settings**:
   - Select **12** or **24 words** for seed phrases.
   - Optionally enable passphrase generation and set the length (max 200 characters).
   - Toggle **Light/Dark** mode and adjust text size as needed.

4. **Generate**:
   - Click the **Generate** button to create a table of 10 seed phrases (and passphrases, if enabled).

5. **Copy or View**:
   - Use **Copy** buttons to copy phrases to the clipboard.
   - Use **View** buttons to inspect phrases in a modal window.

## Requirements
- A modern browser supporting the **Web Cryptography API** and **Clipboard API** (e.g., Chrome 66+, Firefox 57+, Safari 11+, Edge 79+).
- No external dependencies or internet connection required.

## Security Recommendations
- **Use Offline**: Run this tool on an **airgapped (permanently offline)** machine to prevent data exposure.
- **If Online**: Disconnect from the internet and scan for malware before use.
- **Secure Storage**: Store generated phrases on physical media (e.g., paper, metal) in a secure location.
- **Clipboard Caution**: Clear your clipboard after copying sensitive data to avoid leaks.
- Read the [WARNING.md](./WARNING.md) file for detailed security advice.

## License
This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

## Trademark Notice
"Singularity Ninja™" is a trademark. Do not use this trademark in derivative works. If you modify or fork this code, please rename your project.

## Support
This is a free tool provided as-is. For questions or issues, please review the [WARNING.md](./WARNING.md) file or open a GitHub issue. No contributions are accepted at this time.