# Backup your signal conversations

The following repo, [signal-export](https://github.com/carderne/signal-export), provides a way to export your signal conversations into markdown from the signal desktop app.

In short

```
docker pull carderne/sigexport
pip install signal-export
sigexport --list-chats
sigexport --chats <your chat here> location
```

This repo will share some further parsing of those markdown files for convenience sake.
