# React JS Conf Proposal

## Talk Title
Distributed Tracing: From Browser to Services

## Talk Description

This talk details how our teams leverage Flux patterns to automatically instrument our code, providing insights into user behaviors and application performance. Distributed tracing refers to the Google Dapper whitepaper (http://research.google.com/pubs/pub36356.html), which captures how user activity is processed by a distributed system. We've extended this idea to the client side, where a trace starts with a user action in the browser. We record and visualize how the action is processed by UI components in the browser and coordinated with requests to services.

This visualization shows us where our application is suffering from poor response times and low frames-per-second rendering. The Flux Application Architecture provides consistent patterns for instrumenting our applications, so we can understand the impacts of code changes without having to instrument everything ourselves.

I'll show some code examples of how we instrument our application with Redux, though these methods apply to other Flux implementations. I'll also show how we visualize traces using our homegrown application, Hugo. Here's an example screenshot: https://raw.githubusercontent.com/pbomb/reactjsconf/master/proposal/hugo_teamplan.png. Above all, I’ll share the incredible value of distributed tracing, and how we can apply it using Flux for a complete understanding of our application’s performance.
