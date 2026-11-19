# Dionyziuz

## Read this first

**[Scale the Model, Scale the Harness: Unlocking a 2× Leap in Mathematical Reasoning](https://generativeai.pub/scale-the-model-scale-the-harness-unlocking-a-2-leap-in-mathematical-reasoning-231314ab3ea7)** — published in Generative AI on Medium, Nov 2026.

I built a system that wraps a language model in a checking loop: every proof step gets verified with real math tools, the system remembers what worked, and a second pass tries to break the proof before it counts.

I tested it on 300 hard math problems. A 27B model on one home GPU went from 12.7% to 26.7% solved. Muse went 22% to 46.3%. Gemini Flash went 33.7% to 55.3%. The loop fixed 16–33% of the problems each model got wrong on its own.

The point: the setup around the model matters as much as the model.

## The code

**[proof_harness](https://github.com/dionyziuz/proof_harness)** — the harness, open source, with all the test results public so anyone can check them.

## Me

Chief AI Officer.
[LinkedIn](https://www.linkedin.com/in/edwin-jongsma) · [dionyziuz.com](https://dionyziuz.com) · [Medium](https://medium.com/@edwin.jongsma)
