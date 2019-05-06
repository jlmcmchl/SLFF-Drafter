## SLFF-Drafter


##### Setup

Requires Python 3.6+ (may work on earlier versions, we dunno)

Create a file named `keys.py` in the root directory of the project that contains your Discord Bot token:

```python
DISCORD_TOKEN = "my_discord_token"
```

We recommend you create a [virtualenv](https://virtualenv.pypa.io/en/latest/) to handle dependencies.

```bash
$ pip install -r requirements.txt
$ python bot.py
```

If you add a new dependency, add it to `requirements.txt`:

```bash
$ pip freeze > requirements.txt
```
