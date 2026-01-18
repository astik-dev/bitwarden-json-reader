# ![Bitwarden](https://github.com/astik-dev/bitwarden-json-reader/blob/main/img/favicon/favicon-32x32.png) Bitwarden JSON Reader

![Bitwarden](https://github.com/astik-dev/bitwarden-json-reader/blob/main/img/favicon/favicon-16x16.png) 
**Bitwarden JSON Reader** is a web application that allows users to conveniently view **unencrypted, not password-protected JSON files** from the Bitwarden password manager through a user-friendly interface, providing search and filtering features for easy navigation.  

## Password-protected JSON files
If your JSON file is password-protected, you can decrypt it using my other project, [Bitwarden JSON Decryptor](https://github.com/astik-dev/bitwarden-json-decryptor).

## Usage
1. **Add your JSON file:** Place your JSON file in the `json` folder, replacing the `vault.json` example file.
2. **Run on a local server:** The project must be opened via a local web server (e.g., using VS Code Live Server or any other local web server), because JavaScript cannot fetch JSON files directly from a local folder using the `file://` protocol.

## Supported data types:
- [x] Login
- [ ] Card
- [ ] Identity
- [ ] Note
- [ ] SSH key
