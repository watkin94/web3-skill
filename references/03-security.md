# Security

## Golden Rules

- Treat seed phrases and private keys as irreversible master secrets.
- Treat signatures, approvals, and contract interactions as potentially dangerous.
- Verify the domain, the contract, and the requested action before confirming.
- Use separation:
  - one wallet for experimentation
  - one wallet for larger holdings
  - hardware wallet for meaningful funds

## Common Threats

### Phishing

Fake websites, fake support staff, fake browser extensions, fake airdrops, and fake social media replies.

### Blind Signing

Signing unreadable payloads can authorize harmful actions even without sending a visible transaction.

### Unlimited Approval

Granting a contract unlimited spending rights can become dangerous if the contract or frontend is compromised.

### Address Poisoning

Attackers send tiny transactions from lookalike addresses so the victim copies the wrong address later.

### Fake Tokens And Fake Bridges

Attackers imitate real brands, tokens, and bridges. A familiar logo is not proof.

## Safety Checklist Before Any Action

1. Is the URL the official domain?
2. Did the link come from a trusted official source?
3. Is the wallet on the expected network?
4. Do you understand what the signature or approval is asking for?
5. Is the contract address confirmed by official docs?
6. Are you using the smallest amount needed for a first try?

## Response Pattern For Suspicious Requests

When a user pastes a link, signature, or approval prompt:

1. State the risk plainly.
2. Explain what the request appears to do.
3. Tell the user how to verify it safely.
4. Recommend declining if key facts are missing.

## Red Flags

- urgency or countdown timers
- "connect wallet to claim"
- "support" staff asking for screenshare or seed phrase
- requests to disable wallet security warnings
- approvals that do not match the stated action
- messages telling the user to import a wallet into a website

## Good Beginner Habits

- bookmark official domains
- revoke unused approvals periodically
- keep the seed phrase offline
- use different wallets for different risk levels
- test with tiny amounts first
