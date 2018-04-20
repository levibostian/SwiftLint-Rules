# SwiftLint-Rules

[SwiftLint](https://github.com/realm/SwiftLint/) Rules! It is a very useful project that I use in my Swift projects. It is a great lint tool to help catch bugs for you during compile time. 

![SwiftLint is awesome gif](rules.gif)

# How do I use this repo?

SwiftLint is not very good at this time at merging configuration files at this time (check out [this issue](https://github.com/realm/SwiftLint/issues/1889) and [this issue](https://github.com/realm/SwiftLint/issues/1815)). So, the only way to use these rules in your Swift project at this time is to copy and paste the text in the `.swiftlint.yml` files in this repo and paste them in your own project's `.swiftlint.yml` file.

# Rules

Rule to catch when you use `self.addSubView()` instead of `self.contentView.addSubView()` in a subclass of `UITableViewCell`.

* [use_contentview_tableviewcell](use_contentview_tableviewcell/.swiftlint.yml)

