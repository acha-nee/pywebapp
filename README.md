# University Project

[![Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/ccrsxx/pywebapp/app.py)
[![Heroku](https://pyheroku-badge.herokuapp.com/?app=ccrsxx)](https://ccrsxx.herokuapp.com)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## About

I made this web app to finish a project assigned by my teacher. It is written entirely in Python, thanks to [Streamlit](https://github.com/streamlit/streamlit) to make it possible.

It contains three games. The games are:

1. Guess Number
2. Guess Word
3. Tic Tac Toe

## Installation and usage

You can either run it on your local machine (localhost) or host it on a server, in my case I use Heroku.

### Local

1.  Clone this repository. Make sure [git](https://git-scm.com/) is installed and run:

    ```bash
    git clone https://github.com/ccrsxx/University-Project.git
    ```

2.  Install the dependencies with pip. Run:

    ```bash
    pip install -r requirements.txt
    ```

3.  Run the web app. Run:
    ```bash
    streamlit run app.py
    ```

### Heroku

1.  Clone this repository. Make sure [git](https://git-scm.com/) is installed and run:

    ```bash
    git clone https://github.com/ccrsxx/University-Project.git
    ```

2.  Login to your Heroku account. Make sure [heroku-cli](https://devcenter.heroku.com/articles/heroku-cli) is installed and run:

    ```bash
    heroku login
    ```

3.  Create the app name, this will be your site name. Run:

    ```bash
    heroku create sample_app
    ```

4.  Push all the files to Heroku. Run:
    ```bash
    git push heroku master
    ```
