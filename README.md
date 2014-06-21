Purpose
-------

I like `sgml-mode`. It has nice features when editing HTML files that
newer modes lack. The problem is that the current release was intended
for different times when HTML 3 (proposed in 1995) was the near
future. Since then work on HTML 3 was abandoned in favor of HTML 3.2
(completed in 1997). And pretty soon web developers adopted HTML4.

Now the times have certainly changed and most web developers are
editing HTML5 documents. And editing an HTML5 document in a mode that
speaks HTML 3 is at times really awkward. `<p>`-tags are left unclosed
while `<meta>`-tags are automatically closed with `</meta>`, the
`class` attribute are rarely proposed, semantic elements don't exist,
and many more.

That is why I'm working on a revision of this mode, so when I'm
finished it will speak HTML5 fluently to allow for streamlined HTML5
editing using all of the good old SGML-mode features.
