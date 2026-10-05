# interactor-test-ewbik

Test scenes for the EWBIK inverse kinematics solver as a Godot 4 project: simple bone chains, an arm, and full avatars.

## What it is for

Each scene sets the solver up on a known rig, from two- and three-bone chains up to humanoid avatars. The bundled addons import VRM avatars and correct bone directions on import.

## Build and run

Open `project.godot` in a Godot 4 editor built with the EWBIK module and open a scene in `ewbik_samples/scenes/`; a stock editor lacks the solver's node types.

## Licence

MIT; see `LICENSE`. The vendored addons keep their own terms.
