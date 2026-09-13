# Scoop Bucket for Datara & Forgen

Official Scoop bucket for the [Datara Programming Language](https://github.com/datara-lang/datara) and the Forgen native compiler.

## Installation

`powershell
scoop bucket add datara https://github.com/datara-lang/scoop-bucket.git
scoop install datara
`

Or install directly from the manifest URL:

`powershell
scoop install https://raw.githubusercontent.com/datara-lang/scoop-bucket/main/bucket/datara.json
`

## Verify Installation

`powershell
forgen --version
datara --version
`
