# Batuli

An utility irc bot for ##testbot on freenode.
Works on Python 2.7+

## Instructions
* `git clone git@github.com:SanketDG/batuli.git`
* `pip install -r requirements.txt`
* `python main.py`

* To run the bot in logging mode:
```shell
python main.py -l <filename>
```
The channel logs will be saved in `<filename>`.

## Current Features
* `~pym` Gives link to [pymbook](http://pymbook.readthedocs.org/en/latest/)
* `<nickname>, hello` or `<nickname>: hello` Hello's back!
* `<nickname>, ping` or `<nickname>: ping` Pong's back!
* `~date` or `<nickname>, date` or `<nickname>: hello` Print's current date and time.
* `~random` display's a random snippet from commandlinefu.com
* `~whatis <word>` fetches one sentence summary from wikipedia about word.

## LICENSE

MIT
