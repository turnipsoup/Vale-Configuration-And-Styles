# Vale Styles And Configuration For Writing Better At Work

## Summary

[Vale](https://vale.sh) acts as a linter for prose. Its used to help you keep your writing consistent.

## How To Use
MacOS: `brew install vale`

## Setup And Configuration
Clone this repository into `$HOME/.vale-styles`. Then copy the configuration into your home: `cp $HOME/.vale-styles/.vale.ini $HOME`

## Use
```
jheckt-mbp-bv :: ~ % vale .vale-styles/README.md

 .vale-styles/README.md
 5:25  suggestion  Try to avoid using 'is'.        write-good.E-Prime
 5:48  warning     'It is' is too wordy.           write-good.TooWordy
 5:51  suggestion  Try to avoid using 'is'.        write-good.E-Prime
 5:51  warning     'is used' may be passive        write-good.Passive
                   voice. Use active voice if you
                   can.

✖ 0 errors, 2 warnings and 2 suggestions in 1 file.
```

## Notes on Styles
I have included two styles in this repository. The license for each style exists in their respective directory, we do not claim any of that work as our own.
