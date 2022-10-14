<!-- https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#specifying-the-theme-an-image-is-shown-to -->

<picture>
  <source media="(prefers-color-scheme: dark)" srcset=".github/images/dd_logo_h_white.svg?raw=true" width="100%" height="100" alt="Datadog Logo">
  <img src=".github/images/dd_logo_h_rgb.svg?raw=true" width="100%" height="100" alt="Datadog Logo">
</picture>

# Datadog for IntelliJ IDEA

The [Datadog](https://plugins.jetbrains.com/plugin/19495-datadog) plugin helps improve software performance by providing
meaningful code-level insights in the IDE
based on real-time observability data. It helps reduce application latency and lower cloud costs by highlighting
specific code lines that consume the most CPU, allocate the most memory and spend the most time on locks, disk I/O,
socket I/O, and more.

> DISCLAIMER
> 
> This is a **Public Beta** version of the Datadog plugin, intended for Datadog customers that use the [Continuous Profiler](https://docs.datadoghq.com/profiler/#pagetitle) for their Java Services.

### Features

- Top List to identify the methods that consume the most resources
- Flame Graph visualizes the aggregated profile data
- Find resource consumption broken down by method name and line number
- Insights available from various staging and production environments


### Getting Started

#### Step 1: Authenticate Datadog Credentials
Click on the `Datadog` tab at the bottom of the screen to open the plugin tool pane window. Click on ‘Add your
credentials...’ and then enter your Datadog credentials. You will need the following information:

- Name of your Datadog Site. Find your Datadog Site [here](https://docs.datadoghq.com/getting_started/site/)
- A pair of keys: an application key to identify the organization and an API Key to identify the user. For more information on the keys, go [here](https://docs.datadoghq.com/account_management/api-app-keys/).

#### Step 2: Link Service(s)
After you have authenticated your credentials, you can proceed to link one or more services to your project.

### Help and Feedback
Checkout the [documentation](https://docs.datadoghq.com/developers/ide_integrations/idea/) to see more information about the
Datadog IntelliJ Plugin. For any feedback reach out to us via the [issue tracker](https://github.com/DataDog/datadog-for-intellij/issues) or send an email to team-ide-integration@datadoghq.com
