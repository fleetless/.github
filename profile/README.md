# fleetless

ROS 2 robots as an API for your app, your users and their AI.

A robot runs one bridge package and connects outward. You choose in the console
what it exposes and which role may do what. Your app reaches it through a REST
and realtime API or the TypeScript SDK, your users' AI through an MCP server.
All three ask the same roles.

| Repository | What |
|---|---|
| [bridge](https://github.com/fleetless/bridge) | the ROS 2 package on the robot (Humble, Jazzy, Lyrical) |
| [sdk](https://github.com/fleetless/sdk) | `@fleetless/sdk`, TypeScript |
| [contracts](https://github.com/fleetless/contracts) | `@fleetless/contracts`, what goes over the wire |
| [app-starter](https://github.com/fleetless/app-starter) | a template app to start from |
| [turtle-sim](https://github.com/fleetless/turtle-sim) | a simulated robot in one Docker image, for when the real one is busy |

[Docs](https://docs.fleetless.dev) · [fleetless.dev](https://fleetless.dev) · [Status](https://status.fleetless.dev)
