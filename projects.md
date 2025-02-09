# My Projects

## [I Beat Rock](https://github.com/cameroncuster/I_beat_rock)

[@camc on the leaderboard](https://www.whatbeatsrock.com/leaderboard-all)

Developed a strategy and implemented a bot to play [What Beats Rock](https://www.whatbeatsrock.com/), overcoming unique challenges:

- **LLM Judging**: The game uses an LLM for judging, which can be inconsistent. Solution: Leveraged response caching to ensure consistency once a "battle" was judged.
- **Rate Limiting**: Set up ~20 forward proxies on GCP to distribute requests across various IP addresses, enabling longer play sessions for higher scores.

Key aspects:

- Data mining for optimal responses
- Distributed request handling
- Efficient caching mechanism

## [Eventhub](https://www.eventhub.news/)

Bringing the world's information to you while letting you decide what to believe.

![Globe Demo](assets/eventhub-globe.gif)

## [2048 Player](https://github.com/cameroncuster/2048_player)

An AI player for the game 2048, featuring:

- Predictive algorithm simulating 5-7 future moves
- Custom heuristic function for board state evaluation
- Performance optimization through memoization and pruning

![2048 Player Demo](assets/2048-player-demo.gif)

## [Snake Player](https://github.com/cameroncuster/snake_player)

A Snake game AI utilizing graph traversal algorithms, particularly AStar for pathfinding.

Highlights:

- Demonstrates emergent behaviors
- Achieves near-perfect scores on various grid sizes and obstacle configurations

![Snake Player Demo](assets/snake-player-demo.gif)

## [Quadtree Image Compression](https://github.com/cameroncuster/quadtree_image_compression)

Image compression tool using Quadtree structure, emphasizing:

- Test-Driven Development (TDD)
- Object-oriented design principles
- Modular architecture for use as a standalone library
- Applicability to both image and video compression

![Quadtree Compression Demo](assets/quadtree-image-compression-demo.gif)

---

I totally didn't ask an LLM to write this 😉
