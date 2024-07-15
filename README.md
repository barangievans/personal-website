# personal-website
Getting Started and a Recommended Workflow
In the previous two lessons, you:

Created local and remote repos for your project and connected them together
Created the base files for your project: README.md, index.html, style.css, and index.js
Published your new site on GitHub Pages.
With all of this in place, you are ready to start working on the content, styles, and behavior you want your site to have. Because your site is published on GitHub Pages, you'll be able to continuously push updates to your site as you build it.

In general, when it comes to building code-related projects, it is often best to establish a routine of making small improvements, checking to make sure those improvements work and don't break things. This routine might look something like the following:

1) Write some HTML, CSS or JavaScript 2) Go to your browser and refresh the page to see the changes 3) Adjust your code and repeat until you're satisfied 4) Move on to the next task and repeat the process

It is very common to get lost in coding and to keep going from one task to the next without checking your work. The problem here is that if you make a mistake it becomes more and more difficult to spot and debug the error.

By frequently checking your work, you'll set your own project milestones — at each one, you can verify everything is working so when you do make a mistake, you'll know it was made recently.

Professional Git Development Workflow
When it comes to Git, there is ultimately no rule that says you must do things a certain way. However, if there was anything we could impart to you regarding good version control habits, it would be this — commit code frequently.

As mentioned, it is a common habit to dive into the code of a project and write as much as you can, for as long as you can. However, not only does this increase the chance for bugs, it will result in very large Git commits or just one big commit for everything.

Repositories with a good commit history can relay a story about their development from just the commit messages alone. For example, instead of the commit history looking like this:

Commit 1: "Initialize Repository"
Commit 2: "Finish website"
A good history might look closer to this:

Commit 1: "Initialize Repository"
Commit 2: "Add basic HTML, CSS and JavaScript files"
Commit 3: "Create initial HTML content"
Commit 4: "Add CSS rules"
Commit 5: "Fix syntax issue in HTML"
Commit 6: "Finish bio/about section"
Commit 7: "Add JS event listeners"
etc...
Commit 22: "Adjust styling for new HTML layout"
Commit 23: "Finish website"
The commit messages here suggest that each commit above addressed a small, often singular task.

Good commit practices are critical for large companies and organizations where many developers are working on large code-bases — in these cases, limiting the size of commits makes it easier for others to understand what changes the commit brings. If a commit introduces a bug into the code base, it is fairly easy to revert a small commit. A big commit, on the other hand, may require lots of extra work to untangle and fix.

For personal development, though, the same concerns apply. In addition, when you start building more complex projects, you may find yourself in situations where you'd like to go back to an earlier version of a project. Taking the time now to build good habits will help you many times over in the future. Think of good version control habits as a favor to your future self!
