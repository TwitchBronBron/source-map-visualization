# source-map-visualization

http://twitchbronbron.github.io/source-map-visualization/

## Changes from https://github.com/sokra/source-map-visualization/
 - better drag and drop support. Previously you had to drag and drop all 3 files together (and they had to be .js style files). Now you can drag and drop any files in any order, and once we find enough files, THAT's when we trigger the visualization.
 - support 100,000 lines of code instead of 5,000.
 - allow sourceContent to be an empty string

## Contribute

Development:

```bash
npm install
npm start
```
