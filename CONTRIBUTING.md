## Contributing code via PR

Code contributions are welcome, particularly bug fixes and enhancements!  `Pull 
Requests` will be considered with the following criteria:

1. Must pass both `npm test` and `wintest` tests
2. Should make every effort meet or exceed current code coverage level
3. Must respect and align to Project Principles (see [README.md](https://github.com/mseminatore/TeslaJS/blob/master/README.md))
4. Must add general value to the project
5. Must update appropriate documentation
6. New functionality should be demonstrated in a new or updated sample

> Note that the Project owners reserve the right to accept or reject any PR
> for any reason.

## Filing Issues

Useful bug reports include the following:

* Version of the library used (ideally the latest published version)
* Clear set of steps used to reproduct the issue
* Code examples if appropriate

## Testing
A apiary mock can be used, for instance:

```
export TESLAJS_SERVER=http://private-111a5-teslajs.apiary-mock.com
export TESLAJS_STREAMING=http://private-111a5-teslajs.apiary-mock.com
```

## Running Mocha
`./node_modules/.bin/istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec`
