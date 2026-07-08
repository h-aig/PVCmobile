Because I only have a day or two to design this if I want to (hopefully) go to Open Sauce, this'll probably be measured in hours rather than days...

# Wednesday
## 7:30am
Research! I have done no hardware before, so there's a lot I have to research especially because guides to RC cars are scattered across the internet. I decided to go with an RC car because they're slightly more interesting than just a keyboard. In line with this, I also don't have time to wait and get stuff from Aliexpress, limiting what I can build my car out of. After seeing this extremely frugal build:

![pvc car](Pictures/pvcCar.png)

I decided that a PVC Car is the way to go! Lightweight, easy to construct without highly specialised tools, and they look not bad!

After this, I struggled a little with where to start with. All of the builds just looked like a bunch of wires, which made it hard to draw up a mental model. With some help from ChatGPT and the hackaday article below, I broke down the simplest RC car I could find, the RC toilet paper.

![toilet paper on the ground, rolling around](Pictures/toiletRC.png)



The Hackaday article states:
"The project starts with, of all things, popsicle sticks. These are used to make a reinforced platform to which the two motors, radio receiver, speed controller, and battery are mounted. With some clever packing, [Ariel] is able to (tightly) fit it inside of a cardboard tube with just the bottoms of the two wheels protruding through cutouts. A careful wrapping with toilet paper is then used to give it the look of a partially used roll, including a trailing “tail” that flutters in its wake."

I was most interested in the components it listed: a couple motors, a radio reciever, speed controller, and battery. That's all it takes to build a basic RC; there was no need to overcomplicate it. I only had a vague idea of how one might connect these (or rather, in what order), so this is where I asked ChatGPT. It gave me this, which made sense and made it easier to comprehend.

Battery -> Electronic Speed Controller (ESC) -> ( Power to Motor 1 , Power to Motor 2 (or via a second ESC if using separate drive)) -> Radio Receiver (control signal) <- Transmitter

---

After all this research, I found that no one post gave me everything I needed, which made it time consuming initally, but the fact I can piece the useful parts together to learn how to build my own made it less tedious. After cutting down tens of articles I had saved, I decided on these three to form the basis of my RC:

- https://www.instructables.com/RC-Car-From-SCRATCH/ < This gave me a really good guide on how to build a simple one, and helped with my mental model but of course mine won't be made out of 3d printed components so I'll have to adapt it.

- https://makezine.com/projects/scratch-built-rc-car/?utm_source=chatgpt.com < This gives me a really good idea of what/how to construct the frame

- https://hackaday.com/2020/04/04/r-c-toilet-paper-roll-is-the-hero-we-deserve/ < Helped me to break it down and understand how simple an RC could be

(total: 3 hours)

