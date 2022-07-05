<!-- https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#specifying-the-theme-an-image-is-shown-to -->

<picture>
  <source media="(prefers-color-scheme: dark)" srcset=".github/images/dd_logo_h_white.svg?raw=true" width="100%" height="100" alt="Datadog Logo">
  <img src=".github/images/dd_logo_h_rgb.svg?raw=true" width="100%" height="100" alt="Datadog Logo">
</picture>

# Datadog for IntelliJ IDEA

Enables developers to interact with [Datadog](https://www.datadoghq.com/) services while working on Java projects. Features include:

### Profiling
- aggregated [profiling](https://docs.datadoghq.com/tracing/profiler/) data helps developers remove costly bottlenecks in code
- a **Top List** showing methods consuming the most resources
- an **Icicle Graph** visualisation of the aggregated profile data
- direct links from the profiling visualisations to the source code in the editor

### Tracing
- [custom instrumentation](https://docs.datadoghq.com/tracing/setup_overview/custom_instrumentation/) via context actions, code surround and live templates, plus a list of custom instrumentation points in the current project
- display of trace metrics for services associated with the current project, resources within a service and tagged resources in the source code editor (`@Trace` annotations, spans and `dd:trace` comment tags)



[User Guide](https://musical-spork-b9da1bce.pages.github.io/)