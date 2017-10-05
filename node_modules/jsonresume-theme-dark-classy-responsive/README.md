#jsonresume-theme-classy-responsive

An uber-classy theme for JSONResume, now responsive.

## Usage

To first get started with this JSONResume theme, you'll need to have the JSONResume CLI installed. If you haven't already install it with `npm install -g resume-cli`. If this doesn't work, try `sudo npm install -g resume-cli`.

After this, you can get your resume.json ready by typing `resume init`. After hitting enter, your resume will be initialized and you can edit it and fill in the neccessary fields. Check out [the official resume-schema repository](https://github.com/jsonresume/resume-schema) for more information on filling these fields.

When you are finished with your resume, you may test it by yet again opening the command line and typing `resume serve --theme classy` to see how it looks with this theme. You can replace the word `classy` with other theme names too.

If you want a local copy of your resume, type in `resume export resumeName --theme classy`, and replace `resumeName` with the desired filename. You can export it in pdf and txt using the `--format` flag, like so:

```
resume export resume --format pdf --theme classy
```

However, if you wish to export it to the JSONResume Registry, use the command `resume publish` instead.

More details about the CLI and it's commands are available [here](https://github.com/jsonresume/resume-cli).

## Colophon

Thanks to the wonderful [Font Awesome](https://fontawesome.io) for their free-to-use icon font, and a big thank you to the JSONResume theme for their wonderful idea and helping me with a few issues on my part.
