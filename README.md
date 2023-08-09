# Muddle


## What
A web based multi-tool for Base64 Transcoding, URL Encoding/Decoding, MD5/SHA1/SHA256/HMAC hasing and some other ish.

## Why?
Because I don't want what I enter for obsfucation to end up on some random _"special"_ server. This has no DB and is a purely static.

## Build Commands

`$ bundle exec rackup -s puma -p 6969 config.ru`

The app can now be accessed on http://localhost:6969/