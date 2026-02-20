# [Choice] Go version (use -bullseye variants on local arm64/Apple Silicon): go:1.21, go:1.21-bullseye, go:1.21-bookworm
ARG VARIANT=1.21-bookworm
FROM mcr.microsoft.com/devcontainers/go:${VARIANT}

# [Optional] Uncomment this section to install additional OS packages.
# RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
#     && apt-get -y install --no-install-recommends <your-package-list-here>

# [Optional] Uncomment the next line to install go tooling
# RUN go install ...

# [Optional] Uncomment the next line if you want to customize the location for the default user or the working directory.
# WORKDIR /workspaces/${templateWorkspaceFolder}

# [Optional] Uncomment the next line to install the Go language server
# RUN go install golang.org/x/tools/gopls@latest

# [Optional] Uncomment the next line to install the GitHub CLI
# RUN go install github.com/cli/cli@latest
