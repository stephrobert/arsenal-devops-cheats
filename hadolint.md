# Hadolint

Hadolint is a Dockerfile linter that helps you build best practice Docker
images. It is a static analysis tool for Dockerfiles, providing useful feedback
for optimizing and structuring Dockerfile instructions according to best
practices. It can be used in a CI/CD pipeline to ensure Dockerfile quality.

#platform/multiple #target/local #cat/DevOps

% hadolint, docker, dockerfile, linter, best practices

## hadolint - Lint a Dockerfile

```
hadolint <Dockerfile|Dockerfile>
```

## hadolint - Lint Dockerfile from STDIN

```
cat <Dockerfile|Dockerfile> | hadolint -
```

## hadolint - Ignore Specific Rules

```
hadolint --ignore <rule|DL3018> <Dockerfile|Dockerfile>
```

## hadolint - Use a Custom Configuration File

```
hadolint --config <file|file.yaml> <Dockerfile|Dockerfile>
```

## hadolint - Show Trusted Registries

```
hadolint --trusted-registry <registry-url> <Dockerfile|Dockerfile>
```

## hadolint - Output in JSON Format

```
hadolint --format json <Dockerfile|Dockerfile>
```

## hadolint - Output in TTY Format

```
hadolint --format tty <Dockerfile|Dockerfile>
```
