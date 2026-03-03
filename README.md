# 🛡️ ScammerLedger

ScammerLedger is a **constantly updated public list of confirmed Discord scam reports**.  
It is made to help communities, developers, and researchers improve safety and awareness.

This repository is **read-only** and exists only to share the data.

---

## Why This Exists

Online scams cause real harm.  
ScammerLedger exists to make confirmed scam reports easier to find, review, and reference in one place.

The goal is **transparency and safety**, not punishment.

---# 🛡️ ScammerLedger

![Status](https://img.shields.io/badge/status-auto--updated-green)
![Data](https://img.shields.io/badge/data-public-blue)
![Purpose](https://img.shields.io/badge/purpose-community--safety-orange)
![License](https://img.shields.io/badge/license-CC%20BY--ND%204.0-lightgrey)

ScammerLedger is a **public dataset of confirmed Discord scammer reports**.

It helps:
- Communities
- Moderators
- Safety tools
- Developers
- Researchers

This repository shares scammer IDs so tools can improve safety.

The repository is **automatically updated**.

---

# Why This Project Exists

Discord scams affect many users.

ScammerLedger makes it easier to:
- Find confirmed scammer IDs
- Build safety tools
- Improve moderation
- Increase transparency

This project focuses on **awareness and safety**, not punishment.

---

# Where the Data Comes From

The data comes from **trusted Discord servers that track scammers**.

These servers:
- Have experienced moderators
- Review reports carefully
- Verify scams before adding them

Only **confirmed scam reports** are included.

If a report is removed from the source servers, it will also be removed here.

---

# How the System Works

A sync bot automatically updates this repository.

When the system starts or restarts:

1. It reads all files in the `lists/` folder
2. It checks the Discord report channels
3. It compares the IDs
4. Missing IDs are added
5. Removed reports are updated
6. Changes are pushed to GitHub

This keeps the dataset accurate.

The bot runs every few minutes to check for changes.

---

# Repository Structure


lists/
server-1.json
server-2.json


Each file:
- Represents a Discord report channel
- Contains a list of scammer IDs
- Updates automatically

Example:


[
"123456789012345678",
"987654321098765432"
]


---

# Developer Documentation

## Using the Dataset

Developers can use this dataset for:

- Discord bots
- Moderation systems
- Scam detection tools
- Research projects
- Trust & safety systems

---

## How to Read the Data

Each file contains:

- A JSON array
- Discord user IDs
- Confirmed scam reports

Example logic:


if user_id in scammer_list:
flag_user()


You can download the repository or access it directly from GitHub.

---

## Example Bot Integration

Basic example:


fetch scammer list
store in memory
check user join events
warn moderators if user is listed


Many safety bots use this type of system.

---

## Important Notes for Developers

Please follow these guidelines:

- Do NOT automatically ban users using only this list
- Always check context
- Allow human review
- Use this dataset as a **signal**, not final proof

This helps prevent mistakes.

---

# Automatic Updates

This repository is updated automatically by a sync bot running on a VPS.

Manual edits to the dataset may:
- Be overwritten
- Be reverted

The **source of truth** is the reporting Discord servers.

---

# Transparency

- All updates are public
- Commit history is visible
- Anyone can review changes

This helps keep the dataset trustworthy.

---

# Privacy

This repository does NOT store:
- Messages
- Evidence
- Personal information
- IP addresses

It only stores:
- Discord user IDs

---

# License

This dataset is licensed under:

**Creative Commons Attribution–NoDerivatives 4.0 International (CC BY-ND 4.0)**

You can:
- Use the dataset
- Share the dataset
- Build tools using it

But you **must not modify the dataset itself**.

---

# Disclaimer

ScammerLedger is for **informational purposes only**.

It is not affiliated with Discord.

How this data is used is the responsibility of the user.

## What This Repository Is

- A public list of confirmed scam-related Discord accounts
- A shared reference for safety tools and moderation projects
- A single, always-updating source of information

---

## What This Repository Is Not

- Not a ban list
- Not an enforcement system
- Not an official decision-making authority

---

## Where the Data Comes From

All entries come from a **moderator-controlled Discord reporting server**.

Only confirmed reports are included.  
If a report is corrected or removed at the source, it is also removed from this dataset.

---

## How the Data Is Updated

- The list is updated regularly
- Additions and removals are visible through the repository history

This helps keep the data accurate and up to date.

---

## How It Can Be Used

ScammerLedger can be used by:

- Discord safety bots
- Community moderation tools
- Trust and transparency projects

It should be used as **one signal**, not the only source of truth.

---

## Responsible Use

To avoid mistakes or harm:

- Do not rely on this list alone for actions
- Always review context and evidence
- Allow for review and appeal where possible

Human oversight is strongly recommended.

---

## Privacy

- No private information is stored
- No message content is saved
- Only public Discord usernames and user IDs are listed

---

## Transparency

- All updates are public
- Changes can be reviewed at any time
- The dataset is open and auditable

---

## License

This dataset is licensed under the  
**Creative Commons Attribution–NoDerivatives 4.0 International License (CC BY-ND 4.0)**.

You may use and share the data, including for commercial purposes, as long as it is **not modified**.

---

## Disclaimer

ScammerLedger is provided for informational purposes only.  
It is not affiliated with Discord.

How this data is used is the responsibility of the user.
