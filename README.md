## DataWave Spring Boot Starter for Caching

This starter provides customization of all the default spring boot cache configuration types.
The only real difference over the default Spring Boot behavior is that the created cache
manager beans are annotated with `@Primary` so that they will be used by default. This starter
can be used when other named cache managers are created that are intended to be different from
the built-in Spring cache management.