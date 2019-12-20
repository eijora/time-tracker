# Simple Command Line Time Tracker

## What is it?

Time-Tracker is a simple command lime tool which asks what you did the past days. 

It starts 3 days ago, ignores weekends, and will only ask you what you did _today_ after 4pm.

It stores the information in simple text files, and I can see the full list with `time-tracker log`.

## Installation

```
npm install -g time-tracker
```

Then add this to your .bashrc/.zshrc

```
time-tracker
```

The first time it will ask you for a path to store the files in.

## Logging

To easily output your time tracking log, run:

```
time-tracker log
```

## License

MIT
