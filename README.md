# MatchTags

This plugin highlights the matching HTML tag when the cursor is
positioned on a tag. It works in much the same way as the MatchParen
plugin. This is a fork of <https://github.com/gregsexton/MatchTag>.

## Installation

If you have Vim 8 or NeoVim, clone the MatchTag plugin repository into
the appropriate directory:

```bash
$ cd ~/<plugin directory>
$ git clone https://github.com/matchtags/MatchTags.git
```

## Other file types

To get this to work for file types other than html that use a similar
tag structure (e.g XML) you can do something similar to this.

    echo 'runtime! ftplugin/html.vim' > ~/.vim/ftplugin/xml.vim

The xml.vim file demonstrated here is included with MatchTag.

## Screenshot

Thanks to [ithaca.arpinum.org](http://ithaca.arpinum.org/) for this screenshot.

![Screenshot of MatchTag](http://www.gregsexton.org/images/matchtag/matchtag.jpg)


## License

[MatchTags][] is released under the MIT license. Please see the
[LICENSE.txt][] file for more information.

[LICENSE.txt]: https://github.com/matchtags/MatchTags/blob/master/LICENSE.txt
[MatchTags]: https://github.com/matchtags/MatchTags


