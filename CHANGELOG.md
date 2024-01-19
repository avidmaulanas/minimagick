We keep the changelog in [GitHub releases](https://github.com/minimagick/minimagick/releases).

Added new tmpdir configuration, which defaults to Dir.tmpdir

```rb
MiniMagick.configure do |config|
  config.tmpdir = File.join(Dir.tmpdir, "/my/new/tmp_dir")
end