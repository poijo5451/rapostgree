FROM mcr.microsoft.com/vscode/devcontainers/typescript-node:18

# Install PostgreSQL client tools
RUN apt-get update && apt-get install -y postgresql-client

# Install additional tools if needed
RUN apt-get install -y git curl wget

# Clean up
RUN apt-get autoremove -y && apt-get clean -y && rm -rf /var/lib/apt/lists/*