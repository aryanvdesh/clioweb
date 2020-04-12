
clio is a browser plugin that will process search history and recommend books based on articles that you’ve read.
### idea

Recommending books based on your search activity (specific) search history. Aim is to base this on a differentially private ML to make media recommendations.

### creation process

Since it isn't possible to visit the local library due to the outbreak, clio suggests you books based on your surfing with personalised recommendations!

### process

* We pull your browser history using Chrome Extension APIs.
* We make requests, to visited URLs over a time window, and parse the pages.
* We extract topics based on these which we store on your client.
* We then generate recommendations through these stored topics.

### installation
* Navigate to chrome://extensions
* Click install unpacked extensions and select this repository through the file tree popup.
* That's it! Enjoy :)

### note

* All search history processing is done on the client (i.e. your browser). You don't have to worry about privacy concerns.
* In the future we aim to move to more sophisticated ML models to recommend topics, in which case we plan to move over to a backend stack based on differentially private ML. TLDR: we care about the privacy of your data :)
