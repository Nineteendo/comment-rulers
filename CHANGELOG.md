# Change Log

All notable changes to the "comment-rulers" extension will be documented in this file.

## 1.0.0 (Apr 14. 2023)

- Initial release

## 1.0.1 (Apr 14. 2023)

- Fixed Multi-line comments are messed up

### 1.0.2 (Apr 16. 2023)

- Detecting strings (to ingore included comment delimiters).
- Escaping delimiters
- Fixed features.gif

### 1.0.3 (Apr 16. 2023)

- Fixed ruler misplaced by using transparent underscores (color can be modified)
- Fixed that block comments can be terminated by part of the first delimiter
- Removed backtick from escapableChars, added backslash
- Removed backtick from singleLineStringDelimiters
- Added green background color to rulers (color can be modified)
- Renamed style to border

### 1.0.4 (Apr 16. 2023)

- Fixed that block comments can be started by part of the second delimiter
- Made placeholder configurable

### 1.0.5 (Apr 18. 2023)

- Made end delimiters of strings configurable
- Added ruler where the comment line should start
- Added examples
- Added default configuration for top 20 most popular programming languages
- Added comments tests for top 20 most popular programming languages