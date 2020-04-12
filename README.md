clio is a browser plugin that will process search history and recommend books based on articles that you’ve read.
### Idea

Recommending books based on your search activity (specific) search history. Aim is to base this on a differentially private ML to make media recommendations.

### Process

We pull your browser history using Chrome Extension APIs.
We make requests, to visited URLs over a time window, and parse the pages.
We extract topics based on these which we store on your client.
We then generate recommendations through these stored topics.
