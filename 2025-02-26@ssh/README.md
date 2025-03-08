# Go meetup at SSH Communications Security

## When

Wednesday, February 26th 2025

## Location

[SSH Communications Security](https://www.ssh.com/)

Karvaamokuja 2D

## Talks

### Golang and Cryptographic certification requirements

Speaker: **Tero Mononen** ([LinkedIn](https://www.linkedin.com/in/mononen/))

Tero walked through cryptography at a high level, talked about requirements for
certification such as FIPS-140 and covered what this means both as a consumer
of cryptographic libraries and as an author. He also covered the the upcoming
requirements defined by the Cyber Resilience Act (CRA).

- [Cyber Resilience Act](https://digital-strategy.ec.europa.eu/en/policies/cyber-resilience-act)

### What's new in Go 1.24

Speaker: **Antti Kupila** ([LinkedIn](https://www.linkedin.com/in/anttikupila/), [GitHub](https://github.com/akupila), [Website](https://anttikupila.com))

Antti briefly touched on how changes to Go happen through the proposal process
and mentioned gotip, which can be used to try bleeding edge versions of Go. He
then talked about 10 things that are new in Go. The audience participation
added to the discussion, covering additional things such as the swiss table
implementation for maps.

- [Slides](./go-1.24.pdf)
- [Proposal review meeting minutes](https://github.com/golang/go/issues/33502)
- [gotip](https://pkg.go.dev/golang.org/dl/gotip)
- [Go 1.24 release notes](https://go.dev/doc/go1.24)

### Scaling LiveOps with Go: Building Cloud Native Game Servers

Berkay covered the journey of writing a multiplayer game backend in Go. This
started with a comparison to other languages and why Go is a good choice for
this. He then talked about some benefits and lessons learned during the
journey. He also talked about a project he built called k8schedul8r which
scales Kubernetes workloads based on a pre-defined schedule. The audience was
very active to participate in discussion and Berkay was happy to answer any questions.

Speaker: **Berkay Uçkaç** ([LinkedIn](https://www.linkedin.com/in/berkay-uckac/), [GitHub](https://github.com/berkayuckac))

- [Slides](./scaling-liveops-with-go.pdf)
- [k8schedul8r](https://github.com/berkayuckac/k8schedul8r)
