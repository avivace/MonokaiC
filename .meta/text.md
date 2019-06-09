# Header

Lorem ipsum **dolor** sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in *reprehenderit* in voluptate `void dP(int x, int y)` velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laboru m. \* Escaped characters are highlighted, too.

## Something else

>>>> A blockquote
>>>> Lorem ipsum **dolor** sit amet, consectetur adipiscing elit, sed do

A list
- `monospaced inline code`
- Links:
    + [The original monokai relase](http://www.monokai.nl/blog/2006/07/15/textmate-color-theme/)
    + http://google.it - This is a plain link
    + [This repo](https://github.com/avivace/colorMarkdown "Link title")
    + An image: ![das](example-image.png "a title")

---

    You can write codeblocks in markdown with 4 spaces
    like this.

Syntax highlightning inside code blocks:

```lisp
(defun per-tre-pari (l)
    (cond ((null l)
            nil)
          ((and (atom (first l)) (not (numberp (first l))))
            (error "this is not a list of numbers"))
          ((not (numberp (first l)))
            (cons (per-tre-pari (first l)) (per-tre-pari (rest l))))
          ((evenp (first l))
            (cons (* 3 (first l)) (per-tre-pari (rest l))))
          ((oddp (first l))
            (cons (first l) (per-tre-pari (rest l))))
          ))
```