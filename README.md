setup

```bash
brew install python
brew install python-tk
python3.12 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

just run this command to do everything:

```bash
scripts/next.sh
```

open empty file for next version of script

```bash
scripts/create_next_iteration.sh
```

run most recent version:

```bash
scripts/run_most_recent_iteration.sh
```

TODO: use something like this to auto diff https://stackoverflow.com/questions/63196987/is-there-api-for-files-comparison-in-vscode
