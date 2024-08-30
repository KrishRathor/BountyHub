# GitHub Bounty Dispenser

Welcome to the GitHub Bounty Dispenser! This project allows you to manage and distribute bounties on GitHub issues, leveraging Solana for payments. It integrates with GitHub’s API to create and manage bounties and uses Solana wallets for secure transactions.

## Features

- **Create and Manage Bounties**: Easily create bounties for GitHub issues and track their status.
- **Solana Wallet Integration**: Users can connect their Solana wallet to approve and process payments.
- **GitHub Integration**: Automatically handle GitHub pull requests and issue comments.
- **Webhook Support**: Set up webhooks to trigger actions based on GitHub events.

## Technologies

- **GitHub API**: For interacting with GitHub issues and pull requests.
- **Solana**: For processing payments.
- **Octokit.js**: For GitHub API interactions.
- **NextJs**: For the frontend.
- **Tailwind CSS**: For styling.
- **TRPC**: For backend
- **Nginx**: For serving the application and handling HTTPS.
- **Certbot**: For SSL/TLS certificate management.

## Getting Started

To get started with the GitHub Bounty Dispenser, follow these steps:

### Prerequisites

- Node.js
- Yarn or npm
- Solana CLI (for wallet operations)
- GitHub personal access token

### Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/github-bounty-dispenser.git
   cd github-bounty-dispenser
