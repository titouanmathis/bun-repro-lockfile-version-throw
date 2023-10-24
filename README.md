# Bun reproduction lockfile version

Steps to reproduce: 

```bash
git clone https://github.com/titouanmathis/bun-repro-lockfile-version-throw.git
cd bun-repro-lockfile-version-throw
bun i
```

The output of the `bun i` command is: 

```
bun install v1.0.6 (969da088)
error: Please upgrade package-lock.json to lockfileVersion 3

Run 'npm i --lockfile-version 3 --frozen-lockfile' to upgrade your lockfile without changing dependencies.
```
