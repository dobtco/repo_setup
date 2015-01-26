repo_setup
----

## Configuration

`cp .env.example .env` and configure with a personal access token.

## Usage

### To add labels from `labels.yml`

`./repo_setup add org/repo`

### To remove labels that aren't present in `labels.yml`

`./repo_setup remove org/repo`

### 2-in-1 (add & remove)

`./repo_setup setup org/repo`
