# twofiveohwebsite

indev version of the summary website for the twofiveoh podcast. compiled page is hosted on github pages; instead of running a backend the repository of podcast episodes is compiled by the twofiveoh team as a json file using [```./twofiveoh/imdbscrape.py```](https://github.com/uuupah/twofiveoh_website/blob/main/twofiveoh/imdbscrape.py). page is built in react with minimal imports.

## todo
- [ ] frontend
    - [x] core layout
    - [ ] whooshka embeds
    - [ ] spotify / itunes links
    - [ ] better breakpoints to improve narrow desktop experience
- [x] "backend"
    - [x] core data queried from imdb api
    - [x] extra episode data
