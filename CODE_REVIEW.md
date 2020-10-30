Task1 :

Step 2 :

- Create a new observable (resultListBooks) and use aync pipe to subscribes to the observable
  File : book-searchComponent async pipe (fixed)
- Use pipe operaters for the Date rather than calling custom function . (fixed).
  File : book-search.component.html line 25 use date pipe instead of formatDate.
- Error Messaging needs to be improved/added when the API fail eg in BooksEffects when we fail get data .
- Implement service Worker to cache response which will prevent mutiple request for the same request.  
- Improve Code Coverage ( eg book-search.component.ts, books.reducer.ts,reading-list.effects.ts ,reading-list.reducer.ts has less than 83% coverage).
