# ThatQuiz Answer Scrape
The application presents two tabs; one contains a WKWebView object, which evaluates JS that scrapes answers as questions are loaded, and the other is the answerlist.

As a side effect of tab switching, it appears that the password requirement on student profiles can be bypassed. If you, who's reading this, have any idea of why it might be ocurring, do let me know.

Multiple-choice questions are not implemented, but slides and short answer questions work perfectly fine.

For a python implementation of the same method used here, see [this gist](https://gist.github.com/Javgarag/dd02d155cc534f2d23eb90f85b2e0fa4).
