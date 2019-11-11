events
======

[![builds.sr.ht status](https://builds.sr.ht/~kragniz/bristol-events.svg)](https://builds.sr.ht/~kragniz/bristol-events?)

This is an archive of past and future tech related meetup events from around
Bristol, aiming to provide an easy source of data for meetup.com replacements.
Currently only meetup.com is supported as event sources, but if local meetups
migrate to use other tools, those should be supported as well.

Each event is sourced from a collection of organisations, which are configured
in `./orgs/`.

Here's the configuration for PyData Bristol:

```json
{
    "id": "pydata",
    "name": "PyData Bristol",
    "homepage": "https://www.meetup.com/PyData-Bristol/",
    "meetup": {
        "urlname": "PyData-Bristol"
    }
}
```

The events for that org are then automatically collected in `./events/<org id>/`.

Here's an example event:

```json
{
    "description": "<p>long description here</p>",
    "end_time": 1574370000,
    "link": "https://www.meetup.com/PyData-Bristol/events/266189787/",
    "location": {
        "address": "1 Rivergate, Temple Quay, Bristol, BS1 6ED",
        "city": "Bristol",
        "country": "gb",
        "latitude": 51.45014190673828,
        "longitude": -2.5840909481048584,
        "name": "Ovo Energy"
    },
    "org": "pydata",
    "start_time": 1574361000,
    "title": "PyData Bristol - 12th Meetup"
}
```

Using
-----

Feel free to use this data for any project.

Contributing
------------

If there's a meetup or event source you'd like to see here, file an issue (or
even better a pull request!).
