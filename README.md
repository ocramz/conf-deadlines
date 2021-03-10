# Conference Deadlines 

[![Build Status](https://github.com/yttty/conf-deadlines/actions/workflows/jekyll.yml/badge.svg)](https://github.com/yttty/conf-deadlines)

Countdown timers to keep track of a bunch of SE/NLP/ML/PL/DM conference deadlines.

### Contributing

Contributions are very welcome!

Feel free to maintain a separate fork if you don't see your sub-field or conference of interest listed.

To add or update a deadline:
- Fork the repository
- Update `_data/conferences.yml`
- Make sure it has the `title`, `year`, `id`, `link`, `deadline`, `timezone`, `date`, `place`, `sub` attributes
    + See available timezone strings [here](https://momentjs.com/timezone/).
- Optionally add a `note` and `abstract_deadline` in case the conference has a separate mandatory abstract deadline
- Send a pull request


### License

MIT
