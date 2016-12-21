# git-changelog

Generate changelogs from git tags.


## Usage


    Generate changelogs from git tags
    ---------------------------------

    Uses tags matching a version number to generate a changelog. The changelog
    will be written to stdout. The changelog is sorted by the creation date 
    of the tags.

    The following syntax for version numbers is unterstood:

        - <NUMBER>*
        - v<NUMBER>*
        - V<NUMBER>*

    Usage:

        cd my-git-repository
        git-changelog

    This script may also be used as a git subcommand when it is located on
    the PATH:

        cd my-git-repository
        git changelog


For an example changelog, see [example.changelog.txt](example.changelog.txt).

# Installation

Simply drop the script somewhere on your PATH. The script requires bash, 
git, awk and a few common shell utilities.


# License

See the LICENSE.txt file.
