- Code Smells/Improvements:
    - Missing unit tests for `addBook$` and `removeBook$` in reading-list effects. (Fixed).
    - Missing unit tests for book-search component and reading-list component. (Fixed)
    - Reducer on function code is missing for `failedAddToReadingList` and `failedRemoveFromReadingList` actions (Fixed).
    - `addToReadingList` and `removeFromReadingList` actions code defined inside reducers on function call instead of `confirmedAddToReadingList` and `confirmedRemoveFromReadingList`. (Fixed).

- Fixed accessibility issues identified in Light house analysis
    - `Background and Foreground colors do not have a sufficient contrast ratio.
    - `Buttons do not have an accessible name`
  
- Manual accessiblity issues identified
    - Focus is missing for books list after search (Fixed).
    - `search` button `aria-label` is missing. (Fixed).'
    - Reading List `close` button `aria-label` is missing. (Fixed).
  
- lint and e2e are passing

