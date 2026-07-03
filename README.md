# Consumer Electronics Alumni Tracker

This is a static, shareable HTML dashboard for consumer-electronics-company alumni founders and executives.

## Files

- `index.html`: interactive public dashboard
- `consumer_electronics_alumni_expanded_A_recent.csv`: exported source table
- `expanded_parent_pool.json`: source pool and summary counts
- `robots.txt`: asks crawlers not to index the site
- `.nojekyll`: disables Jekyll processing on GitHub Pages

## Publishing

The simplest long-term setup is GitHub Pages from the repository root on the `main` branch.

When the local source data changes, regenerate the HTML/CSV in the main workspace, copy the refreshed files into this repository, commit, and push to GitHub. GitHub Pages will publish the updated static site from the latest commit.
