# Simple Time Tracker

## What is it?

Time-Tracker is a simple command line tool which asks what you did the past days when you open up your terminal. 

It starts 3 days ago, ignores weekends, and will only ask you what you did _today_ after 4pm.

It stores the information in simple text files, and lets you see the full list using the `time-tracker log` feature.

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
