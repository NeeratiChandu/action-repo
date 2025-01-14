# Action Repository

This repository is designed to trigger GitHub webhooks on specific actions (Push, Pull Request, Merge) and send the event data to a specified webhook endpoint.

## Features

- Sends webhook events for:
  - Push actions
  - Pull request submissions
  - Merges

## Setup Instructions

1. **Create a New Repository**:
   - Create a new GitHub repository named `action-repo`.

2. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/action-repo.git
   cd action-repo
