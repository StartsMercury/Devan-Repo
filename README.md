# Devan-Repo

Fork of [Devan-Kerman]'s maven repo as part of an effort to restore "lost" versions of [ARRP], specifically `(0.4.2,0.6.2)` and probably `0.6.3` and `0.6.5`.

## Usage

### Kotlin DSL

```kotlin
repositories {
    maven {
        url = uri("https://raw.githubusercontent.com/StartsMercury/Devan-Repo/master/)
    }
}

```

### Groovy DSL

```groovy
repositories {
    maven {
        url = 'https://raw.githubusercontent.com/StartsMercury/Devan-Repo/master'
    }
}

```

[ARRP]: https://github.com/Devan-Kerman/ARRP
[Devan-Kerman]: https://github.com/Devan-Kerman
