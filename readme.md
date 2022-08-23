# NSERC DG proposal template '22

This repository contains a LaTeX template for preparing the proposal and references documents as part of a NSERC Discovery Grant application. If you don't know what NSERC or a DG is, you probably don't need it.

This follows NSERC guidelines to the best of my knowledge but I cannot guarantee it will meet them. You are responsible for ensuring your document meets all formatting requirements; I take no responsibility for that, and no responsibility or blame if your submission gets desk-reject for formatting violations.

## Q&A


**Q:** This is not good LaTeX. Why didn't you put all formatting commands in a separate class?  
**A:** Because I am lazy and this gets the job done.

**Q:** Doesn't this make LaTeX look like Word?  
**A:** It kinda does, although that was not the goal. It may not look the best, but this template keeps everything in 12pt font with nicely tight spacing.

**Q:** `\subsection` does not match the rest of the document. Why?  
**A:** I only redefined formatting for `\section` commands; I don't use `\subsection`, `\subsubsection` and `\paragraph` because too many headings take away precious real estate (you only have five pages after all!). If you plan to use them, you can redefine them similarly to what I did with `\section`.
