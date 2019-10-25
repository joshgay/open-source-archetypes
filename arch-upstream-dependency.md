Upstream Dependency {#archetype:upstream-dependency}
-------------------

**Examples:** *OpenSSL, WebKit, and just about every small JavaScript
library on GitHub*

**Characteristics:** Intended as a building block for other software, so
the user base is made up of developers, and adoption means third-party
integration of your software into their products. When small, this
archetype often overlaps with Single-Maintainer Houseplant[^1].

For smaller or more specialized libraries, this is a bit like Wide Open,
but the experience for maintainers and contributors is qualitatively
different. When a significant portion of the user base is able to
participate technically, a lot of attention and investment may be needed
from each serious participant just to take part in discussions, even
when the number of parties in a discussion is small. Relative to Wide
Open, there are fewer one-off or lightweight contributors and more
ongoing, engaged contributors.

The degree of the software's specialization does not necessarily dictate
how much investment it receives. Upstream Dependency projects attract
technical investment based on two factors: their replaceability (it's
easier to duplicate or find an alternative for a six-line JavaScript
library than it is to do so for, say, all of OpenSSL), and which
downstream projects depend on them.

Therefore understanding who is using the project, and how, is key to
knowing what goals the project can serve for Mozilla. An Upstream
Dependency project can be quite influential thanks to its role in
downstream dependees, even if only a small minority of developers in
those dependees are familiar with it.

-   **Licensing**: Typically non-copyleft.

-   **Community standards**: Welcoming, and specifically amenable to
    one-time contributions.

-   **Component coupling**: Standalone, decoupled from one another and
    the downstream projects that pull them in.

-   **Main benefits**: Connections to many downstream dependee projects
    offers insight into market and usage trends, and can provide
    openings to potential partners.

-   **Typical governance**: Informal, maintainer-led, committer groups.

[^1]: 
