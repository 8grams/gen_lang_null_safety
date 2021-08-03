# gen_lang with Null Safety

Copied and modified from [https://github.com/dpr10/gen_lang](https://github.com/dpr10/gen_lang)

This repository is created to add support for Null Safety in [gen_lang](https://github.com/KingWu/gen_lang)

## Usage

Add the library under `dev_dependencies` in `pubspec.yaml`

```

dev_dependencies:
	// other libraries
    gen_lang:
        git:
          url: git://github.com/8grams/gen_lang_null_safety.git
          ref: master
```

Update packages

```
~$ flutter pub get
```