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

## Generations cleaning
```
nix-env --delete-generations 30d
```

## EFI loaders removal
```
nix-collect-garbage --delete-old
nixos-rebuild boot
nixos-rebuild switch
```
