# to actually build it locally, run extconf.rb in /ext, then make

require 'jeweler' # 1.8.4 also libxml2-dev package on linux and libxslt-dev
Jeweler::Tasks.new do |gemspec|
    gemspec.name = "google_hash"
    gemspec.summary = "Ruby wrappers to the google hash library"
    gemspec.description = gemspec.summary
    gemspec.email = "rogerdpack@gmail.com"
    gemspec.homepage = "http://github.com/rdp/ruby_google_hash"
    gemspec.authors = ["rogerdpack"]
    gemspec.add_dependency('sane') # real dependency as it's used for building the gem, in the extconf.rb file
    gemspec.add_development_dependency('hitimes')
end

