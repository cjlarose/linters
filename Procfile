web: bundle exec ruby app.rb -p $PORT
resque: TERM_CHILD=1 RESQUE_TERM_TIMEOUT=7 QUEUES=scss_review bundle exec rake jobs:work