guiders-gwt
===========

GWT version of https://github.com/jeff-optimizely/Guiders-JS

Requirements
=

The same requirements apply as for Guiders-JS itself (jQuery), in addition to the jars required to compile the GWT code.

That is:
<pre>
war/WEB-INF/lib/gwt-user.jar
war/WEB-INF/lib/gwt-dev.jar
</pre>

Building
=

To build `guidersgwt.jar`, it needs `gwt-dev.jar` and `gwt-user.jar` in `war/WEB-INF/lib`. After that, a simple `ant` builds the jar.

At the time of writing, it was built with GWT 2.5.1.
