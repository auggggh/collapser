# collapser
m4l device of extreme gating distortion

# what's happening??
Collapser is what I would call an "extreme gating distortion." It started out as a basic single-sample noise gate, only letting through samples that are louder than the "collapse" setting. When "mode" is set to 100%, this is how the effect is functioning. If mode is set to 0%, however, it will only let through samples that are quieter than the "collapse" setting, and will amplify the output by collapse's reciprical (so if collapse were at -6.02 dB, only samples below -6.02 dB (i.e., absolute value smaller than .5) would be let through, and would then be amplified by 2).  
Because of the nature of the effect, you can get some strange oscillations when you add feedback, which can be very particular at times; because of this, I added the option to change the range of feedback between .1% and 200%. There are toggles to invert the feedback loop and to control the feedback with the amplitude of the input signal. The options for envelope control are "follow," which directly controls the amount of feedback with the input's amplitude, "gate," which turns feedback on or off depending on if the amplitude is above the "thresh" setting, and "gatfol," which combines the two (turning the feedback off below the threshold, following the input's amplitude above the threshold). The "inv. env." toggle will flip how the envelope following modes percieve the signal's amplitude; it's not usually very helpful unless you want oscillation whenever the input signal is silent, which you may want in some cases.

# video
[Here's a video showing various sounds coming out of Collapser](https://www.youtube.com/watch?v=eZ_u4W_yUXU).
