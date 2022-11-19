# ruby

<!---
Note: Do NOT edit directly, this file was generated using https://github.com/chainguard-images/readme-generator
-->

[![CI status](https://github.com/chainguard-images/ruby/actions/workflows/release.yaml/badge.svg)](https://github.com/chainguard-images/ruby/actions/workflows/release.yaml)

WORK IN PROGRESS

## Get It!

The image is available on `cgr.dev`:

```
docker pull cgr.dev/chainguard/ruby:latest
```

## Supported tags

| Tag | Digest | Arch |
| --- | ------ | ---- |
| `migration-31` `migration-31-20221118` `migration-31-3` `migration-31-3.1` `migration-31-3.1.2` `migration-31-3.1.2-r0` | `sha256:59610dd6a14c91d8c00324076502410e1f72ac60ca85745b3de88f9181010cfd`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:59610dd6a14c91d8c00324076502410e1f72ac60ca85745b3de88f9181010cfd) | `amd64` |
| `migration-30` `migration-30-20221118` `migration-30-3` `migration-30-3.0` `migration-30-3.0.4` `migration-30-3.0.4-r0` | `sha256:1e49a8a1943dfc3af0533806b5f2eb7a8ee849a60f9b0f51ef2a58db5762b239`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:1e49a8a1943dfc3af0533806b5f2eb7a8ee849a60f9b0f51ef2a58db5762b239) | `amd64` |


## Usage

WORK IN PROGRESS


## Signing

All Chainguard Images are signed using [Sigstore](https://sigstore.dev)!

<details>
<br/>
To verify the image, download <a href="https://github.com/sigstore/cosign">cosign</a> and run:

```
COSIGN_EXPERIMENTAL=1 cosign verify cgr.dev/chainguard/ruby:latest | jq
```

Output:
```
Error: GET https://cgr.dev/v2/chainguard/ruby/manifests/latest: MANIFEST_UNKNOWN: manifest unknown
main.go:62: error during command execution: GET https://cgr.dev/v2/chainguard/ruby/manifests/latest: MANIFEST_UNKNOWN: manifest unknown
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

