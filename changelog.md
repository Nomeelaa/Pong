# Changelog

# [1.0.0] - 2023-01-28
### Added
- In "update_pong" added a sequence of "if/else" to simulate an simple AI player.
- In "Settings" file added macro MID_LINE_HEIGTH for set heigth of mid line.
- Create "draw_table" function to print the mid line, ball and score.

### Changed
- The solid mid line in function "render_pong" was updated by a broken line.
- When draw the table it is only occurs in "PLAY", "SERVE" and "DONE" state.
- Split the draw of table and score into a new function.
