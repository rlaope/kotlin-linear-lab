# Kotlin Linear Algebra Core 🧩

Lightweight Kotlin library for matrix and vector operations.

- Pure Kotlin, extensible and easy-to-read
- `Matrix`, `Vector`, dot product, norms, system solvers

## Example

```kotlin
val A = Matrix.of(2, 2, listOf(1.0, 2.0, 3.0, 4.0))
val b = Vector.of(2, listOf(5.0, 6.0))
val x = A.solve(b)
