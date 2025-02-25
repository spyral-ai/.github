# Welcome to Spyral 😀

We are building infrastructure for AI. You can see more of what we make at [spyral.ai](https://www.spyral.ai).

## Goals

Our goal is to provide simple, scalable, and efficient infrastructure on top of which AI applications can be built. Our infrastructure will allow anyone to build AI applications quickly and robustly, and deploy them in the most cost-efficient way possible. We believe that AI should be accessible to anyone that has an idea and wants to incorporate AI into it, which is not currently possible. Rather, it is challenging to build sophisticated applications which use AI in multiple ways, and they can be slow and expensive in production.

We believe that open, accessible AI will make the world a better place, and our aim is to both advance the current SOTA in AI while making it accessible to everyone, and use those advancements to create a product which our users love.

We can do this by 1) making ML development (training, inference, and incorporation into a larger application) and deployment simpler and cheaper, and 2) producing novel research and making that available so that people can use it to build amazing things.

## What we are doing

Unfortunately, the reality of today is that AI is gated by formidible barriers to entry. The current state of AI is that only those with vast resources have the means to contibute meaninfully to progress (although this is improving). This concentration of power not only stifles innovation but also perpetuates inequality. We believe that the full potential of AI will help humanity to solve the most important problems and provide immesurable value to people's lives, but that this will only be possible when AI is more accessible. Our version of the future is one in which anyone with a passion for innovation can contribute to the evolution of AI, or use it to solve any problem in their own lives - a future where the benefits of this technology are shared by all.

To make this a reality, we are building the infrastructure to reduce the prohibitive costs and complexity that currently gatekeep innovation. Our platform and tools will empower even small teams to train and deploy cutting-edge models at a fraction of the current cost and then to swiftly transition prototypes into production grade systems that create value for end users (or use them for research). We believe that such an infrastructure will utilize the collective potential of the global community, rather than the current few collections of well-resourced companies, and push AI and science towards its highest potential.

Ultimately, we aim to provide the following to AI scientists and app builders:

- **Simplicity:** Training or inference on hundreds to thousands of devices is very challenging. We abstract all of the details of distributed exection so that for the user, developing and debugging on thousands of devices is just as simple as on one. For inference, using a model will be as simple as adding a few lines of code, and can be used on device or on a server, depending on the local device capability.

- **Accessibility (cost-effectiveness):** Intially, we will reduce the cost of training by enabling distributed training across failable, but cheaper, more available, and possibly heterogeneous, devices. For both training and inference, we are able to determine when compute performed by one user doesn't fully saturate the device, in which case we can use the device for multiple users, making it cheaper for both without decreasing performance.

- **Performance:** In addition to being the simplest and cheapest solution, we are also the most efficient solution, which compounds the above factors.
