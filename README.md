utfhate
=======
Doing Bad Things<sup>TM</sup> to UTF-8 byte strings.

e.g.
```
$ python
>>> import utfhate
>>> utfhate
<module 'utfhate' from 'utfhate/__init__.py'>
>>> utfhate.htmlstring('\xc2\xa3\xc2\xa5\xc2\xbf\xef\xbb\xbf\xc5\xbb')
'&#163;&#165;&#191;&#65279;&#379;'
```
