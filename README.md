# Simple Time Tracker

## What is it?

Simple-Time-Tracker is a simple command line tool based on the "track-your-damn-time" tool made by latentflip. 

When you open up your terminal, it will ask you what you did the past days. It starts 3 days ago, ignores weekends, and will only ask you what you did _today_ after 4pm.

It stores the information in simple text files, and lets you see the full list using the `time-tracker log` feature.

## Installation

```
npm install -g simple-time-tracker
```

Then add this to your .bashrc/.zshrc

```
simple-time-tracker
```

The first time it will ask you for a path to store the files in.

## Logging

To output your time tracking log, run:

```
simple-time-tracker log
```

## License

MIT
