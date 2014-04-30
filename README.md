# Fat Oak

Adding all this stuff to every new project is stoopid, so I boxed it up. I'm welcome.

Built with:
- Middleman
- Bower
- Haml
- Scss

Features:
- Autoprefixer
- Modernizr
- Normalize
- jQuery
- Fontawesome

Locked and loaded with:
- middleman-blog, if you're into that
- middleman-livereload, because duh
- middleman-syntax, so code will be fun to read
- middleman-deploy, for easy deployment with rsync, Github pages, FTP, and SFTP
- middleman-minify-html, to squish markup
- readingtime, to show how long it takes to read and article

## Installation

Just clone this repo into your `~/.middleman/` directory, then run `middleman init --help` to make sure it's on the template list. 

If not then frown and [@rdnydnns](https://twitter.com/rdnydnns). 

If so then run `middleman init My_New_Project --template=fatoak` to initiate a new middleman fatoak project

## Usage
After you've created the project you'll want to grab your dependencies with bower like so

```bash
$ bower install
```

You should now have a directory called `bower-components` ( super original naming, I know ) with all the dependencies FatOak needs.

## Conclusion

I made this because I like these things, but I am only one person. If you think there's something else that should be here or something that is here that shouldn't be, tweet me [@rdnydnns](https://twitter.com/rdnydnns).