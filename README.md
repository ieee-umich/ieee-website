# IEEE UMich Website
Last Edited by Shuta Suzuki (shutas@umich.edu) on May 31th, 2018.

## Contributors
- Akshay Chiwhane (achiwha@umich.edu)
- Shuta Suzuki (shutas@umich.edu)
- Anthony Wohlfeil (antwohlf@umich.edu)

## Getting Started
- Install Jekyll  
`gem install jekyll`

- And Probably a Bunch of Other Dependencies (please add to this list if you find any)  
`gem install bundler`  
`bundle install`  
`gem install nokogiri` (this should be included in `bundle install`, but I had to install it separately)  
`gem install rouge`

- Navigate to Website Directory in Your Terminal (obviously you need to `git clone` this repo first...)

- Run `jekyll serve` (if you're lucky)  
I had to `bundle exec jekyll serve` instead

- Just in case...   
`jekyll build` or `bundle exec jekyll build` to rebuild.  
This is probably rare, but if you edit certain files like [_config.yml](_config.yml) that do not get reloaded by simply serving, then you need to restart the serve process.

## Troubleshooting
Setting up the development environment for Ruby is a _pain_. Luckily, I have a few suggestions that may help if you're stuck somewhere in the installation process:

- Ensure that you have the most recent bundler  
  `gem update bundler`

## Note
This website uses Jekyll, a static website generator. 
