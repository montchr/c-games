# c-games

a collection of configuration files by way of a carefully-tuned tracking of
`C:\Games\`, where most of my games are installed.

obviously, we want to ignore the vast majority of this file tree since it
includes Steam files, game files, backups, downloaded mods, and other things
that should never be redistributed.

as you might have guessed, most of the important stuff happens in `/.gitignore`.

i have tried to track only configuration files -- JSON, TOML, INI, etc. -- but the
patterns are bound to be leaky. consult the gitignore file.

so, consider this your first and only warning: if you want to try this approach,
you risk accidentally doing some things that can easily result in legal issues.
don't redistribute unfree software! or do, but leave me out of it and consult
the `LICENSE` file included in this repo.

tread carefully!

## Motivation

i like to keep my mods up to date. but i also don't want to lose my changes to
files that get overwritten by changes to upstream mod options. my standards for
software quality are lowered dramatically when dealing with mods, so i want to
keep my preferences safe so i don't face later discouragement.

git seemed like the ideal method for acheiving my goal, because managing
upstream changes is one of git's primary purposes.

## Oversights

### ReShade Presets

I honestly have no idea about the legal status of ReShade presets downloaded
from Nexus Mods. They are just saved parameters in a text file, and most of them
are incredibly similar at this point in time. If you are an author of one of the
presets here, please ask and I will remove your preset from this repo.
