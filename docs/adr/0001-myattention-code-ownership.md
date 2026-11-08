# ADR 0001: My Attention project code ownership

Status: Accepted by the organization owner on 8 November 2026.

## Context

The current [NDDev license standard](https://github.com/NDDev-Technocracy-Standarts/agent-standards/blob/368f2b63de37fcbe32e4fdd48960ded1ee88c0af/topics/foundations/licenses.md)
uses Danil Silantyev / NDDev as the default holder of original code and prescribes its private
license template. My Attention project repositories already name My Attention AI, Inc. as their
copyright holder. The owner explicitly confirmed retaining the company and recording a scoped
departure in this organization and its projects.

## Decision

For original My Attention project code in this organization, retain My Attention AI, Inc. as
the copyright holder and the existing My Attention proprietary repository license. This is an
approved departure from NDDev's personal-rights-holder and private-license-template defaults.
Project documentation records this decision; package metadata must accurately refer to its
repository's license. Private project packages remain private and unpublished.

The departure concerns the ownership and license of original My Attention project code. Other
NDDev requirements continue to apply. Third-party code, fonts, artwork and other supplied
material retain their applicable rights, licenses and notices. This decision does not assign
their rights to the company or relicense an upstream provider.

The organization profile's presentation artwork retains its existing separate [license](../../LICENSE).
This ADR does not alter the public profile, user agreements, product policies or repository
visibility. Those remain governed by their actual published terms and explicit decisions.

## Consequences

Standards adoption must not substitute personal NDDev ownership for the company's existing
copyright in My Attention code. New My Attention code follows the same company policy.
Dependency and asset reviews still enforce the applicable terms; this exception is not an
exception to dependency licensing or confidentiality. Other NDDev organizations and projects
are outside its scope.
