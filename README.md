# Manuscripts Handbook and Notes

## What's Manuscripts?

Manuscripts is a free (and public domain) book format for Markdown.
Basically just a bunch of text files (in markdown) plus a `book.yml` (for the book info e.g. title, author, edition, year, etc.)
and `contents.yml` (for table of contents and the file structure) file.


## Book Info, Table of Contents & File Structure

### `book.yml`

Name. Open Questions?

- use `book.yml` or `.book.yml` or `_book.yml` or `.book/book.yml`  ??

- use just `author` or `authors`
- or use 

```
author:
  name:
-or-
authors:
  - name:
  - name:
```
  


### `contents.yml`

Name. Open Questions?

- use `contents.yml` or `.contents.yml` or `_contents.yml` or `.book/contents.yml` ??


## Text

Any text files using the markdown formatting style in any order in any folder structure you please.


## Images

Any images in any folder structure you please.

Note: For a single-page book everything gets merged into a single page (hence, the name ;-) and for your images in your build
you have two options:

1) All images get copied along into the "top-level" folder of the single-page book   - or -
2) All images get copied along into a single `/i`, `/images` or `/your-name-here`  (sub) folder.



## License

The Manuscripts format and conventions are dedicated to the public domain.
Use it as you please with no restrictions whatsoever.

## Questions? Comments?

Send them along to the [wwwmake mailing list/forum](http://groups.google.com/group/wwwmake). Thanks.

