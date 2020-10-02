
## The files in this project were taken from [Source Forge](http://htmlcxx.sourceforge.net/) and modified:

- A proper header with license information is provided for all files (LGLP and two Apache).
- The LGLP and Apache licenses are included.
- Tree.h was given an updated license its author, making it LGLP when used with this project.
- strstream code was modified to use the new stringstream class, removing deprecated warnings.
- Several warnings related to 64-32 bit conversions were fixed.
- The Perl script was modified to use unsigned ints, and the list of domains had the BR specific URLs pruned.

The code here is designed to be incorporated directly in your Mac or iOS project and not as a library.

## Three targets are provided for testing:

- htmlcxx, which runs the bit of test code shown on the sourceforge page .
- Tests, provided by the original authors.
- uriTests, also provided by the original authors.
- Added a method to compute the length of the content, which may be 0.
- Added a content method to the Node class returning the content between opening and closing tags, which may be an empty string.
- The css methods were ported over (and it took so fiddling) but while they build clean there are not test cases (ost people probably don't need them)
- To update the css source files, download the htmlcxx project from sourceforge and build the library.
