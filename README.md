Branching/committing/merging guidelines go here.

1. main contains general organizational changes in the repository, such as this file. Don't commit anything to it, it's a pain to fix main.
2. dev contains the general development history of the mod. Branch features and experiments from it, merge features back into it.
3. release contains versions thoroughly tested and approved for live sessions. The only commits here are merges from dev.
4. feat-<featureName> branches are your playground. Branch them out of dev, use them to develop the features you need, merge them back into dev.
5. exp-<experimentName> branches are for your experiments not directly related to any features. Do not merge these into dev.

As a rule of thumb, our workflow from github's point of view should look like this:
1. Define the pool of features we want implemented by the next iteration of MP.
2. Implement and test out separate features in separate branches. Iterate if necessary.
3. Feature freeze, merge feature branches into dev, test them together, iterate if necessary.
4. Merge the stable version into release.
