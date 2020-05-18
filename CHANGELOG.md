# [1.0.7](https://github.com/gskbyte/GSKStretchyHeaderView/releases/tag/1.0.6)

Fixes

# [1.0.6](https://github.com/gskbyte/GSKStretchyHeaderView/releases/tag/1.0.6)

Fixes

# [1.0.5](https://github.com/gskbyte/GSKStretchyHeaderView/releases/tag/1.0.5)

Added static mode to skip frame changes if needed

# [1.0.4](https://github.com/gskbyte/GSKStretchyHeaderView/releases/tag/1.0.4)

- [Fix zPosition change issues](https://github.com/gskbyte/GSKStretchyHeaderView/pull/82)

Thanks @abotkin-cpi!

# [1.0.3](https://github.com/gskbyte/GSKStretchyHeaderView/releases/tag/1.0.3)

- [Fix layout guides crash on iOS 11](https://github.com/gskbyte/GSKStretchyHeaderView/pull/71)

# [1.0.2](https://github.com/gskbyte/GSKStretchyHeaderView/releases/tag/1.0.2)

- [Fix device rotation issue](https://github.com/gskbyte/GSKStretchyHeaderView/pull/65)
- [Add Xcode 9 support](https://github.com/gskbyte/GSKStretchyHeaderView/pull/64)
- [Fix contentInset and view hierarchy issues with iOS 11](https://github.com/gskbyte/GSKStretchyHeaderView/pull/68)

Thanks [@julienpouget](https://github.com/julienpouget)!

# [1.0.1](https://github.com/gskbyte/GSKStretchyHeaderView/releases/tag/1.0.1)

- [Fixed crash when removing header from a superview without window](https://github.com/gskbyte/GSKStretchyHeaderView/pull/53). 

Thanks [@ojcarcete](https://github.com/ojcarcete)!

# [1.0.0](https://github.com/gskbyte/GSKStretchyHeaderView/releases/tag/1.0.0)

- After a few months without changes or critical errors found, we have marked the library as stable. Enjoy!

# 0.12.2

- Add the possibility to disable changing the scroll view `contentInset` automatically
- Optimise the arrangement of the header view inside the scroll view

# 0.12.1

- Fix crash when removing from scroll view

# 0.12.0

- Remove dependency on `KVOController``
- Remove test dependencies on `Expecta` and `OCMock`
- Create library project to generate a framework
- Support [Carthage](https://github.com/Carthage/Carthage)
- Support test coverage display via [Coveralls](https://coveralls.io)

# 0.11.0

- **New functionality**: add [new mode](https://github.com/gskbyte/GSKStretchyHeaderView/blob/master/Pod/Classes/GSKStretchyHeaderView.h#L64) for immediate expansion when scrolling down. Showcased in the examples *With tabs*, *From a XIB file* and *Scalable Text*)
- Improved how the header view is rearranged inside the scroll view: it won't cover the scrollbars anymore
- Rename `contentBounces` to `contentExpands`
- Rename `contentStretches` to `contentShrinks`
- Refactor layout code: stretchy header frame is configured in the scrollview

# 0.10.0

- Move `UIView+GSKLayoutHelper` to the example project, because its functionality shouldn't belong to the library and the method names may collide with others
- Add a new example resizing a `UILabel`

# 0.9.0

- Simplify internal code thanks to [`KVOController`](https://github.com/facebook/KVOController)
- Add lots of tests (coverage **above 94%**)
- Add Twitter example
- Fix a couple of smaller issues

# 0.8.2

- Make stretchy header view stay always on top, so that section headers and footers do not overlap it.

# 0.8.1

- `contentInset` recalculation bugfixes
- Add airbnb-like example

# 0.8.0 Improved API

- Add new anchorMode
- Add `contentInset` property
- Add code documentation
- Unify stretchFactor properties

# 0.7.0 Initial version

- Initial working version
