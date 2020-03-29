rails_best_practices mirror
===========================

Mirror of rails_best_practices gem for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit
For rails_best_practices: see https://github.com/flyerhzm/rails_best_practices


### Using rails_best_practices with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: https://github.com/adithyabsk/mirrors-rails-best-practices
        rev: ''  # Use the sha / tag you want to point at
        hooks:
        -   id: rails_best_practices


**Based on**: https://github.com/pre-commit/mirrors-ruby-lint