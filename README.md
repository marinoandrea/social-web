# social-web

Project repository for the Social Web 2022 course at VU Amsterdam

## Setup

Firs, make sure poetry is available on your system, if not already installed, do so with the following command:

```bash
curl -sSL https://install.python-poetry.org | python3 -
```

Then install the project dependencies:

```bash
poetry install
```

Finally, in order to run the tasks we expect the reader to have a `.env` file available with secrets and necessary configuration variables.
We provide the following as a template:

```env
TWITTER_CONSUMER_KEY="..."
TWITTER_CONSUMER_SECRET="..."
TWITTER_OAUTH_TOKEN="..."
TWITTER_OAUTH_TOKEN_SECRET="..."
```

## Usage

In order to run the `jupyter` server simply type:

```bash
poetry run jupyter notebook
```
