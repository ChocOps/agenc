<img src="./assets/chocops-agenc-dark.png#gh-dark-mode-only" alt="agenc" width="275" />
<img src="./assets/chocops-agenc-light.png#gh-light-mode-only" alt="agenc" width="275" />

age encrypt multiple files

## Usage

Example agenc.yaml file:

```yaml
agenc:
  # Your identity file
  identity: ${HOME}/.ssh/keys.txt

  # List of recipients
  recipients:
    - age1r0nknwaz0prnq8vh5tlja387cz56evrvjskrtvj0d2ldjetqf9eqscelj0

  # Files to encrypt/decrypt
  files:
    - examples/secret.yaml
```
