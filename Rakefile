require 'hoe'
require './lib/cryptopunks/version.rb'

Hoe.spec 'cryptopunks' do

  self.version = Cryptopunks::VERSION

  self.summary = "cryptopunks - mint your own 24×24 pixel punk images off chain from the True Official Genuine CryptoPunks™ sha256-verified original 10 000 unique character collection; incl. 2x/4x/8x zoom for bigger sizes"
  self.description = summary

  self.urls    = { home: 'https://github.com/cryptopunksnotdead/cryptopunks' }

  self.author  = 'Gerald Bauer'
  self.email   = 'wwwmake@googlegroups.com'

  # switch extension to .markdown for gihub formatting
  self.readme_file  = 'README.md'
  self.history_file = 'CHANGELOG.md'

  self.extra_deps = [
    ['crypto-lite'],
    ['chunky_png'],
    ['csvreader'],
  ]

  self.licenses = ['Public Domain']

  self.spec_extras = {
    required_ruby_version: '>= 2.3'
  }

end
