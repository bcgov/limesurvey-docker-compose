# LimeSurvey Docker Compose
==========

This repository was forked from [https://github.com/adamzammit/limesurvey-docker](https://github.com/adamzammit/limesurvey-docker)

## How to use this image

Run `docker-compose up`, wait for it to build and run, and visit `http://localhost:8082`.

## Caveats

- Chrome may try to force https when connecting. https isn't supported yet so you'll need to be explicit about accessing localhost over http.

## Working with themes

New survey themes are added under themes/survey. Once added therein, you'll need to install them in the admin interface.

When you make theme modifications(such as extending it and changing theme files), the extended/copied theme will be added to uploads/themes/survey.