# Umami Demo profile with Lightning

## Installation

1. Clone this repo
2. Run

        composer install

3. Run, including your database information. E.g. `--db-url=mysql://un:pw@127.0.0.1/db`

        drush si config_installer --account-pass=admin && drush pmu demo_umami_content && drush en demo_umami_content
        
