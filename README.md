# Chrome profile persistence check

A small, dependency-free test page from the Cloudbrowser team. It saves the same disposable label in Chrome local storage and in page memory so you can see which state survives a reload. The page also walks through checking a paused profile and comparing independent browser forks.

## Run the example

Open the [live test page](https://langyi-ship-it.github.io/chrome-profile-persistence-check/). You can also serve `index.html` over HTTP and open its URL in Chrome. Keep the URL the same across the browsers you compare. Use a fresh test browser and a synthetic label.

The app stores the label only in the browser. The [Cloudbrowser lifecycle documentation](https://cloudbrowser.tv/docs/browsers) explains pause, resume, fork, and connection handling.
