Branching rules for this repository:

1. master is only for organisational changes overhauling the structure of the repository. Do not commit mod content to this branch.
2. dev is the main development branch. Branch features and experiments from here, merge features back into here.
3. release is the branch for stable builds approved for usage in multiplayer sessions. Merge dev into this branch when it's been thoroughly tested.
4. feat-<feature_name> stands for a branch with a feature in it. Grow these from dev and merge them back into dev once the feature is implemented and working.
5. exp-<experiment_name> stands for miscellaneous experiments not part of any feature. Grow these from dev or feat-; do not merge these into dev.
