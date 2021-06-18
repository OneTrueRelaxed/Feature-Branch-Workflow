<h1>Feature-Branch-Workflow</h1>
This repository is an example of Feature Branch Workflow model. In its simplest form, a repository could have a master branch with stable, 
readily available code and other branches for various features (or bugs, or enhancements) that could be integrated into the master branch. 
That is, the repository will have a secondary main branch (dev) that will store the stable code under test to be sent to users when it is merged from master. 
In this case, the feature branch will be merged into dev, not master.

<h2>When to use</h2>
This approach is more suitable for teams that use some kind of project management method (for example, Agile). Let's say that your project is under 
continuous development and you need to add a set of features before the next release. These features are assigned to different developers, who create
a separate branch for each published feature before it is merged into dev for testing. When you're ready to release, dev merges into master.
