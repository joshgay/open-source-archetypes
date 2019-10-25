Single-Maintainer Houseplant {#archetype:houseplant}
----------------------------

**Examples:** *All those small packages in npm, Ruby Gems, Python PyPI,
and other package management repositories.*

**Characteristics:** This is a project started by one developer to
fulfill an immediate and small-scale personal or professional need[^1],
and that then stays at that size because that's the appropriate size for
what the project does.

This is probably the most well-known and widely written-about type of
open source project, because it is the quickest "stable evolutionary
state" to reach in open source. Vast numbers of houseplant projects are
started, since they're so easy for one person to start --- you don't
have to coordinate with anyone else. Even though only a small percentage
of them gain much adoption, that percentage still accounts for a large
proportion of distinct open source projects total. Many such projects
stay under the single founder's stewardship for a long time, because
there's no technical need for the project to grow significantly in
complexity or capabilities.

A Single-Maintainer Houseplant is most likely to transition to another
archetype when it succeeds in gaining widespread adoption. Even if its
niche is well-defined enough that adoption does not necessarily imply
feature growth, the increased rate of incoming bug reports and related
inquiries may still overwhelm the maintainer.[^2] This is because the
rate at which a piece of software receives bug reports is mostly
proportional to the size of its user base, not to the size and
complexity of the software nor even to number of actual bugs in the
code.

To the extent that a Single-Maintainer Houseplant project has a
community, it is usually a loose community that forms a "star
topology"[^3] with the single maintainer as hub. Most communication is
between a given contributor and the maintainer --- albeit still visible
to all --- with relatively fewer inter-contributor discussions than
happen in other archetypes.

This archetype often overlaps with Upstream Dependency[^4], as many
dependencies also happen to be small, single-maintainer packages.

-   **Licensing**: Can be copyleft or non-copyleft (but more often the
    latter when also an Upstream Dependency).

-   **Community standards**: Entirely dependent on the personality of
    the single maintainer. We have seen a wide range of community
    standards in this archetype, from welcoming and responsive to almost
    aggressive non-engagement. Even in when the maintainer is by nature
    welcoming, however, broad adoption of the software can strain a
    single maintainer's time and attention.

-   **Component coupling**: Little to none. It is one component.

-   **Main benefits**: Easy to start; easy make decisions in.

-   **Typical governance**: Benevolent dictatorship by founder.

[^1]: The classic phrase is that such a project starts by
    "\...scratching a developer's personal itch" (). This dermatological
    metaphor has become so well-known by now that it is probably
    hopeless to try to dislodge it, but we can at least tuck it away
    discreetly in a footnote.

[^2]: The burden experienced by unfunded or underfunded individual
    maintainers of widely-used open source code is one of the threads
    running through Nadia Eghbal's influential 2016 report *Roads and
    Bridges: The Unseen Labor Behind Our Digital Infrastructure* () and
    the followup discussion it spurred. The report's topic is broader
    than just single-maintainer projects, however.

[^3]: 

[^4]: 
