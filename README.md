# Example - Wasmbuild w/ WebGPU - Hello Triangle

The `wgpu` "Hello Triangle" example extracted out and built with Wasmbuild:

https://github.com/gfx-rs/wgpu/tree/trunk/examples/src/hello_triangle

## Setup

1. Install [Deno](https://deno.land).
2. `deno task build`
3. Start a file server:
   `deno run --allow-read=. --allow-net https://deno.land/std/http/file_server.ts`
4. Open http://localhost:4507 in a browser.

## TODO

- Deno example (only works in a browser atm)
