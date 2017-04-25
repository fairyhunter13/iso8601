# iso8601
A fast ISO8601 date parser for Go

## Background

Whilst working with dates, especially with API communication the default `RFC3339` time layout is too restrictive to support the wide range of dates supported in the ISO8061 specification.

This library is intended to work with any date from any language that follows the ISO8601 specification.

## Performance

This library is fast with no allocations needed to parse a full date.

    BenchmarkParse-8        20000000               106 ns/op               0 B/op          0 allocs/op
