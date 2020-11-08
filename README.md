# PKI

This repo contains my personal PKI data, with `git-crypt` encrypting all of the
key material. This is only public so I can be lazy and download the Root CA
certificate directly from here.

## About

The different CAs are managed with [easypki](https://github.com/google/easypki),
specifically this
[fork/branch](https://github.com/cardil/easypki/tree/feature/go-modules) since
the original project has some Module-based breakage.
