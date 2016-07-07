---
title: "Wrapping up boids & flocking patterns"
slug: wrapping-up
---

Nice job! You just implemented your own swarm intelligence for fish (also known as boid behavior)!

![Final flocking fish](./final.gif)

Now you have some time to play around with the weights and distances.

> [challenge]
>
> The weights we have work well enough but it does take some time for the fish to cluster into coherent "schools". Can you re-weight the values and make them school together faster?

# More resources

In this tutorial we covered a few mathematical concepts and basic, "boid"-style artificial intelligence.

We covered:

- Points in two-dimensional space
- Vectors in two-dimensional space
- The difference between speed and velocity
- How simple rules (cohesion, separation, alignment) can create emergent, complex behavior

## Some other boid-style things to check out

- Batman Returns (1992) used boids for movement of [bats](https://www.youtube.com/watch?v=jCVwdeAobYc) and [penguins](https://www.youtube.com/watch?v=Mo_1rAaj7FE)
- The Lord of the Rings franchise used [MASSIVE](https://en.wikipedia.org/wiki/MASSIVE_(software)) for it's large fight scenes. It has since been in numerous movies and TV shows. If you see a large, computer generated crowd in a movie, it's probably orchestrated with MASSIVE. Check out their professional [demo reel](https://www.youtube.com/watch?v=cr5Cwz-5Wsw) and this [real time battle sequence](https://www.youtube.com/watch?v=3FuahvrXNkk). They've even combined what we learned in this project and in the cruise control project to [simulate traffic](https://www.youtube.com/watch?v=x4oWEz0G1f8).
- Boid-style algorithms can even model opinions propagating through social networks! It is not limited to just movement. Any system of individual "agents" (fish in our case) that change their properties based on those around them can be simulated with boids. This [article](http://www.gamasutra.com/view/feature/130232/modeling_opinion_flow_in_humans_.php) is a bit of a long read, but very interesting if you want to see how it's done.
