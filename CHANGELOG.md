# TOML Changelog

## HEAD

* Specify that zeros (Integer 0 and float 0.0) cannot have a sign (+ or -).
* Rename Datetime to Offset Date-Time.
* Add Local Date-Time.
* Add Local Date.
* Add Local Time.
* Add ABNF specification.
* Allow accidental whitespace between backslash and newline in the line
  continuation operator in multi-line basic strings.
* Specify that .toml is the standard file extension.
* Clarify that U+007F is an escape character.
* Clarify that keys are always strings.
* Clarify that you cannot use array-of-table to append to a static array.
* Clarify that a TOML file must be a valid UTF-8 document.
* Clarify what are valid Array values.
* Clarify that literal strings can be table keys.
* Clarify that at least millisecond precision expected for Date-Time and Time.
* Clarify that comments are OK in multiline arrays.
* TOML has a logo!

## 0.4.0 / 2015-02-12

* Add Inline Table syntax.
* Allow underscores in numbers.
* Remove forward slash as an escapable character.
* Unicode escapes must be scalar values.
* Newline is now defined as LF or CRLF.

## 0.3.1 / 2014-11-11

* Fix incorrect datetime examples.

## 0.3.0 / 2014-11-10

* Add scientific notation for floats.
* Allow optional + prefix on integers.
* Switch to RFC 3339 for datetimes (allowing offsets and fractional seconds).
* Add multiline and literal strings.
* Clarify what characters valid keys can contain.

## 0.2.0 / 2013-09-24

* Use "table" instead of "key group" terminology.
* Add the ability to define nestable arrays of tables.

## 0.1.0 / 2013-03-17

* From Twitter rage to reality; TOML is now a thing.
* First proper release.
* TOML adheres to the SemVer standard for version numbers.
