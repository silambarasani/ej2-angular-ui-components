# Changelog

## [Unreleased]

## 16.4.44 (2018-12-24)

### TreeGrid

#### Bug Fixes

- Expanding and Collapsing records is working fine when `pageSizeMode` is set as `All`.
- `expandAtLevel`, `collapseAtLevel`, `expandAll` and `collapseAll` methods are working fine when `pageSizeMode` is set as `All`.


- `actionBegin`, `actionComplete` and `actionFailure` events are triggered properly.
- Additional parameters that are added using the `query` property of TreeGrid are passed to the server side when a parent record is expanded.


