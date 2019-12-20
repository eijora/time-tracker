# Simple Commandline Time Tracker

## What is it?

Every time I open my terminal, if there is missing time in my time tracking, time-tracker asks me what I did:

![](https://i.cloudup.com/gyb_fTR0Ep-3000x3000.png)

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
