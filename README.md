# dvo/cliargs
dvo/cliargs is a simple piece of code used to interpret arguments given to NodeJS as key/value pairs. It will basically output arguments such as
`node script.js alpha beta -charlie delta --echo foxtrot`
into an object
```
cliargs = {
 "alpha":true,
 "beta":true,
 "c":true,
 "h":true,
 "a":true,
 "r":true
 "l":true,
 "i":true,
 "e":"delta",
 "echo":"foxtrot"
}
```
The script was first wrote as an answer to a [stackoverflow question](https://stackoverflow.com/questions/4351521/how-do-i-pass-command-line-arguments-to-a-node-js-program/54870766#54870766), but as I proceed to actually use it, it was simpler to add it to npm.
