# Profile assets

The profile uses local SVGs for its banners and badges, so these graphics do not depend on a badge service at render time. Keep this directory alongside the root README.

- `banner.svg` is the animated desktop banner; `banner-mobile.svg` is selected by the README's `<picture>` element at widths up to 600px. Both respect reduced-motion preferences.
- `stack-*.svg` use cyan for languages, lavender for data, amber for databases, and mint for developer tools.
- Social and coding-profile badges are linked from the root README. Their text and icons are self-contained, with accessible titles and alternative text.

Technology, Instagram, LeetCode, and Codeforces icon paths come from [Simple Icons](https://github.com/simple-icons/simple-icons), distributed under [CC0-1.0](https://github.com/simple-icons/simple-icons/blob/develop/LICENSE.md). Brand names and marks belong to their respective owners. The LinkedIn and email symbols are drawn locally.

GitHub statistics and the contribution snake remain dynamic external images. Their links live in the root README; no activity counts are hardcoded in these assets.
