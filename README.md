# Minimg
This is a minimal library that enables output of RGBA png images. The colour type is a Vec4.
Example

```
fn main() {
    let mut buf = ImageBuffer::new(512, 512);
    buf.set(69, 420, vec4(1.0, 0.0, 0.0, 1.0));
    buf.dump_to_file("test.png");
}
```