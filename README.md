repo_setup
----

This repository handles the provisioning of labels across our GitHub repositories. To read about our labels and their usage, see [labels.yml](https://github.com/dobtco/repo_setup/blob/master/labels.yml).

## Configuration

`cp .env.example .env` and configure with a personal access token.

## Usage

### To add labels from `labels.yml`

`./repo_setup add org/repo`

### To remove labels that aren't present in `labels.yml`

`./repo_setup remove org/repo`

### 2-in-1 (add & remove)

`./repo_setup setup org/repo`
