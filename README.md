# encode-club-weekend-project-4

token based lottery dApp

- Angular front-end dApp repo: https://github.com/numoonchld/encode-club-weekend-project-5-web-dapp-client
- Hardhat based smart-contract repo: https://github.com/numoonchld/encode-club-weekend-project-5-lottery-contract-workbench

**note**: this repo has git sub-modules

## cloning this repo

### 3-step method

```bash
git clone <repo-url>

git submodule init

git submodule update
```

### 2-step method

```bash
git clone <repo-url>

git submodule update --init --recursive
```

### 1-step method

```bash
git clone --recurse-submodules <repo-url>
```

## list all submodules attached to this repo

```bash
git submodule
```

### update submodule to latest commits on remote

```bash
git submodule update --remote <sub-module-name>
```

- after running above command, commit this parent repo and push it to remote
- if the above throws an error, run the following

```bash
git pull --recurse-submodules
```
