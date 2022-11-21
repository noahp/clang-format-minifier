# clang-format-minifier

> NOTE this is hard-coded to only handle a single Cpp Language section today!

From a custom `.clang-format` file, generate the minimum set of differences from
one of the `clang-format` base configs ("LLVM", "GNU", "Google", "Chromium",
"Microsoft", "Mozilla", "WebKit").
