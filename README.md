`purgecss` for critical css
`cssnano` for css minification
`cwebp` for webp conversion
`trimage` for jpg/png minification

* All text dependencies inlined
* Critical css generated with purgecss
* Optimized font file only 6kb
  * Inlined in base64 data URI to avoid FOUT
* Mobile cropped and optimized header image only 21kb
  * Optimized with webp
  * Fallback to json with compatibility check
* Lazy loaded image placeholders using minimal transparent gif data uri with sizing set for layouting responsive images
* All external resources below header lazy loaded
* rel prefetch for header image resources
* rel dnsprefetch for analytics scripts
