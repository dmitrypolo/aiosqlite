aiosqlite
=========

v0.11.0
-------

Feature release

- Added support for `set_progress_handler` (#49)
- Improved and updated documentation

```
$ git shortlog -s v0.10.0...v0.11.0
     9	John Reese
     4	Stanislas
     2	Vladislav Yarmak
     1	pyup-bot
     5	tat2grl85
```


v0.10.0
-------

Feature release v0.10.0:

- Support using connections without context managers (#29)
- Include test suite in aiosqlite package

```
$ git shortlog -s v0.9.0...v0.10.0
    16	John Reese
     1	Simon Willison
     1	dark0ghost
```


v0.9.0
------

Feature release v0.9.0:

- Support for sqlite extensions
- Fixed support for type annotations on early Python 3.5

```
$ git shortlog -s v0.8.1...v0.9.0
     2	Alexander Lyon
     3	John Reese
```


v0.8.1
------

Bug fix release v0.8.1:

- Fix connections to byte string db locations (#20)

```
$ git shortlog -s v0.8.0...v0.8.1
     1	DevilXD
     6	John Reese
```


v0.8.0
------

Major release v0.8.0:

- Use futures instead of polling for connections/cursors.
  This will significantly reduce time spent blocking the
  primary event loop, resulting in better performance of
  asyncio applications using aiosqlite.

```
$ git shortlog -s v0.7.0...v0.8.0
     3	John Reese
     2	Matthew Schubert
```


v0.7.0
------

Feature release v0.7.0:

- Added macros for combined insert/id and select/fetch
- Better perf testing output

```
$ git shortlog -s v0.6.0...v0.7.0
     1	Grigi
     4	John Reese
```


v0.6.0
------

Feature release v0.6.0:

- Performance improvements for atomic or fast queries
- Support passing Path-like objects to aiosqlite.connect
- Unit tests now use aiounittest instead of a custom test harness
- Limited set of performance tests now available

```
$ git shortlog -s v0.5.0...v0.6.0
     1	Grigi
     8	John Reese
```


v0.5.0
------

Feature release v0.5.0:

- More aliases from sqlite3, including Row, errors, and register_*
- Additional connection properties for row/text factory, total changes
- Better readme

```
$ git shortlog -s v0.4.0...v0.5.0
     6	John Reese
```


v0.4.0
------

Feature release v0.4.0:

- Enable using a custom asyncio event loop
- Increase performance by decreasing sleep time

```
$ git shortlog -s v0.3.0...v0.4.0
    15	John Reese
     1	Justin Kula
     1	Richard Schwab
```


v0.3.0
------

Feature release v0.3.0:

- Cursors can be used as context managers

```
$ git shortlog -s v0.2.2...v0.3.0
     6	John Reese
     5	Linus Lewandowski
```


v0.2.2
------

Minor release:

- Correct aiosqlite.__version__
- Markdown readme, release via twine

```
$ git shortlog -s v0.2.1...v0.2.2
     5	John Reese
```


v0.2.1
------

Minor release v0.2.1:

- Increase polling speed on event loop
- Using black and pylint

```
$ git shortlog -s v0.2.0...v0.2.1
     8	John Reese
     2	Pavol Vargovcik
```


v0.2.0
------

Beta version 0.2.0

```
$ git shortlog -s c606de200b7afe6d73a6e2900557d622c62ed78c...v0.2.0
     1	John Reese
```


