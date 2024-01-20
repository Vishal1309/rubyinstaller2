## RubyInstaller-3.3.0-1 - 2023-12-26

This is the first release based on ruby-3.3.0: https://www.ruby-lang.org/en/news/2023/12/25/ruby-3-3-0-released/

### Changes compared to [RubyInstaller-3.2.2-1](CHANGELOG-3.2.md#rubyinstaller-322-1---2023-04-01)

- Remove the `.irbrc` file previously generated by RubyInstaller versions before 3.3.0.
  It is no longer necessary, since the enabled extensions have been made defaults in ruby core.
- Return registry strings as UTF-8 instead of OEM charset. [#348](https://github.com/oneclick/rubyinstaller2/issues/348)
- Update the SSL CA certificate list and to OpenSSL-3.2.0.