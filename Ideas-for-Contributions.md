These are some of the ideas for contributing to Orleans. Just an initial list for consideration, meant to be a live document. If you are interested in any of these or one that is not listed, create an issue to discuss it.

We roughly put them into 3 size categories based on our gut feel, which may be wrong: 
 * Small - hours of work
 * Medium - couple of days of work
 * Large - big projects, multiple days up to weeks of work

1. **Project template/wizard for Azure deployment** [Medium/Large]
  * Worker role for silos (in our experience it is better to star a silo as a standalone process and wait on the process handle in the worker roles code)
  * Worker/web role for frontend clients
  * Configuration of diagnostics, ETW tracing, etc.
  * Try Azure SDK plug-in as suggested [here](http://richorama.github.io/2015/01/13/thoughts-on-deploying-orleans/) by @richorama.

2. **Migrate system storage from Azure SDK 1.7 version to 2.5.** - DONE

3. **Add support for [Bond](https://github.com/Microsoft/bond)/[Avro](http://avro.apache.org/)/other serialization** [Medium/Large]
  * One way to support Bond is to allow to use it optionally in addition to the built-in Orleans-generated serializers, similar to custom serializers. That way code that already uses Bond could work with Orleans.
  * The solution will probably need to add a message header to indicate serializer used
  * Will be less automatic than the built-in option but compatible with non-.NET clients
  * Explore other ways to use Bond.

4. **Refactor code generation to use [Roslyn] (https://github.com/dotnet/roslyn) instead of CodeDOM** [Medium/Large]

5. **Cluster monitoring dashboard** [Medium]
  * https://github.com/OrleansContrib/OrleansMonitor may be a good start

6. **Migrate and update samples from [Codeplex] (https://orleans.codeplex.com/wikipage?title=Samples%20Overview&referringTitle=Documentation)** [Small/Medium]

7. **Migrate documentation from Wiki to HTML-based solution (GitHub pages)** [Small/Medium]

8. **Make system storage fully pluggable, so that we support more than Azure Table and SQL** [Medium/Large]

9. **Proper support for F#** [Medium/Large]

10. **Support for dependency injection** [Medium]

11. **Orleans backplane for SignalR** [Medium]