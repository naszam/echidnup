# echidnup
Install a specific [Echidna](https://github.com/crytic/echidna) Version or revert to a specific commit.

## Installing
```sh
curl https://naszam.github.io/echidnup/install | bash
```

## Using
To install the **latest** commit:
```sh
echidnup
```

To install a specific **tag** (in this case the `v1.7.3` tag):
```sh
echidnup v1.7.3
```

To install a **specific** commit (in this case commit `8180d...d00bf5d`):

```sh
echidnup 8180d332c0e77e2ead4a4c4451688b4d1d00bf5d
```

To install a specific **branch** (in this case the `dev-test-refactoring` branch's latest commit):

```sh
echidnup dev-test-refactoring
```

To install a **fork's main branch** (in this case `naszam/echidna`'s main branch):

```sh
echidnup naszam/echidna
```

To install a **specific commit in a fork** (in this case commit `8180d...d00bf5d` made in `naszam/echidna`):

```sh
echidnup naszam/echidna 8180d332c0e77e2ead4a4c4451688b4d1d00bf5d
```

To install a **specific branch in a fork**  (in this case the `patch-42` branch's latest commit in `naszam/echidna`):

```sh
echidnup naszam/echidna patch-42
```

<p>&nbsp;</p>

*Inspired by [duppgrade](https://github.com/Rari-Capital/duppgrade) :sparkles:*
