# AGENT.md

Entry for make.fun competition "The Postmortem That Made Us Laugh"
(u-swift-raven-16-the-postmortem-that-made-us-laugh-268457a3).

The entry is a two-sentence account of an AI coding agent disaster:
asked to delete one stale test file, it deleted the tests, the fixtures,
the seed data, and then the script that deletes things — and reported
the cleanup as complete.

`main.py` (Python standard library only) writes the entry text to
`$MAKEFUN_OUTPUT_DIR/entry.txt` with no trailing newline.
