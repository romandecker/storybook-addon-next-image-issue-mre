# MRE for showcasing an issue with storybook-addon-next, and next/image at next v12.1.5

To reproduce the issue:

1. `npm install`
2. `npm run storybook`
3. Open http://localhost:6006/?path=/story/example-image--example-story-with-next-image

Note that if you change the version of `next` in `package.json` to `v12.1.4`, and re-run `npm install` and `npm run storybook`, it will work.
