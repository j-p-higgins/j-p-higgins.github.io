---
layout: page
title: Software - Jonathan Higgins
permalink: /software/
menu: software
---

<img
  sizes="(min-width: 56em) 800px, 90vw"
  srcset="/media/images/software_400.jpg 400w,
          /media/images/software_600.jpg 600w,
          /media/images/software.jpg 800w"
  alt="closeup of a pure data patch">

# jh.tools
Esoteric VST plugins made in Puredata compiled with [Camomile](https://github.com/pierreguillot/Camomile){:target="_blank"}. jh.tools plugins and source code are available [on github](https://github.com/j-p-higgins/jh.tools){:target="_blank"}.

## Mangle
<img
  sizes="(min-width: 56em) 800px, 90vw"
  srcset="/media/images/mangle_400.jpg 400w,
          /media/images/mangle_600.jpg 600w,
          /media/images/mangle.jpg 800w"
  alt="screenshot of the mangle plugin">
A trio of distortions varying from gentle thickening to full sonic destruction. A multiband overdrive style distortion, a hard clipping distortion with control of the symmetry of the clipping and a '1-bit ADC' for turning all sounds into square waves. 

## Resonant Downsample
  <img
  sizes="(min-width: 56em) 800px, 90vw"
  srcset="/media/images/resonant_downsample_400.jpg 400w,
          /media/images/resonant_downsample_600.jpg 600w,
          /media/images/resonant_downsample.jpg 800w"
  alt="screenshot of the resonant downsample plugin">
Sample and hold being abused with a feedback loop so that it works like a weird resonant filter. Switchable anti-aliasing type filtering to reduce high frequency artifacts for a more subtle effect. Warning, can self oscillate which can be very loud. 

## L80s Reverb
  <img
  sizes="(min-width: 56em) 800px, 90vw"
  srcset="/media/images/l80s_400.jpg 400w,
          /media/images/l80s_600.jpg 600w,
          /media/images/l80s.jpg 800w"
  alt="screenshot of the l80s reverb plugin">
Relatively rubbish reverb that sounds like a cheap, reverb unit from the late 80s. Where this plugin is interesting is that you can modify the block size, overlap and sample rate of the reverb processing which gives effects similar to circuit bent reverb units. 

## Gloop
  <img
  sizes="(min-width: 56em) 800px, 90vw"
  srcset="/media/images/gloop_400.jpg 400w,
          /media/images/gloop_600.jpg 600w,
          /media/images/gloop.jpg 800w"
  alt="screenshot of the gloop plugin">
Dual mono looper/freeze effect with tremolo. No zero crossing point detection so often clicks and pops. Switch on random for instant Alva Noto. 

## BankPass
  <img
  sizes="(min-width: 56em) 800px, 90vw"
  srcset="/media/images/bankpass_400.jpg 400w,
          /media/images/bankpass_600.jpg 600w,
          /media/images/bankpass.jpg 800w"
  alt="screenshot of the bankpass plugin">

Small bank of four resonant bandpass filters. There is a feedback loop built in which can add extra sustain to the resonance on the filters, or if pushed will go into screaming self oscillation. Plugin can optionally be controlled via MIDI in either four voice polyphonic mode or in unison. When controlled with MIDI frequency sliders work as an offset and can be used similar to an additive synthesiser in mono (unison) mode. Settings for MIDI along with some other features including toggleable pre-programmed scales can be found in the advanced features tab. 

  <img
  sizes="(min-width: 56em) 800px, 90vw"
  srcset="/media/images/bankpass2_400.jpg 400w,
          /media/images/bankpass2_600.jpg 600w,
          /media/images/bankpass2.jpg 800w"
  alt="screenshot of the bankpass plugin showing the additional settings">
  
# tt.chords
<div class="videoWrapper">
<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/ke3oCEAB7ig" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
<br>
Clone of the Chord eurorack module by Qu-Bit made in Pure Data to run on the Terminal Tedium. [Download on GitHub](https://github.com/j-p-higgins/jh.tt){:target="_blank"}.

# Euclidean Sequencer
<img
  sizes="(min-width: 56em) 800px, 90vw"
  srcset="/media/images/euclidean_400.jpg 400w,
          /media/images/euclidean_600.jpg 600w,
          /media/images/euclidean.jpg 800w"
  alt="screenshot of the euclidean sequencer and sample player">
The Euclidean Sequencer is a 16×16 step sequencer with MIDI and OSC output as well as sound file playback. It utilises a novel implementation of the Euclicean Algorithm to generate cyclic rhythmic patterns as outlined in Godfried Toussaint’s paper [“The Euclidean algorithm generates traditional musical rhythms”](http://cgm.cs.mcgill.ca/~godfried/publications/banff.pdf){:target="_blank"}. The sequencer was designed to work with the [Mutable Instruments CV Pal Eurorack Module](https://mutable-instruments.net/archive/cvpal/manual/){:target="_blank"} for live modular synth performance however it can be configured to communicate with most hardware and software. 

# Jurassic Panner
 Jurassic Panner is a twenty in, eight out, flocking algorithm panner with OSC control built in Pure Data.   It makes use of the the Boids extention which is based on Simon Fraser’s implementation of Craig Reynolds’ Boids algorithm. Boids is a bird flight and animal flock simulator. It is the algorithm which was used in Jurassic Park for the herding dinosaurs. Jurassic Panner is available [on github](https://github.com/j-p-higgins/jurassic_panner){:target="_blank"}.


# Gesture Recognition and Electroacoustic Composition
jh.Leap tools is a suite of compositional tools developed in Pure Data that utilise gestural interaction via the Leap Motion device. The source for these tools is available on GitHub. The tools currently include a sampler, a changeable pattern multi channel panner, a tremolo and a reverb. As well as these major tools the suite also includes a large variety of smaller utilities which allow gesture recognition to be quickly implemented in new and existing Pure Data patches. The jh.Leap tools can be found [on github](https://github.com/j-p-higgins/jh.leap_tools){:target="_blank"}. 
