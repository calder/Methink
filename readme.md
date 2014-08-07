# Methink

A MySQL to RethinkDB migration script.


## Usage

Migrate a single table:
```
mysql2rethink -h 'localhost' -u 'boozeallen' -p 'password123' -d 'prism' -t 'us_citizens' -D 'prism' -T 'us_citizens'
```

Migrate all tables:
```
mysql2rethink -h 'localhost' -u 'boozeallen' -p 'password123' -d 'prism' -D 'prism'
```


## Contribute

Please! =)


## License

Methink is released under the public domain.

The original structure was based on [Yeoman](http://yeoman.io) which is licensed under the [BSD license](http://opensource.org/licenses/bsd-license.php) and copyright Google.
