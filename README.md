# Lab Report Template

I used this my freshman year for physics and digital logic, might use it in the future but don't plan on updating it any time soon.

To use the template just clone the repo and use whatever LaTeX compiler you have installed.
```
git clone https://github.com/danninx/tu-report.sty
```

### Misc.
- If your lab/section doesn't have lab groups, you can just use `\nolabgroup` to emit the group section from the header
- You can use `\leftextra` and `\rightextra` to add things to the header, but if you add lines to one side you must then add additional lines to the other side, or the header will format strangely
    - I've only had to do this once or twice, but for the occasion there's a command `\insertlines{n}` that will insert 'n' newlines into a given position, which you can use like in the below example:

```tex
\leftextra{\insertlines{3}} % add three lines into the left side of the header
```

