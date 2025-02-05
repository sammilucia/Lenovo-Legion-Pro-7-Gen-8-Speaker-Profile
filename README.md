# Lenovo Legion Pro 7 Gen 8 (2024) Speaker Profile

Created for [JamesDSP-Linux](https://github.com/Audio4Linux/JDSP4Linux) with my EARS.

## What is it?

It's an EQ curve and spatialization to get the best sound from your laptop speakers, at a good volume, with better bass response.

Similar to Dolby Atmos etc. on Windows.

## Installing

1. Install [JamesDSP-Linux](https://github.com/Audio4Linux/JDSP4Linux) via Flatpak or however you prefer
2. Run it
3. Click the 3 dots bottom left > **Load from file**
![image](https://github.com/user-attachments/assets/bfe2ca34-7581-4d28-9d99-b10174c795d5)
4. Load jamesdsp01.conf

You should be good to go!

*Note: You can enable/disable **Reverb** as you like. I've configured it add a subtle 'spatial' impact, but it probably won't suit everything you listen to so I've left it off by default.*

Feedback welcome! Open an issue 😊

xx SammiLucia

## Technically what does it do?

The EQ curve is essentially the 'opposite' of the Lenovo laptop speakers, with a high pass filter around 60 Hz (because the speakers can't produce frequencies below this, so it's wasted energy).

It uses the psychoacoustic effects in JamesDSP to increase perceived loudness, and add width to "bring the sound out of your speakers".

I prefer a fairly flat EQ curve, so it shouldn't give any particular colour or emphasis to anything you listen to, you should hear things pretty much as the artist/author intended, within the confines of laptop speakers.

## Why JamesDSP-Linux?

Why JamesDSP and not [EasyEffects](https://github.com/wwmm/easyeffects)? Because EasyEffects has **horrible** filters*

*I _really love_ EasyEffects, however I can't listen to your filters, they comb terribly. No combination of settings fixed this. Please use some better algorithms 😊❤️
