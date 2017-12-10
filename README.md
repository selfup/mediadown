# Mediadown

_Please read the medium [developer agreement](https://github.com/Medium/medium-api-docs#developer-agreement) for using their API._

Write markdown and get a nice Medium Blog Post in return!

### Install

`npm install -g mediadown`

Make a directory for your markdown files: `mkdir posts_md`

Pick the absolute file path for your file and then: `MEDIUM_TOKEN=YOUR_MEDIUM_TOKEN mediadown <file_path>`

Or for a bit more clarity (example): `MEDIUM_TOKEN=1234567abcdefg mediadown ~/posts_md/newest_post.md`

_You may also source or set your ENV variable for the MEDIUM_TOKEN anywhere that is needed prior to running the scripts and just use `mediadown <path_t0_file>`_

To get your Medium token visit: https://github.com/Medium/medium-api-docs#22-self-issued-access-tokens

### Enjoy!

Please feel free to open any issues you may encounter as long as they are not user error (that you know of) :smile:
