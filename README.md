# INSTALLATION

Using Vundle:

    # add this line to .vimrc
    Plugin "osfameron/perl-tags-vim"

    # then run :PluginInstall

Manual VIM configuration

    If you haven't yet switched to a Modern VIM package manager, you can of
    course copy the code from `ftplugin/perl.vim` into your Vim configuration
    as appropriate!

# USAGE

    * open a Perl file
    * use Tags as normal: `<C-]>`, `<C-t>`, `g]`  etc.
    * :call PT_show_tags()  # view the generated tags file

# NOTE

    This plugin is under development.  Comments from more experienced
    Vim hackers are welcome, as are bug reports and pull requests.

    The fatpacked dependencies have been generated and tested on Perl 5.14.2
    (which is the default on the popular Debian Wheezy (stable) and Ubuntu
    Precise64 Linux distributions.)  Does it work on other platforms?  Please
    let me know!

# TODO

    * consider using a tagger per file-path?
    * allow user to use non-fatpacked Perl::Tags or other customizations
    * more documentation
    * tests
