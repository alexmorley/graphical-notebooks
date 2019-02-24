# Graphical Notebooks
**Computational notebooks that reflect the mental model of humans**
A core tenet of user-centered design is that user interfaces should, as much as possible, reflect the prior mental model that the user has of a process. Just as syscall API hides hardware-specific details from programmers developing applications, abstractions at each level of a user interface offer an opportunity to reduce the mental load on the user, enabling them to perform more complex tasks and make fewer mistakes. However these abstractions, however well implemented, will often have tradeoffs in terms of the complexity or performance of the application.

Computational notebooks, such as Jupyter and Wolfram, have had broad success by reflecting in their interface an existing user model i.e. “this code produces this visualisation” by allowing multimedia to be embedded as part of a script. Jupyter has arguably had more success not only because it is free software, but also by piggybacking on existing programming languages which allows users to transfer previously applied models into a new context, rather than having to learn something new. Both types of computational notebooks also reflect the modularity inherent in analysis pipelines, reading in some files might take more than one line of code but most of the time we just want to think about the process as “reading in the files”. In programming language design this is solved using functions, modules and namespaces, in computational notebooks it is reflected in the UI in the form of code cells.

Through personal experience, and observations of wider usage patterns of Jupyter notebooks we have gleaned that there is still room for moving even closer to the user's mental model of how code should be organised for data analysis. We propose design a new user interface that capitalizes on what Jupyter already does well, and fills in the gaps where they exist. In our first prototype we aim to support:
- Branching Paths: reflecting the generally non-linear flow of exploratory analysis and testing
- Hierarchical Modularity: Allow collapsing and grouping of cells for organisation. Indeed, whole notebooks can be included as one unit of computation in another notebook using this framework.
- Modularity II: Allow naming and documenting to be explicitly linked to code cells. Allow decoration of code cells for easy recognition while they are collapsed.
- Horizontal (left to right * ) progression model: Take advantage of modern widescreen hardware, and the natural reading pattern to specify workflows that flow across the screen, with branches being represented by vertical splits. * or right to left depending on locale

Many of the concepts here are well validated in current / past software, the next section discusses some of this prior art as well as the goals underlying other work on the Jupyter UI.

## Prior Art
### Visual Programming
[Wiki page](https://en.wikipedia.org/wiki/Visual_programming_language)


#### Examples:
[Max](https://en.wikipedia.org/wiki/Max_(software))

[KNIME](https://en.wikipedia.org/wiki/KNIME)

[LabView](https://en.wikipedia.org/wiki/LabVIEW)

[WebML](https://en.wikipedia.org/wiki/WebML)

[Orange](https://en.wikipedia.org/wiki/Orange_(software))

[Alteryx](https://pages.alteryx.com/Alteryx-Overview-Demo-ty.html?aliId=230367714)

[Open Source Alteryx Alternatives](https://www.reddit.com/r/Alteryx/comments/5tvp5i/opensource_alteryx_alternative/)


### Other directions for improving notebook interfaces


### Misc Notes
[Graph Rewriting](https://en.wikipedia.org/wiki/Graph_rewriting)

[On Weaponised Design](https://ourdataourselves.tacticaltech.org/posts/30-on-weaponised-design/)


