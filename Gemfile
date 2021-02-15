source 'https://rubygems.org'

ruby '2.6.3'

gem 'jekyll', "3.8.6"
gem 'html-proofer'
gem "rack", ">= 2.0.6"
gem 'asciidoctor'
gem 'asciidoctor-pdf', '~> 1.5.0.beta.5'
gem 'pygments.rb', '~> 2.1.0'

group :jekyll_plugins do
  gem 'jekyll-algolia', '~> 1.0'
  gem 'jekyll-sitemap'
  gem 'jekyll-assets'
  # jekyll-assets depends on sprockets, which depends on rack, which has two
  # security vulnerabilities prior to 2.0.6.
  # https://nvd.nist.gov/vuln/detail/CVE-2018-16471
  # https://nvd.nist.gov/vuln/detail/CVE-2018-16470
  gem 'jekyll-asciidoc'
end
