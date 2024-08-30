# Sports Analytics

## Project Purpose

The purpose of this project is to submit a proposal for the research assessment task as declared in the [index.md](./Application_PhD_Sports_Analytics/src/index.md). The project aims to harness AI agents to automate data analysis and reporting for performance analysis in soccer using open-source large language models.

## Project Files

The project is organized into several key files, each serving a specific purpose in the overall structure. Below is a detailed explanation of each file along with links to access them:

### [Research Proposal](./Application_PhD_Sports_Analytics/src/01_research_proposal.md)

This file contains the project proposal, outlining the motivation behind the project, the goals, and the methodologies to be employed. It provides a comprehensive overview of the project's objectives and the rationale for undertaking it.

### [Research Impact](./Application_PhD_Sports_Analytics/src/02_research_impact.md)

This file discusses the potential impact of the research and project completion. It highlights the benefits of the project, including data-driven decision-making, resource optimization, accessibility, and innovation in sports analytics. It also outlines the dataset, technology stack, research challenges, and skill development challenges.

### [Research Proposal Papers](./Application_PhD_Sports_Analytics/src/research_proposal_papers.bib)

This file is a bibliography containing references to the research papers cited in the project.

## Setting Up the Development Environment

```bash
# Step 1 -> installs nvm (Node Version Manager)
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.0/install.sh | bash

# Step 2 
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"

# Step 3 -> download and install Node.js (you may need to restart the terminal)
nvm install 20

# Step 4
# verifies the right Node.js version is in the environment
node -v # should print `v20.17.0`

# verifies the right npm version is in the environment
npm -v # should print `10.8.2`

# Reference -> https://nodejs.org/en/download/package-manager
```

```bash
# change directory
cd ./Application_PhD_Sports_Analytics/

# Observable Framework’s local development server 
npm run dev
```
