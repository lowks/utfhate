utfhate
=======
Doing Bad Things<sup>TM</sup> to UTF-8 byte strings.

e.g.
```
$ python
>>> import utfhate
>>> utfhate
<module 'utfhate' from 'utfhate/__init__.py'>
>>> utfhate.htmlstring('asd \xc2\xa3 qwe \xc2\xa9 qwe \xc2\xa5 xcv \xc2\xbf > \xef\xbb\xbf \xc5\xbb')
'asd &#163; qwe &#169; qwe &#165; xcv &#191; &#62; &#65279; &#379;'
```
