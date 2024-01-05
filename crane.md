# Crane

% docker

## Copie une image d'une registry source vers une autre

```
crane copy <image_source> <image_destination>
```

## Récupère le manifest d'une image

```
crane manifest <image|ubuntu> | jq
```