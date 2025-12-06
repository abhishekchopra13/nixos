# nixos

## Rebuild
```
nixos-rebuild switch
```

## Update OS
```
nix-channel --update
nixos-rebuild switch --upgrade
```

## Garbage collect
```
nix-collect-garbage -d
```

## Geration cleaning
```
nix-env --delete-generations 30d
```
