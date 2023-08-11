# 11 Real-World Design Examples that Prioritize Accessibility Lesson  Uxcel
## Use alternative text for images

![Use alternative text for images Bad Practice](https://img.uxcel.com/practices/use-alternative-text-for-images-1612874157081/b-1680861199942.jpg)

![[Attachments/8b057d958dd8b35e7fbb1a520699c931_MD5.jpg]]

Alt text is an [HTML](https://app.uxcel.com/glossary/html) attributive snippet that provides text descriptions to [images](https://app.uxcel.com/glossary/images) for [search](https://app.uxcel.com/glossary/search) engines and assistive technology. Without it, your website has no "voice," and users of assistive [devices](https://app.uxcel.com/glossary/device) like screen readers will struggle to navigate and understand the [content](https://app.uxcel.com/glossary/content).

Alt text shouldn't be a literal description of the image. Instead, it needs to explain the purpose of an image for those who can't see it, like the New York Times does with the image of a famous pianist.

Cut off unnecessary details like [colors](https://app.uxcel.com/glossary/color) when they don't matter. For decorative images that don’t carry any extra information, provide an empty alt text (alt=""). This signals to assistive technologies that they can ignore the null alt attribute. Otherwise, screen readers will announce the file name and add audible clutter.<sup><a href="moz-extension://1fff0f8b-616f-485f-8cf3-32584a1a9298/#anchor-1" rel="noopener noreferrer" applinkanchor="">[1]</a></sup>

If you're unsure of whether your images need alternative text, check out the [World Wide Web Consortium's guide.](https://www.w3.org/WAI/tutorials/images/decision-tree/)

**Tip!** For a more detailed study on making your product more inclusive and accessible, check out our [Design Accessibility](https://app.uxcel.com/learn/design-accessibility) course.

## Allow navigating with keyboard

[Keyboard](https://app.uxcel.com/glossary/keyboards) [navigation](https://app.uxcel.com/glossary/navigation) can make or break the whole [user experience](https://app.uxcel.com/glossary/user-experience). While it's vital for users with motor disabilities, it also benefits a broader circle of people — someone who has a broken arm, someone with a dead mouse battery, or keyboard power users.

If done correctly, the keyboard focus moves from top left to bottom right, following the logical order of the visual [layout](https://app.uxcel.com/glossary/layout-composition), not skipping any important elements. If done poorly, the focus jumps all over the place, and keyboard users can't access some interactive [features](https://app.uxcel.com/glossary/feature) like [dropdown](https://app.uxcel.com/glossary/dropdown) options.

**Tip!** If your website has dozens of navigational links, make sure users can leap directly to the main content by clicking the To the Main Content button.

## Use captions and transcripts

![[Attachments/c88b3f6a4c0833367fe7373045168b81_MD5.jpg]]

![[Attachments/bed8e5c1490ebc1d456a8dad9a71c910_MD5.jpg]]

How to help users with hearing, cognitive, or learning disabilities consume audio and video content? One of the best options is captions and transcripts. They remove barriers by converting speech into written text, identifying speakers, and mentioning any other sound effects like laughter or rain to portray the environment more realistically. Captions are also helpful for all people in noisy surroundings, like public transport, or quiet places, like libraries or hospitals.

The TED team nails it with their video content, providing captions, subtitles, and transcripts in multiple languages and making it accessible to anyone.

If you need help with transcripts, the [World Wide Web](https://app.uxcel.com/glossary/web) Consortium shares a [list of transcription services](http://www.uiaccess.com/transcripts/transcript_services.html) that provide text versions of audio files in different formats.

## Put users in control and prevent autoplay

![[Attachments/37e0c4eca8212287b30edd628dfce5e8_MD5.jpg]]

![[Attachments/bf2af6e7262d3a8d1a5a078cf1001062_MD5.jpg]]

We've all been there — you open the website only to get caught off guard by videos that start playing instantaneously. You're lucky if the sound is off! While merely annoying for most users, autoplay can cause real damage to some — for example, trigger an epileptic seizure.

Facebook lets users choose if they want to enable autoplay — Instagram isn't that gracious, but at least the sound is off by default. The most important thing is to give users control over video content. It's also a good idea to let users pause and play the playback using the [Space](https://app.uxcel.com/glossary/spacing) key — in addition to the Play [icon](https://app.uxcel.com/glossary/icons), of course.

## Provide a logical heading structure

Headings serve several functions. First, they stand out and emphasize key concepts. Second, they convey the levels of importance, both on a visual level and in code, and it's crucial that the design coincides with its skeleton. For example, higher-level headings should look more prominent, and the structure must follow a logical order — similar to a [table](https://app.uxcel.com/glossary/tables) of contents in a book.

Having a clear heading structure makes your website appear clear and logical and reduces clutter. Make sure your heading levels follow a design outline so screen readers can identify headings and read out the content to users with disabilities.<sup><a href="moz-extension://1fff0f8b-616f-485f-8cf3-32584a1a9298/#anchor-2" rel="noopener noreferrer" applinkanchor="">[2]</a></sup> For example, a `<h3>` tag indicates the 3rd level headings and should always go after headings under `<h2>` [tags](https://app.uxcel.com/glossary/tags).

**Tip!** Explore popular HTML tags that are commonly used in web development to structure and organize content in the [Popular Tags in HTML](https://app.uxcel.com/lessons/html-popular-tags-770?utm_source=share-lesson) lesson.

## Follow level AA color contrast guides

![[Attachments/86be4242c7d1493c3f4782716e2d8ca4_MD5.jpg]]

![[Attachments/0880ec39a990965f120d5c55b365e8bf_MD5.jpg]]

You might put your heart and soul into crafting an exquisite [color palette](https://app.uxcel.com/glossary/color-palette) for your website, but it doesn't mean much to those who can't see it. To be accessible to most users, your website needs to meet [WCAG](https://app.uxcel.com/glossary/wcag) level AA that requires a [contrast](https://app.uxcel.com/glossary/contrast) ratio of at least 4.5:1 for normal-sized text (less than 18pt for regular or 14pt for bold). For large-sized text (18pt and larger for regular or 14pt and larger for bold), the contrast ratio between foreground and [background](https://app.uxcel.com/glossary/background) colors must be 3:1.<sup><a href="moz-extension://1fff0f8b-616f-485f-8cf3-32584a1a9298/#anchor-3" rel="noopener noreferrer" applinkanchor="">[3]</a></sup>

Using textures and patterns for backgrounds can impede [legibility](https://app.uxcel.com/glossary/legibility). You can avoid this by increasing the contrast — for example, by applying a dimmed overlay or an extra layer underneath the text when using an image for a background. Also, ensure that essential elements have sufficient hue, value, and chroma contrast, and avoid using hues with similar values close to one another.

**Tip!** Make sure to use a high contrast hue for unclicked and visited links. For example, use blue (#0000FF) for new links and deep burgundy (#660033) for visited links so that color-blind users can feel the difference.

## Don't rely on color only

![[Attachments/765b7bf55929795cf6b56fabadbb3d91_MD5.jpg]]

Colors are powerful, but don't rely on them exclusively — otherwise, you'd be excluding users with disabilities. Instead, emphasize the information using icons, text explanations, and graphic elements.

For error messages, [warnings](https://app.uxcel.com/glossary/warning), or success [states](https://app.uxcel.com/glossary/states), add helpful [microcopy](https://app.uxcel.com/glossary/ux-microcopy) and icons to describe what is happening in the system and how users can fix possible issues.<sup><a href="moz-extension://1fff0f8b-616f-485f-8cf3-32584a1a9298/#anchor-4" rel="noopener noreferrer" applinkanchor="">[4]</a></sup> Booking.com does a great job of providing short explanatory messages and icons and outlining [inputs](https://app.uxcel.com/glossary/inputs) that contain [errors](https://app.uxcel.com/glossary/errors). What may seem like tiny details actually benefit all users, including those with visual, cognitive, or learning disabilities?

## Allow zoom without affecting the layout

![[Attachments/5dd4d901c3f134d784f1df8bcf18a0b4_MD5.jpg]]

![[Attachments/e60c6c054a9d22bd487ee94eec5b5483_MD5.jpg]]

WCAG guidelines state that the entire website must be resizable up to 200% without assistive technology and loss of content or functionality.<sup><a href="moz-extension://1fff0f8b-616f-485f-8cf3-32584a1a9298/#anchor-5" rel="noopener noreferrer" applinkanchor="">[5]</a></sup>Users with visual impairments might want to scale up the web [page](https://app.uxcel.com/glossary/pages) to simplify reading. Browsers usually accomplish this either by enlarging the [font size](https://app.uxcel.com/glossary/font-size) only or zooming in on the whole page and applying responsive [styles](https://app.uxcel.com/glossary/style).

Collaborate with the dev team and ensure the code doesn't interfere with the browser's default [settings](https://app.uxcel.com/glossary/settings) of zooming content. Amazon could have done better than enlarging with scrolling! In contrast, Airbnb adjusts the content without losing functionality and information or distorting the layout.

## Avoid rapidly flashing videos and animations

![[Attachments/775aea147d5777dc8d1441e58b3b35c6_MD5.jpg]]

![[Attachments/bd1e3865f21c3b54c76bcb19e75385ce_MD5.jpg]]

According to the Epilepsy Foundation, about 65 million people worldwide live with this condition.<sup><a href="moz-extension://1fff0f8b-616f-485f-8cf3-32584a1a9298/#anchor-6" rel="noopener noreferrer" applinkanchor="">[6]</a></sup> Users with the photosensitive [form](https://app.uxcel.com/glossary/forms) of epilepsy might experience seizures or severe headaches when seeing videos and [animations](https://app.uxcel.com/glossary/animation) with flashing and strobing effects.

How can you limit the risk of harming your users? Follow in the footsteps of TikTok, who in 2020 announced a new feature of showing a warning of videos or [photo](https://app.uxcel.com/glossary/photos) effects containing potentially harmful effects. Users can select the Skip All option and continue enjoying the app.

## Allow users to control image carousels

You know how when you ride a carousel, at some point, the surroundings turn into an incoherent blur? That's how people with motor, cognitive, or learning disabilities feel when they encounter image [carousels](https://app.uxcel.com/glossary/carousels). On the one hand, carousels are fantastic when it comes to saving space. On the other hand, they might change too fast for people with certain impairments who often need more time to focus, read, react, type, and complete tasks.

Another reason for allowing users to control image carousels is that it gives users who may not be able to use a mouse or trackpad the ability to navigate through the carousel using only their keyboard.

Make sure carousels have a time limit of 5 seconds or longer and allow users to stop, pause, or hide the content.

## Use enough spacing

![[Attachments/8e3ad40f6970950e826c3007ba7a21d6_MD5.jpg]]

![[Attachments/bb83c69a549068cee6da8c6e60cf0022_MD5.jpg]]

Adding enough spacing in designs is like letting the fresh air into a stuffy room. First off, it makes websites look sharp and modern. Secondly, more space between words helps people with visual, cognitive, and learning disabilities process information more easily.

As a rule of thumb, don't skimp on [white space](https://app.uxcel.com/glossary/white-space) between text blocks, as well as line spacing. The British Dyslexia Association recommends keeping line spacing proportional to character spacing and defines 150% of font size as preferable for readability.<sup><a href="moz-extension://1fff0f8b-616f-485f-8cf3-32584a1a9298/#anchor-7" rel="noopener noreferrer" applinkanchor="">[7]</a></sup> Failing to do so, you make letters on adjacent lines cram and turn them into a tangly mess of words.

As for line length, follow the WCAG recommendations, where 80 characters or glyphs per line are acceptable in English.<sup><a href="moz-extension://1fff0f8b-616f-485f-8cf3-32584a1a9298/#anchor-8" rel="noopener noreferrer" applinkanchor="">[8]</a></sup>

Take the lesson quiz and assess your knowledge

Completing the interactive quiz is proven to help you learn faster and remember the information for longer.

## References

-   [Headings](https://www.w3.org/WAI/tutorials/page-structure/headings/) | Web Accessibility Initiative (WAI)
    

## Key skills

## Share this lesson