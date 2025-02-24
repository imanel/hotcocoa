# hotcocoa

* [http://github.com/ferrous26/hotcocoa](http://github.com/ferrous26/hotcocoa)
* [Documentation](http://rdoc.info/github/ferrous26/hotcocoa/master/frames)

## Description

HotCocoa is a thin, idiomatic Ruby layer that sits above Cocoa and
other frameworks. The goal of the project is to simplify the process of creating
and configuring Cocoa objects used when building native Mac apps. To get more
information on HotCocoa (including tutorials) see
[http://macruby.org](http://macruby.org).

## Note

HotCocoa has ambitious goals that are difficult to accomplish with the input of
only a few people. Feedback is the easiest way to contribute and goes a long way
to making sure HotCocoa is on the right path to accomplishing those goals.

There are still some APIs that need documentation, regression tests that need to
be written, and tutorials to be updated; but new features and improved performance
will also be coming in the not too distant future. If you find issues with
HotCocoa, don't hesitate to open tickets on Github (or try to fix it yourself and
send in the patch :)).

There are a list of
[gotchas](https://github.com/ferrous26/hotcocoa/wiki/Gotchas) in the
wiki.

## Install

From rubygems:

    sudo macgem install hotcocoa

Or you can clone the repository on Github and install from there:

    git clone git://github.com/ferrous26/hotcocoa
    cd hotcocoa
    sudo macrake install

__Note__: If you are on Snow Leopard, you will also need the
[Bridge Support Preview](http://www.macruby.org/files/BridgeSupport%20Preview%203.zip)
in order to run HotCocoa. Read about it on the
[MacRuby Blog](http://www.macruby.org/blog/2010/10/08/bridgesupport-preview.html).

__Note 2__: You will also need the Mac OS X developer tools in order
to build apps. Xcode is not required, but the compiler toolchain is
needed.

## Documentation

Documentation is a work in progress; some of the documentation is
being ported from the MacRuby website and you can still view it there.

The documentation currently does not include the mappings right now due to the
way that mappings are implemented; a YARD plug-in will be needed for thatv

## Contributing to HotCocoa

* Check out the latest master to make sure the feature hasn't been implemented or the bug hasn't been fixed yet
* Check out the issue tracker to make sure someone already hasn't requested it and/or contributed it
* Fork the project
* Start a feature/bugfix branch
* Commit and push until you are happy with your contribution
* Make sure to add tests for it. This is important so I don't break it in a future version unintentionally.
* Please try not to mess with the Rakefile, version, or history. If you want to have your own version, or is otherwise necessary, that is fine, but please isolate to its own commit so I can cherry-pick around it.
* No contribution is too small!

## License

(The MIT License)

Copyright (c) 2009-2010 Richard Kilmer
Copyright (c) 2011 Mark Rada

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
