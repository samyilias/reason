
## 3.0.0

TODO: re-enable rtop integration tests in makefile (./miscTests/rtopIntegrationTest.sh) before the release

- Even better infix operators formatting for `==`, `&&`, `>` and the rest (#1380, #1386)
- Removed `--add-printers` option from refmt; we'll have a better strategy soon.
- Remove unused binaries: `reup`, etc.
- Remove the old `reactjs_jsx_ppx.ml`. You've all been on `reactjs_jsx_ppx_2.ml` for a long time now.
- Remove `--add-printers` from `refmt`. The feature wasn't stable enough; we'll find a better way soon. Sorry about that!
- New syntax based on (but not entirely) #1299
- BuckleScript's `Js.t {. foo: bar}` now formats to `{. "foo": bar}`, just like its value counterpart (`[%bs.obj {foo: 1}]` to `{"foo": bar}`.
