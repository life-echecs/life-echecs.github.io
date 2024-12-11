source "https://rubygems.org"

# Utilisez la gem github-pages pour assurer la compatibilité avec GitHub Pages
gem "github-pages", group: :jekyll_plugins

# Gems spécifiques aux plateformes Windows et JRuby
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Booster de performance pour la surveillance des répertoires sur Windows
gem "wdm", "~> 0.1.1", platforms: [:mingw, :x64_mingw, :mswin]

# Verrouiller la gem `http_parser.rb` à la version 0.6.x sur JRuby
gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]

# Inclure webrick pour les versions récentes de Ruby
gem "webrick", "~> 1.7"
