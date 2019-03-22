# gkc_utils

### About
* Ruby script for prepend hash code in file
### Technical
* Using `git` command to ignore files on `.gitignore` such as: `node_modules`, `.bundle`
### Example
* `./script.rb -h `: list options
* `./script.rb {hash_code} -f Gemfile`: add hash code to `Gemfile`
* `./script.rb {hash_code} app/assets/stylesheets -l css`: add hash code to `app/assets/stylesheets` with `.css` extension
* `./script.rb -c test.yml {hash_code}`: Run with file config `test.yml`
