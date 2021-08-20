## Video and audio on the web:

![Js](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQZDIL_wl_e9GktcPMlkXOgHLevpdfhrzzHyA&usqp=CAU)

Web developers have wanted to use video and audio on the Web for a long time, ever since the early 2000s when we started to have bandwidth fast enough to support any kind of video (video files are much larger than text or even images.) In the early days, native web technologies such as HTML didn't have the ability to embed video and audio on the Web, so proprietary (or plugin-based) technologies like Flash — and later, Silverlight (both of which are now obsolete) — became popular for handling such content. This kind of technology worked ok, but it had a number of problems, including not working well with HTML/CSS features, security issues, and accessibility issues.

A native solution would solve much of this if implemented correctly. Fortunately, a few years later the HTML5 specification had such features added, with the <video> and <audio> elements, and some shiny new JavaScript APIs for controlling them. We'll not be looking at JavaScript here — just the basic foundations that can be achieved with HTML.

We won't be teaching you how to produce audio and video files — that requires a completely different skillset. We have provided you with sample audio and video files and example code for your own experimentation, in case you are unable to get hold of your own.
 The features of note are:

src
In the same way as for the <img> element, the src (source) attribute contains a path to the video you want to embed. It works in exactly the same way.
controls
Users must be able to control video and audio playback (it's especially critical for people who have epilepsy.) You must either use the controls attribute to include the browser's own control interface, or build your interface using the appropriate JavaScript API. At a minimum, the interface must include a way to start and stop the media, and to adjust the volume.
The paragraph inside the <video> tags
This is called fallback content — this will be displayed if the browser accessing the page doesn't support the <video> element, allowing us to provide a fallback for older browsers. This can be anything you like; in this case, we've provided a direct link to the video file, so the user can at least access it some way regardless of what browser they are using.
