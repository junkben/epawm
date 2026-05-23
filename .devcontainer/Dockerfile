FROM ghcr.io/astral-sh/uv:python3.14-trixie-slim

ENV \
    # silence cross-fs warnings
    UV_LINK_MODE=copy \
    # precompile .pyc files
    UV_COMPILE_BYTECODE=1 \
    # virtual env path
    UV_PROJECT_ENVIRONMENT=/workspaces/.venv

WORKDIR /workspaces