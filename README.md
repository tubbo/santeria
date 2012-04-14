# My Sublime Configuration

These are my settings for [Sublime Text 2][subl]. I am also using the [Soda theme][soda].

## Installation

Before installing...

- Make sure **Sublime Text 2 is CLOSED!!**
- Install the Soda theme

### Setup

Go to your Sublime Text 2 library:

    cd "~/Library/Application Support/Sublime Text 2"

Make a backup of your **Packages/User** folder,

    mkdir -p "Packages/User (backup)"
    cp -R Packages/User/* "Packages/User (backup)"

And clone the repo into your User folder.

    git clone git://github.com/tubbo/santeria.git Packages/User

Now restart Sublime Text 2. You should see a solarized TextMate. ;-)

[soda]: https://github.com/buymeasoda/soda-theme
[subl]: http://sublimetext.info
