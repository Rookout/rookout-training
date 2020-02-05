# What is Rookout?

Rookout is a debugging and data-collection solution that allows developers to quickly get data and debug apps/services/APIs in real-time, without stopping the application and without impacting its performance. Rookout supports Java (and any JVM based language), Python, Node.js and .NET/C# (Framework and Core).

Rookout will provide you with better visibility into your applications including the ability to:

* Quickly solve complex engineering issues
* Slash your Mean Time To Resolution
* Empower your organization with faster and more reliable delivery processes

# Rookout Workshop

This workshop provides an introduction into Rookout and will cover the following topics:

  * Setting up and configuring the [Rookout SDK](https://docs.rookout.com/docs/setup-intro.html) in an existing application
  * Getting familiar with the Rookout App including things like creating a new project, connecting your application sources, organizations, and configuring labels/filters
  * Setting [Non-Breaking Breakpoints](https://docs.rookout.com/docs/breakpoints.html) and examining Rookout snapshot data from an application
  * Configuring Non-Breaking Breakpoints including [Conditional Breakpoints](https://docs.rookout.com/docs/breakpoints-conditional.html) and Time-to-Live
  * Creating and configuring [Rookout targets](https://docs.rookout.com/docs/integrations.html) including integration with Slack

# Setup and Prerequisites

In order to complete the training, users should have the following:
  
  * An account on GitHub: https://github.com
  * Docker installed locally: https://www.docker.com/get-started
  * An account on Slack: https://slack.com/get-started
  * A Rookout account: https://app.rookout.com/#mode=signUp

  Before starting the workshop, please visit the [Setup page](./setup.md)
   

# Workshop Sections

The Rookout training consists of the following sections:

* Section 1 - [Configuring the Rookout SDK](./configure-rookout-sdk.md)
* Section 2 - [Connecting Sources and Exploring the Rookout App](./sources-rookout-app.md)
* Section 3 - [Projects and Filtering Application Instances](./projects-filters.md)
* Section 4 - [Setting Non-Breaking Breakpoints](./non-breaking-breakpoints.md)
* Section 5 - [Editing Non-Breaking Breakpoints](./editing-breakpoints.md)
* Section 6 - [Configuring Rookout Targets](./targets.md)


# Rookout Use Cases

By integrating the Rookout SDK within your application, you can accomplish the following:

* **Live Debugging**
  * Debug running applications in Production, Staging, and Dev environments real time on the fly using Rookout's Non-Breaking Breakpoints
* **Sustainable Logging**
  * Log only what you need and use Rookout to debug applications live at runtime
* **Data Pipelining**
  * Collect data from live running applications and send it to any external system with an API available including logging or monitoring platforms  
* **Dynamic Alerting and Monitoring**
  * Use Rookout as an effective alert management channel.  Data can be sent to Slack or other systems on demand.
* **On-Demand Pinpoint Profiling**
  * Developers use Rookout to explore areas where they have performance concerns and pinpoint the exact line that impacts performance.
* **Dev Collaboration and Handoffs**
  * Developers can see eachothers work side by side and collaborate real time on issues
* **Dev Training and Onboarding**
  * Rookout allows devs to speed up their learning process by letting them observe unfamiliar code “in the wild”: as it’s running live in its true surroundings.


# How to Contribute
There are two primary ways to contribute or provide feedback:

* Using the issue tracker
* Creating a Pull Request
  * You should fork this repository, make changes in your own fork, and then submit a pull request

