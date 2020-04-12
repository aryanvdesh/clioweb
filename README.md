clio is a browser plugin that will process search history and recommend books based on articles that you’ve read.
### Idea

Recommending books based on your search activity (specific) search history. Aim is to base this on a differentially private ML to make media recommendations.

### Creation Process

Since it isn't possible to visit the local library anymore due to the outbreak, clio suggests you books based on your surfing with personalised recommendations!

### Process

1. We pull your browser history using Chrome Extension APIs.
2. We make requests, to visited URLs over a time window, and parse the pages.
3. We extract topics based on these which we store on your client.
4. We then generate recommendations through these stored topics.

### Installation
* Navigate to chrome://extensions
* Click install unpacked extensions and select this repository through the file tree popup.
* That's it! Enjoy :)

### Notes

* All search history processing is done on the client (i.e. your browser). You don't have to worry about privacy concerns.
* In the future we aim to move to more sophisticated ML models to recommend topics, in which case we plan to move over to a backend stack based on differentially private ML. TLDR: we care about the privacy of your data :)
