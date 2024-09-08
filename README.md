### Mapinguatech Design System
This is one part of my own tech stack for personal projects, this tech stech is composed of:

### Design System
Design system Maintain cohesion of design/ui through my projects and redy to use components to use in any projects. Any new component that is needed will also be added to the design system for tuture use.

### Server
Server Basic integration of a server without business rules and processes, mostly sync processing and db integration. It will handle basic auth and observability 
out of the box, i am assuming every project will need at least that. If i see the need along the way the improvements will be implemented in the core server if it is not 
a business rule, that way i can guarantee it is evolving but not holding complexity based on product, remaining a core implementation for generic use.

### Worker/Consumer

Simple implemention of a worker/consumer that will be used to process assincronous tasks, usually tasks that take more resources and can be deferred to a worker. 
It will have basic security and observability implementations out of the box. It will use rabbitmq as message broker. Will be improved over time from the same concept of core service.


### Useful Commands for this repo

- `pnpm build` 
- `pnpm dev` 
- `pnpm lint` 
- `pnpm changeset` 
- `pnpm clean` 

Will open storybook on port 6006


```bash
Local:  http://localhost:6006/ 

```

### Links for the other repos in the tech stack

- [worker/consumer](https://github.com/caiocampoos/a-simple-consumer-rust)
- [Server]() `soon`
