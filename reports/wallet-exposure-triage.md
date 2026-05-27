# Wallet Exposure Triage Note

This note describes a defensive triage structure for suspected wallet compromise.

## Immediate Questions

- Which wallets and chains are affected?
- Is the risk a leaked seed phrase, a malicious approval, a compromised device, or an exchange/account issue?
- Are assets still present, already moved, or partially at risk?
- Are there active approvals that can be revoked safely?

## Evidence To Preserve

- Wallet addresses
- Transaction hashes
- Token contract addresses
- Approval records
- Timestamps and explorer links
- Screenshots of warnings or phishing pages, with sensitive data removed

## Defensive Actions

- Stop using the suspected device for signing.
- Move unaffected assets only from a clean environment.
- Revoke risky approvals where doing so is safe and still relevant.
- Avoid sharing seed phrases, private keys, or wallet backup files with any third party.

## Public Reporting Boundary

Public reports should explain the risk pattern and evidence trail without publishing sensitive victim data or operational details that enable abuse.
