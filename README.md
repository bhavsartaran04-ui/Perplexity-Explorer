# Perplexity Explorer

A small browser based tool for exploring token probabilities and language model perplexity.

## Run

Open `index.html` in a modern browser. On the first calculation, the page downloads the DistilGPT-2 model through Transformers.js. A network connection is needed for the model and library CDNs.

The page includes:

- Token probabilities and a perplexity calculation for a sentence
- Next token predictions
- A manual probability calculator for experimenting with perplexity

## Notes

The language model runs in the browser. The manual calculator is simulated and does not use the model.
