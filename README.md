# gatkinso/homebrew-tap

Homebrew formulae for [skywire](https://github.com/gatkinso/skywire):
`wiregen`, which generates C, C++, C#, Go, Java, JavaScript, Python, Rust and
Swift for fixed-layout binary messages, with JSON, XML, BSON and protobuf, and
the C and C++ runtime headers.

```sh
brew install gatkinso/tap/skywire
wiregen --version
```

For Apple silicon Macs. On Linux and Windows, use the
[release archives](https://github.com/gatkinso/skywire/releases/latest), which
need nothing else installed.

`Formula/skywire.rb` installs a release archive as it is, and is generated
for each release by skywire's
[`packaging/homebrew/make_formula.py`](https://github.com/gatkinso/skywire/tree/master/packaging/homebrew).
Report problems with it at https://github.com/gatkinso/skywire/issues.
