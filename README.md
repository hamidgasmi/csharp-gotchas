# C# Gotchas
A collections of some C# gotchas, tips and tricks found around the internet

## Castle.Windsor
- Watch for dependencies that have different lifetime
- E.g. a singletons cache that depends on a dependency that is `PerWebRequest`
