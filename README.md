# plutus-pioneer-program-nix-script
A script that automatically sets up your nix shell

This script will do the basic setup:
 - get the commit hash from the cabal.project file
 - do the git checkout in the plutus-apps repository
 - enter a nix shell
 - navigate back to plutus-pioneer-program/code/week..

The plutus-apps repository should be in the same directory as the plutus-pioneer-program repository.
You should execute this script in a 'week' directory (e.g. week01).

