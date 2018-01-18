# Heroku Buildpack for Ghostscript (full version)

Currently installs Ghostscript 9.22 on Heroku Cedar. This buildpack takes the binary available at https://www.ghostscript.com/download/gsdnld.html

## Install

    $ cd /path/to/your-app
    $ heroku buildpacks:add https://github.com/jpaas/heroku-buildpack-ghostscript.git

    # Push changes to deploy
    $ git push
