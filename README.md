<!-- tyhp-readme:start -->
# tyhpdef/spatie-laravel-activitylog

Tyhp type definitions for `spatie/laravel-activitylog` `5.1.1`.

```bash
composer require --dev tyhpdef/spatie-laravel-activitylog:5.1.1
```

This is a metapackage. Composer also installs `tyhpdef/spatie-laravel-activitylog-impl` (type files).
Require **this** name, not `tyhpdef/spatie-laravel-activitylog-impl`.

See https://tyhplang.com.

## Maintain `spatie/laravel-activitylog`? Ship the types yourself

If you are a Packagist maintainer of `spatie/laravel-activitylog`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/spatie-laravel-activitylog-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `spatie/laravel-activitylog` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/spatie-laravel-activitylog": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `spatie/laravel-activitylog` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `spatie/laravel-activitylog` with a real constraint,
   `"replace": { "tyhpdef/spatie-laravel-activitylog": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `spatie/laravel-activitylog` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/spatie-laravel-activitylog` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
