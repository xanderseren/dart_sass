# CHANGELOG

## v0.3.1

  * Update Sass version to `1.43.4`
  * Allow `config :dart_sass, :sass_path, path` to configure the path to the Sass snapshot (or executable)
  * Allow `config :dart_sass, :dart_path, path` to configure the path to the Dart executable
  * Support OTP 24 on Apple M1 architectures (via Rosetta2)

## v0.3.0 (2021-10-04)

  * Use Rosetta2 for Apple M1 architectures until dart-sass ships native
## v0.2.1 (2021-09-23)

  * Apply missing `--runtime-config` flag check to `mix sass.install`

## v0.2.0 (2021-09-21)

  * No longer load `config/runtime.exs` by default, instead support `--runtime-config` flag
  * Update initial `sass` version to `1.39.0`
  * `mix sass.install --if-missing` also checks version

## v0.1.2 (2021-08-23)

  * Fix target detection on FreeBSD (h/t @julp)
  * Extract archive with charlist cwd option (h/t @michallepicki)

## v0.1.1 (2021-07-30)

  * Fix installation path/unzip on windows
  * Add wrapper script to address zombie processes

## v0.1.0 (2021-07-25)

  * First release
