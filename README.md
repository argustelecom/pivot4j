About Pivot4J
=======

Pivot4J provides a common API for OLAP servers which can be used to build an analytical service frontend with pivot style GUI.

It aims to leverage mature but now discontinued JPivot project's codebase to make it a general purpose OLAP API library which is independent of any particular GUI implementation.

Motivation
=======

For a long time JPivot has remained as the de facto standard for creating a pivot grid style OLAP frontend application in Java language. However, as the project is no longer actively maintained for now, advance of web technologies has made its JSP-based approach look quite outdated.

Moreover, JPivot was never desiged as a common API for OLAP even it included lot of useful backend implementations for connectiong to and work with XMLA and Mondrian servers.

As many BI developers felt the need for more modern and generic API for OLAP in Java, Olap4J has emerged as a combined effort by various commercial and open source projects to fill this gap.

However, as it is still in very early stage of development, it proved quite challenging to build a working pivot grid GUI component over the current release due to its lacking any substantial implmentation for query transformation or generation API which is essential for operation like drill down, sort, and etc.

Pivot4J project has been started as a fork and major refactoring effort of JPivot to combine the best parts of both libraries. It replaced JPivot's legacy backend implementation with Olap4J while leveraging its mature query transform API. And also Pivot4J has done extensive refactorings to make the codebase more modern and maintainable.

Pivot4J does not contain any concrete GUI implementation for now. However, it's designed as an easy to use model API for creating pivot GUI component using any web technologies like JSP, JSF, GWT, and more.

Project Page
=======

Please visit Pivot4J home page at http://mysticfall.github.com/pivot4j