# Xvfb Buildpack for Heroku

This buildpack installs Xvfb (X Virtual Framebuffer) on a Heroku dyno, allowing you to run applications that require a graphical user interface headlessly.

## Usage

To use this buildpack, add it to your application's buildpacks:

```bash
heroku buildpacks:add https://github.com/psrnk/heroku-buildpack-xvfb
