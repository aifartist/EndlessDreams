# EndlessDreams
Exploring endless real-time interactive dreams

## Navigate the Infinite Diversity of Stable Diffusion Models
Imagine sitting back in your easy chair dictating your dreams your voice and using commands like zoom in/out, pan left/right/up/down and seeing the results instantly. Imagine being surprised when a famous person appears in your dream and you realize; Oh, I have the TV on in the background and they were just talking about that person. Imagine drawing into the video with noise in real-time and getting iteresting effects. Imagine merging another video stream, family picture, or an openpose animation into your dream as it unfolds and seeing the result immediately.

You might say: Oh, but the video is jittery. Of course, with other excellent video generators you can generate a very smooth video that takes 5(?) minutes to get perhaps 10 seconds of someone turning their head or taking a few steps. And, yes, the quality is high. However, EndlessDreams generates continuous variety for hours, days, weeks, ... as you interact with it in real-time. It is a different use case and those that have seen EndlessDreams think it has its niche in this world.

## History of real-time Stable Diffusion
**Jan 2022**: Retired as a database performance architect at Microsoft.  
**Aug 2022**: Learned of Stable Diffusion and was hooked.  
**Dec 2022**: Bought hi-end system with Ubuntu, i9-13900K and a 4090.  
Spent little time on "art?". Most of my time was spent pushing the performance of SD to the max. For me the question was: How many milliseconds do I need to generate an image? I was learning python, stable diffusion internals, and optimization techniques making continuous progress.  
**Oct 2023**: Simian Luo announces [LCM](https://github.com/luosiallen/latent-consistency-model)  
Prior to Oct the dreams of real-time AI video generations were just a fantasy. With LCM I saw that the time was **NOW**. Within hours of LCM dropping I had what **might** have been the first jittery real-time video generations running on my 4090 and I posted examples to reddit and elsewhere. By real-time I don't mean the Youtube demoes starting to appear in Nov/Dec 2023 claiming real-time SD videos at 3 to 5 fps. I started out of the gate at 10fps and quickly got to 15 fps with SD1.5. Then 33 fps for 800x800 SDXL, 22 fps 1024x1024, 17 fps 1280x1024, and I continued to this day to make things faster.
**Oct 30, 2023**: Deepfakes had been around for awhile. But not real-time generated DeepFakes. Here is a poorly lit crude early demo of mine: [RT DF Demo](https://www.reddit.com/r/StableDiffusion/comments/17kekea/demo_of_realtime15fps_camera_capture_plus_sd/)
**Nov 5, 2023**: Coined the term [RTSD](https://www.reddit.com/r/StableDiffusion/comments/17ovxqq/rtsd_real_time_stable_diffusion_powered_by_lcm/) and demoed the ability to, in real-time, generate images on the fly as one changed the prompt or other paramaters using sliders. Instant feedback vs making a change, clicking generate and then waiting.

My Twitter where you can see some older demoes:  https://x.com/Dan50412374/  
My YouTube channel with my first try at a YouTube demo: https://www.youtube.com/watch?v=irUpybVgdDY  

There are a number of reasons I'm starting with "no license". I'll only mentions this one: I gave a screen share demo of this to a guy that does Hackathons. He recorded my demo, and having not written a line of code of this, he posted it on Linked-in as one of his projects. I got mentioned as a member of his team.  Egads.  
Enjoy EndlessDreams. It is my fault and my fault alone for sitting on this for so long. If was a breakthrough when I first created it and all I ask is for people to give it a look.
