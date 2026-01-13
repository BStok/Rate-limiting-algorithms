# Rate-limiting-algorithms

A hands-on playground for understanding and implementing the most common **rate limiting algorithms** used in real-world systems.

This repository accompanies my blog on rate limiting and focuses on turning theory into working code.

## Why this repo exists

Different algorithms make different trade-offs between:
- accuracy
- memory
- performance
- fairness under bursts

This repo puts those trade-offs under a microscope.

## Algorithms implemented

- **Token Bucket**  
  Allows bursts. Smooths long-term rate.

- **Leaky Bucket**  
  Enforces a constant outflow. Brutally consistent.

- **Fixed Window Counter**  
  Fast and simple. Edge cases at window boundaries.

- **Sliding Window Log**  
  Precise but memory-heavy. The “truth serum” approach.

- **Sliding Window Counter**  
  Approximation of the log. Practical and widely used.

Each algorithm lives in its own folder with:
- implementation
- brief explanation
- example usage

## Project structure
token-bucket/
leaky-bucket/
fixed-window-counter/
sliding-window-log/
sliding-window-counter/


## How to use

Clone the repo, pick an algorithm, and run the example file inside its folder.

This is built to be read, broken, tweaked, and stress-tested.

## Who this is for

- backend engineers
- system design learners
- interview prep
- anyone curious how platforms actually say “too many requests”

## Blog

This repo is based on my blog post on rate limiting algorithms.  
([You can link it here.](https://explaining-rate-limiter-system-design.hashnode.dev/explaining-rate-limiter-system-design))

## License

MIT — do anything useful with it.

