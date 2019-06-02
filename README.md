# 👷 `worker-template` curl

A Cloudflare worker template that intercepts requests from `curl` command and returns something different. Can be useful for showing a special response for developers, or showing a cool developer card 😎

## Example

`curl gafi.dev`


![card example](https://raw.githubusercontent.com/gaafar/curl-worker/master/screenshot.png)

## Wrangler

To generate & deploy using [wrangler](https://github.com/cloudflare/wrangler)

```
wrangler generate myApp https://github.com/gaafar/curl-worker
```
