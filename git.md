# Package instralation
### Pre-commit hooks:
```bash
pre-commit install --install-hooks
pre-commit install --hook-type commit-msg
```

# Setup
### Define user name and mail for a specific repo
```bash
cd /path/to/git/repo
git config user.name $GIT_USER
git config user.email $GIT_EMAIL
```

### Define user name and mail globally
```bash
git config --global user.name $GIT_USER
git config --global user.email $GIT_EMAIL
```

