# Grant Nieda's Website and Blog


## Useful resources

Issues solved from 7.3.0 forked version on June 16, 2025
- Outdated packages using Ubuntu 'sudo apt install' (Ruby, bundler, rbenv, aria2c)
- Don't use snap for Ruby projects due to permission issues and poor version control
- Fork the repository instead of cloning, the init.sh file will not work without forking
- gem 'jekyll-include-cache', '~> 0.2' added to the Gemfile
- Manually installed Ruby 3.1.0 using rbenv (Ubuntu current version is out-of-date: 3.0.7)
- Removed snap and rvm
- Edit bashrc file to prioritize rbenv instead of local system version
- Removed husky and commitlint using npm
- changed ruby version in the _config.yml file (deployment works!)

TODO:
- Work on deattaching the fork from the website (completed)
- Creating the first blog post



### Documentation

To learn how to use, develop, and upgrade the project, please refer to https://chirpy.cotes.page/posts/getting-started/


## License

This project is published under [MIT License][license].
