clear_sources
bundle_path "vendor/bundler_gems"

source "http://gemcutter.org"
source "http://gems.github.com"

gem "rails", "2.3.4", :only => :bundle
gem "clearance"
gem "will_paginate"
gem "ddollar-pacecar", "1.1.6", :require_as => "pacecar"

gem "shoulda",             :only => :test
gem "factory_girl",        :only => :test
gem "webrat",              :only => :test
gem "cucumber", "0.3.101", :only => :test
gem "rr",                  :only => :test
gem "redgreen",            :only => :test
gem "fakeweb",             :only => :test
gem "rack-test",           :only => :test, :require_as => "rack/test"

gem "rack-cache",        :require_as => "rack/cache", :only => :production
gem "aws-s3",            :require_as => "aws/s3",     :only => :production
gem "ambethia-smtp-tls", :require_as => "smtp-tls",   :only => :production
gem "memcache-client",   :require_as => "memcache",   :only => :production
