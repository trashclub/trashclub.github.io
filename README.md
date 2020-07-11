# Trash Club ... online!

## Instructions for local deployment:

If you don't have Ruby installed on your computer, run `brew install ruby` on Terminal. 
`ruby -v`
Next, you'll need to update your Ruby file path to the version you just installed. (To check what version, run `ruby -v`). Update by changing the X.X to the version number: `echo 'export PATH="$HOME/.gem/ruby/X.X.0/bin:$PATH"' >> ~/.bash_profile`

At that point, you should be able to run this: `gem install --user-install bundler jekyll`, but depending on your operating system, it might fail and you can run this instead: `sudo gem install bundler`. 

Then navigate into this directory and run `bundle install`.

And when you are ready to serve locally: `bundle exec jekyll serve`. The site will deploy to `http://127.0.0.1:4000`. 

Learned all this from [Jekyll Docs](https://jekyllrb.com/docs/installation/macos/). 