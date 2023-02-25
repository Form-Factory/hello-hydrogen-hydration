This is a temporary fix to alleviate the hydration problems caused by client-side DOM manipulation by 3rd party scripts / extensions that can cause Styled Components to fail on React 18.2 flavors of Remix.

Based on [@kiliman's](https://github.com/kiliman) [initial fix](https://github.com/remix-run/remix/discussions/5244#discussioncomment-4832036), wrapped into [remix-island](https://github.com/Xiphe/remix-island) by [@Xiphe](https://github.com/Xiphe) and [adapted for readableStreams](https://github.com/remix-run/remix/discussions/5244#discussioncomment-4890083) by [@clgeoio](https://github.com/clgeoio)

More information:
- https://github.com/remix-run/remix/issues/5569
- https://github.com/remix-run/remix/discussions/5244
- [Remix Roadmap Discussion](https://www.youtube.com/live/tdVFZidXGZo?feature=share&t=2972)
- https://github.com/facebook/react/issues/24430
