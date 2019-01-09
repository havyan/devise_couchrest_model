source 'https://rubygems.org'

group :test do
  gem "test-unit",  ">= 2.0.9"
  gem "webrat",     ">= 0.7.0"
  gem "mocha",      ">= 0.9.8", :require => false
end

group :default do
  gem "rails",      ">= 3.2.0"
  gem "webrat",     ">= 0.7.0"

  gem 'couchrest_model',        '>= 2.0.4'
  gem 'devise',                 '>= 2.1.0'
  gem 'devise-encryptable'
  gem 'bson_ext',               '>= 1.2.0'

  gem 'rake',                   '>= 0.8.7'
  gem "orm_adapter"
  gem "orm_adapter_couchrest_model", git: 'https://github.com/mudynamics/orm_adapter_couchrest_model.git',
                                     ref: '4e8b55de11354c7308b35b091506cee69d6bb5b6'
  # gem "oa-oauth",   '>= 0.3.0', :require => "omniauth/oauth"
  # gem "oa-openid",  '>= 0.3.0', :require => "omniauth/openid"
  gem "omniauth-openid", '>=1.0.0'
  gem "omniauth-facebook", '>=1.2.0'
end
