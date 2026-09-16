# LSR
LSR (Light Super Resolution) is a mod for FSR4 that runs in half the time on the Steam Deck (approximately 3ms of upscale time at 800p, 5.5ms for 1080p, ~8ms for 1440p). This is the same upscale time that FSR2/3 need and in my tests it's also faster than XeSS. The first and only job of LSR to be better than FSR3 (and with the exception of some ghosting issues in some games that I'm working to train away) it accomplishes that goal. It is 100% not as good as FSR4 but it doesn't need to be, it just needs to be good enough. I haven't done sufficient comparisons yet but I think it's also higher quality than XeSS in the DP4a path.

[![BuyMeACoffee](https://buymeacoffee.com/xmHdqLUWf)]
Note: This project has taken a lot of time and resources to get to this point. I'm releasing it now because I think it's a good enough alpha version to show what's possible but the model needs a lot more training to produce better image quality and reduce temporal artifacts. I will be doing that work anyway but if you believe in this project and want to support me please use my BuyMeACoffee link above.

# Why?
The Switch 2 shows that a competent upscaler (a custom DLSS in that case) that doesn't take forever to return a result can be a huge boon to performance and image quality. FSR4 is probably better than the DLSS being used on the Switch 2 but it cannot do the same for the Switch 2 because it costs 10ms to run at 1080p, that's almost a third of your frametime gone. While I don't have numbers, I would expect DLSS on the Switch 2 to run in ~4ms. So the motivation is that we need a temporally stable neural upsampler that can run in a lot less time (and now we do, ish).

# How?
(TODO) Fill in details of downscaled feature grid and memory being fed at lower resolution.

