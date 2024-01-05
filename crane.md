# Crane

% docker

## Copy an image from one source registry to another

```
crane copy <image_source> <image_destination>
```

## Retrieve the manifest of an image.

```
crane manifest <image|ubuntu> | jq
```