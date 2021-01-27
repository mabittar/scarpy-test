# Scrapy-test

First test with Scrapy

Official Doc [here](https://docs.scrapy.org/en/latest/index.html)

## Install guide

I'm using [VS Code](https://code.visualstudio.com/), so everything I'd from powershell instance.

I tried to install using `pip install Scrapy` but got an error. Search on StackOverflow I've found the solution.

You could see the [post](https://stackoverflow.com/questions/42320197/not-able-to-install-scrapy-in-my-windows-10-x64-machine).

I had downloaded the matching Twisted OS file from https://www.lfd.uci.edu/~gohlke/pythonlibs/#twisted and saved in my project folder. Then I used `pip install Twisted‑20.3.0‑cp39‑cp39‑win_amd64.whl` to install it, so I tried `pip install Scrapy` and it's work.

## Starting a Project

With Scrapy installed correctly now try on terminal window `start project name_of_your_project` and you see a return message `New Scrapy project 'name_of_your_project', using template directory` .

I called mine first, from first project.
