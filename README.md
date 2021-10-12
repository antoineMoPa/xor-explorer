# xor-explorer

If you code, you may know about bitwise operator XOR and AND (respectively ^ and &  in C, C++, Js, etc.). You probably also know about the modulus operator, which gives the remainder of the division (% in C, C++, Js, etc.).

With a simple expression combining these, you can create quite complex visuals. I put up a github page some time ago to tests these formula:  https://antoinemopa.github.io/xor-explorer/

Under the hood, it compiles your expression in a GLSL shader and renders is in realtime. You can zoom and drag to explore the generated surface.
