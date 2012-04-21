Del/Ins Extension for Python-Markdown
=====================================

Wraps the inline content with `ins` and `del` tags.


Installation
------------

    pip install git+git://github.com/aleray/mdx_del_ins.git


Usage
-----

    >>> import markdown
    >>> src = """This is ++added content++ and this is ~~deleted content~~""" 
    >>> html = markdown.markdown(src, ['del_ins'])
    >>> print(html)
    <p>This is <ins>added content</ins> and this is <del>deleted content</del>
    </p>


Dependencies
------------

* [Markdown 2.0+](http://www.freewisdom.org/projects/python-markdown/)


Copyright
---------

2011, 2012 [The active archives contributors](http://activearchives.org/)
All rights reserved.

This software is released under the modified BSD License. 
See LICENSE.md for details.
