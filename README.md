tcptrace - A More Colorful tcpdump
================================

`tcpdump` is pretty frickin' sweet right?  What with its metadata,
hex dumps and more, it's really bleeding useful for anyone who has
to troubleshoot anything that talks over a network (which, let's
face it, is _everything_ these days).

Sure would be nice if it did colors though...

`tcptrace` to the rescue!

![screenshot](https://raw.githubusercontent.com/jhunt/tcptrace/master/screenshot.png)

Installation
------------

It's Perl, but it doesn't need any modules, just `perl` herself.
To install `tcptrace`, just curl or copy the binary somewhere in
`$PATH` and chmod to taste

```
curl https://raw.githubusercontent.com/jhunt/tcptrace/master/tcptrace > ~/bin/tcptrace
chmod 0755 ~/bin/tcptrace
```

Usage
-----

Use it like `tcpdump`!

```
tcptrace -i lo port 5432
```

Enjoy the colors!
