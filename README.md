# Manuscripts Handbook and Notes

## What's Manuscripts?

Manuscripts is a free (and public domain) book format for Markdown.
Basically just a bunch of text files (in markdown) plus a `book.yml` (for the book info e.g. title, author, edition, year, etc.)
and `contents.yml` (for table of contents and the file structure) file.


## Book Info, Table of Contents & File Structure

### `book.yml`

Name. Open Questions?

- use `book.yml` or `.book.yml` or `_book.yml` or `.book/book.yml`  ??



#### Keys

##### Author(s)

- use just `author` or `authors`
- or use 

```
author:
  name:
-or-
authors:
  - name:
  - name:
-or-
author:
```
  
Allow one or many or shortcut (w/o name).



### `contents.yml`

Name. Open Questions?

- use `contents.yml` or `.contents.yml` or `_contents.yml` or `.book/contents.yml` ??


#### Keys

##### Id [optional]

Use `id` for references.

##### Title [required]

Use `title` for title.

##### Label [optional]

Use `label` for prefix e.g. Appendix, Chapter 1, Part I, Section 1.1, etc.

##### Number [optional]

Use `n` or `num` or `number` for counter (note: is not a number but a string)
e.g.: 1. or 1.1. or A.1. or I.§1b etc.

##### Path [optional]

Use `path` for the relative local file path.



## Text

Any text files using the markdown formatting style in any order in any folder structure you please.


## Images

Any images in any folder structure you please.

Note: For a single-page book everything gets merged into a single page (hence, the name ;-) and for your images in your build
you have three options:

1. All images get copied along into the "top-level" folder of the single-page book   - or -
2. All images get copied along into a single `/i`, `/images` or `/your-name-here`  (sub) folder  - or -
3. All images get base64 encoded (ascii-fied) and inlined and embedded into the single-page book.



## License

The Manuscripts format and conventions are dedicated to the public domain.
Use it as you please with no restrictions whatsoever.

## Questions? Comments?

Send them along to the [wwwmake mailing list/forum](http://groups.google.com/group/wwwmake). Thanks.

