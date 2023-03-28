# Test GitCrypt

## Description

Git-Crypt enables committing files encrypted from the server perspective but not locally

## Links

- [GitCrypt docs](https://github.com/AGWA/git-crypt)
- [Followed tuto](https://dev.to/heroku/how-to-manage-your-secrets-with-git-crypt-56ih)

## Use

```sh
git-crypt init
```

```sh
git-crypt export-key /path/to/public-key # Export the public key
```

> Add files to encrypt to .gitattributes

```sh
git-crypt status # To check what files will be encrypted
```

```sh
git-crypt unlock /path/to/public-key  # To unlock files handled with git-crypt
```
