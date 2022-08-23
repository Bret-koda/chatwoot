release: bundle exec rails db:chatwoot_prepare
web: bin/rails server -p 4000 -e development
worker: bundle exec sidekiq -C config/sidekiq.yml
