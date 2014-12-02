# GLSL Arbitrary Floating-Point Precision

A mini-library for performing arbitrary-precision arithmetic in OpenGL ES Shader Language.

```glsl
void main() {
	int a[vals];
	a[vals-1] = 394;
	a[vals-2] = 286;
	// ...

	int b[vals];
	zero(b, vals);
	b[vals-1] = 864;
	b[vals-2] = 397;
	// ...

	add(a, b);
	int sum[vals];
	assign(sum, result);

	mul(a, b);
	int prod[vals];
	assign(prod, result);
}
```
