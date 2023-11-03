# frozen_string_literal: true

source 'https://rubygems.org'

gemspec

platform :jruby do
  gem 'jruby-openssl', '~> 0.7'
end

# gem 'wordlist', '~> 1.0', github: 'postmodern/wordlist',
#                           branch: 'main'

# Ronin dependencies
gem 'ronin-support',  '~> 1.1', github: 'ronin-rb/ronin-support',
                                branch: '1.1.0'

gem 'ronin-core', '~> 0.2', github: 'ronin-rb/ronin-core',
                            branch: '0.2.0'

# gem 'ronin-repos',    '~> 0.1', github: 'ronin-rb/ronin-repos',
#                                 branch: 'main'

gem 'ronin-db-activerecord', '~> 0.2', github: 'ronin-rb/ronin-db-activerecord',
                                       branch: '0.2.0'

gem 'ronin-db',      '~> 0.2', github: 'ronin-rb/ronin-db',
                               branch: '0.2.0'

gem 'ronin-masscan', '~> 0.1', github: 'ronin-rb/ronin-masscan',
                               branch: 'main'

gem 'ronin-nmap',    '~> 0.1', github: 'ronin-rb/ronin-nmap',
                               branch: 'main'

gem 'ronin-web-spider',  '~> 0.2', github: 'ronin-rb/ronin-web-spider',
                                   branch: '0.2.0'

group :development do
  gem 'rake'
  gem 'rubygems-tasks',   '~> 0.2'

  gem 'rspec',            '~> 3.0'
  gem 'simplecov',        '~> 0.20'

  gem 'kramdown',         '~> 2.0'
  gem 'kramdown-man',     '~> 0.1'

  gem 'redcarpet',        platform: :mri
  gem 'yard',             '~> 0.9'
  gem 'yard-spellcheck',  require: false

  gem 'dead_end',         require: false
  gem 'sord',             require: false, platform: :mri
  gem 'stackprof',        require: false, platform: :mri
  gem 'rubocop',          require: false, platform: :mri
  gem 'rubocop-ronin',    require: false, platform: :mri
end
