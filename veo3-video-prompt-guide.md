[Skip to main content](https://leonardo.ai/news/mastering-prompts-for-veo-3/#brx-content) [Skip to footer](https://leonardo.ai/news/mastering-prompts-for-veo-3/#brx-footer)

# Mastering Prompts For Veo 3

Insights\|Published on June 6, 2025

![Wave crashing](https://leonardo.ai/wp-content/uploads/2025/06/ai-generated-wave-1024x579.jpg)

Table of contents

- [Prompting Essentials](https://leonardo.ai/news/mastering-prompts-for-veo-3/#leo-toc-0)
- [Prompt Length](https://leonardo.ai/news/mastering-prompts-for-veo-3/#leo-toc-1)
- [Prompt Structure](https://leonardo.ai/news/mastering-prompts-for-veo-3/#leo-toc-2)
- [Camera Shots](https://leonardo.ai/news/mastering-prompts-for-veo-3/#leo-toc-3)
- [Camera Movements](https://leonardo.ai/news/mastering-prompts-for-veo-3/#leo-toc-4)
- [Camera Angles](https://leonardo.ai/news/mastering-prompts-for-veo-3/#leo-toc-5)
- [Repetition vs. Variation](https://leonardo.ai/news/mastering-prompts-for-veo-3/#leo-toc-6)
- [Object Count and Complexity](https://leonardo.ai/news/mastering-prompts-for-veo-3/#leo-toc-7)
- [Tone and Writing Style](https://leonardo.ai/news/mastering-prompts-for-veo-3/#leo-toc-8)
- [Conclusion](https://leonardo.ai/news/mastering-prompts-for-veo-3/#leo-toc-9)

[Start Now](https://app.leonardo.ai/ "Start Now")

Share

- [Facebook](https://www.facebook.com/sharer.php?u=https%3A%2F%2Fleonardo.ai%2Fnews%2Fmastering-prompts-for-veo-3%2F&picture=https%3A%2F%2Fleonardo.ai%2Fwp-content%2Fuploads%2F2025%2F06%2Fai-generated-wave.jpg&title=Mastering%20Prompts%20For%20Veo%203)
- [X](https://x.com/share?text=Mastering%20Prompts%20For%20Veo%203&url=https%3A%2F%2Fleonardo.ai%2Fnews%2Fmastering-prompts-for-veo-3%2F)
- [LinkedIn](https://www.linkedin.com/shareArticle?mini=true&url=https%3A%2F%2Fleonardo.ai%2Fnews%2Fmastering-prompts-for-veo-3%2F&title=Mastering%20Prompts%20For%20Veo%203)

We’ve been working closely with our Creator Community to understand the best ways to prompt for [Veo 3](https://leonardo.ai/veo-3/). After consolidating their feedback and running our own extensive tests, we’ve put together this comprehensive prompting guide.

Since audio prompting comes with its own challenges and best practices, we’ve covered that in a [separate companion guide.](https://leonardo.ai/news/how-to-prompt-audio-for-veo-3/)

## **Prompting Essentials**

Before we get into advanced techniques, we need to get the basics right. Every strong Veo 3 prompt includes a few core elements that compose the building blocks of your shot. According to [Google’s own guidance](https://cloud.google.com/vertex-ai/generative-ai/docs/video/video-gen-prompt-guide), the most important parts of any prompt are:

- **Subject**: Who or what is the focus of the scene? A person, animal, object, or abstract form.
- **Context**: Where is this taking place? Think background, setting, environment, time of day.
- **Action**: What is the subject doing? This can be simple (walking, sitting, turning) or layered (pausing, reacting, adjusting posture).
- **Style**: The overall look and feel. You can reference film genres ( _film noir_, _animated short_), visual tone ( _gritty realism_, _warm and soft_), or artistic aesthetics ( _oil painting_, _Pixar-like_).

These four are essential, but you can also add optional modifiers for more control:

- **Camera motion**: Is the camera static, tracking, pulling in, or panning?
- **Camera framing**: What type of shot is this? Wide, medium, close-up?
- **Camera angle:** Do we see the subject at eye level, from below (low angle), from above (high angle), or directly overhead?
- **Ambiance**: Describe the lighting and color tone (e.g., “pale morning light,” “cool blue shadows,” “sunset orange haze”).
- **Audio**: If you want sound, specify it. Dialogue, ambient noise, or background music can all be included—check out our separate [guide on prompting for audio](https://leonardo.ai/news/how-to-prompt-audio-for-veo-3/).

### Example Prompt

_A man in worn clothing walks slowly across an open desert, one hand raised to shield his face from the sun. The camera begins at shoulder height behind him, then rises in a smooth, drone-style lift into an overhead wide shot, revealing the vast, empty landscape stretching endlessly in all directions. The horizon shimmers with heat beneath a pale blue sky. Style: Cinematic, tense, minimalist. Audio: A slow-building thriller film score, layered with low strings and subtle pulses beneath the silence._

### Observations

The result shows an almost perfect prompt adherence! Let’s unpack this prompt:

- **Subject:** A man in worn clothing.
- **Context:** An open desert under a pale blue sky, with the horizon shimmering from heat.
- **Action:** He walks slowly, one hand raised to shield his face from the sun.
- **Style:** Cinematic, tense, minimalist.
- **Camera:** The camera begins behind him at shoulder height, then lifts smoothly into an overhead shot.
- **Audio:** A slow-building thriller film score.

What else could you add to make this shot even stronger? Maybe a dust storm on the horizon? You could even reverse the camera movement—have it approach instead of pulling away. Try it in [Leonardo.Ai](https://leonardo.ai/) and see if the new version pushes the mood in a direction you like.

## **Prompt Length**

### What It Is

Prompt length is how much you tell Veo about the shot. Too short, and the output may feel generic. Too long, and the model might get confused or try to do too much.

### Best Practice

Aim for a balanced range: roughly 3–6 sentences, or 100–150 words. This gives you room to describe the subject, context, action, and style, with optional space for other elements like camera, ambiance, or sound. Long-winded paragraphs or overly compressed one-liners tend to perform worse. Think of each prompt as a single, self-contained shot.

### Example Prompt

_A wide, eye-level cinematic shot captures a man walking slowly across a frost-covered bridge at dawn, his hands tucked into the pockets of a heavy coat. Pale morning light glows faintly through soft, curling fog that clings to the bridge railings. In the distance, bare trees fade into the mist, their skeletal branches barely visible. The pace is unhurried and reflective, evoking a naturalistic and quiet mood. The scene is filled with subtle, atmospheric sounds—faint footsteps crunching on frost, steady breaths in the cold air, and the distant caw of a crow echoing across the stillness._

### Observations

Notice that while the output keeps the camera below eye level (instead of at eye level), it gets so many other elements impressively right:

- **Subject:** A man with his hands tucked into the pockets of a heavy coat.
- **Action:** He’s walking at an unhurried, reflective pace.
- **Context:** A frost-covered bridge on a foggy morning; in the distance, bare trees fade into the mist, their skeletal branches barely visible.
- **Style:** Cinematic.
- **Composition:** Wide shot.
- **Ambiance:** Pale morning light glowing faintly through soft fog.
- **Sound:** Faint footsteps crunching on frost, with the distant caw of a crow echoing across the stillness.

**Sound:** Faint footsteps crunching on frost, with the distant caw of a crow echoing across the stillness.

## **Prompt Structure**

### What It Is

Prompt structure refers to the overall way your shot description is organized. It’s not just about word order, but about how the information is arranged and presented. For example, you might write your prompt as a flowing cinematic paragraph or break it into labeled sections like “Subject,” “Action,” and “Camera.” Veo may interpret the same scene differently depending on the structure you use or which element it encounters first.

### Best Practice

There’s no one-size-fits-all format, but Veo tends to interpret structure literally. The way you format your prompt can affect how the model handles pacing, focus, and motion. One of the most important things is to clarify your goal and visualize the shot beforehand so you know what you want to see. If you want the background to stand out or the lighting to carry more weight, it often makes sense to mention it first. For example, let’s rewrite the prompt above in a modular format with labeled sections, this time placing the context before the subject.

### Example Prompt (Modular Format With Labeled Sections)

_Context: A frost-covered bridge at dawn, with bare trees fading into the mist in the distance._

_Subject: A man with his hands tucked into the pockets of a heavy coat._

_Action: He walks slowly across the bridge at an unhurried, reflective pace._

_Style: Cinematic._

_Composition: Wide shot, eye level_

_Lighting and Ambiance: Pale morning light glowing faintly through soft, curling fog that clings to the bridge railings._

_Audio: Faint footsteps crunching on frost, steady breaths in the cold air, and the distant caw of a crow echoing across the stillness._

### Observations

One major difference we’re seeing compared to the previous prompt is that we now see much more of the bridge in the first few seconds. While a video generation model is a bit of a black box and we can never know for sure, we can hypothesize that specifying the bridge first forced the model to give more attention to that element.If you want to try more variations, you can go on [Leonardo.Ai](https://leonardo.ai/) and experiment with different prompt structures. Remember that finding the right structure takes a lot of experimentation, which is why having a clear goal is key: it helps you experiment purposefully, not aimlessly.

## **Camera Shots**

### What It Is

Camera shot refers to how much of the subject and environment is visible in the frame. A wide shot might show a landscape and a distant figure. A close-up might focus on a single gesture, like a hand clenching or a tear falling. Veo understands classic film language (wide shot, medium shot, close-up, etc.) and generally follows these instructions accurately.

### Best Practice

Always specify the shot type if you want control over framing. If you leave it out, Veo will often default to the most common framing patterns it encountered during training for videos similar to what you’re trying to create. You can combine it with a camera angle or motion, but avoid describing multiple conflicting shot types in a single prompt.

Because of how video generation models are trained, they sometimes have a strong tendency to default to a certain camera framing, even if you repeatedly and clearly ask for a different one. This happens when the subject, action, and context you’re trying to depict are strongly tied in the training data to a specific framing. The best approach here isn’t to repeat the same prompt over and over, hoping the model will eventually get it right—instead, try a workaround, like changing some aspect of the subject or action, even if it means making a small compromise.

### Example

_Close-up. Style: TV commercial. A woman in her 30s takes her first sip of coffee while sitting on a small balcony overlooking a quiet city street. She’s wrapped in a soft sweater, morning light grazing her face. It’s chilly—steam rises gently from the mug and curls past her cheek. Her shoulders drop slightly as the warmth hits. Her eyes close for just a moment—not dramatic, just real. Audio: background music._

### Observations

Prompt adherence is nearly perfect here. Building on our advice about prompt structure, notice how frontloading the camera framing and style helped ensure we got a close-up in a TV commercial tone.

## **Camera Movements**

### What It Is

Camera movement refers to how the camera behaves within the shot. Is it staying locked in place, pulling back, panning across a space, or tracking a subject from behind? These choices affect pacing, emotional tone, and how much of the scene unfolds over time.

### Best Practice

If you want the camera to move, you need to say so clearly in your prompt. If you don’t mention any movement, Veo will default to something that might not match what you had in mind. Starting with a visual goal is key because it directs your experimentation.

Movement instructions typically work better when separated from subject actions. For example, write “The camera pulls back” as a standalone sentence, rather than embedding the motion within a longer description. This helps the model parse your intent and match the framing more reliably.

Again, if you don’t get the output you want, it’s not a good idea to fight the model by repeating the same prompt over and over again. Think of Veo as a highly complex statistical machine—instead of forcing it to behave the way you want (which, statistically, it won’t), it’s better to experiment with different approaches to achieve your goal.

### Example Prompt

_A sleek smartwatch sits on a rugged rock near the edge of a mountain cliff. The camera begins close, then pulls back in a smooth, continuous drone-style shot. As it rises, a vast alpine landscape unfolds—jagged peaks, mist rolling through the valley, and golden sunrise light washing over everything. The tone is cinematic and epic, emphasizing the contrast between modern technology and untamed nature._

### Observations

Prompt adherence was high for this shot, and we got nearly everything right, especially the camera movement. Notice how the sentence describing the camera movement is clearly separated from those describing other elements.

## **Camera Angles**

### What It Is

Camera angle refers to where the camera is positioned in relation to the subject. Are we looking up at the subject, looking down on them, or seeing them straight on? This choice changes how the subject is perceived:

- **Low angle (camera below eye level):** Makes the subject look large, powerful, or imposing.
- **High angle (camera above eye level):** Can make the subject feel small, isolated, or vulnerable.
- **Eye-level:** Neutral, grounded, balanced.

### Best Practice

If the angle matters, name it early, because Veo won’t always choose the most expressive or cinematic angle on its own. Like with other aspects of prompting, if the angle isn’t specified, the model often defaults to an angle that might not be what you want.

Specifying angle alone isn’t always enough. For high angles, describe what the camera sees beneath the subject. For low angles, describe what’s behind or above them. This helps Veo lock onto the perspective you want.

Since they are all elements related to the camera, it’s always worth trying to include angle, framing, and movement together.

### Example Prompt

_A low-angle medium shot frames a boxer from below as he bounces in place before a match, lit by harsh overhead fluorescents. Sweat glistens on his jawline and neck, catching the cold light. His breath is slow and controlled, his shoulders rolling with each inhale. Huge crowd. Style: Gritty, cinematic realism._

### Observations

The output shows strong prompt adherence, especially for camera angle and framing. Notice that because we didn’t specify any camera movement, Veo defaulted to a handheld shot. To understand why, consider its training data: most boxing scenes—whether from live broadcasts or films—are often shot handheld at the start of a match.If you want to experiment further with this prompt, go to [Leonardo.Ai](https://leonardo.ai/) and try adding a camera movement that feels counterintuitive (for example, a dolly-out, which in this case might release the tension instead of building it).

## **Repetition vs. Variation**

### What It Is

Repetition is using the same words many times in the same prompt to force the model to emphasize an element more. Variation involves using synonyms, rephrasings, or different visual references to express the same idea—sometimes with added nuance—without repeating the exact same words.

### Best practice

Veo doesn’t understand language the way we do. It’s a statistical model, and under the hood, your prompt is converted into a sequence of numbers. So repeating a word—like you’re trying to clarify something to a toddler—usually doesn’t help. Our tests show that repeating the same word multiple times in one prompt doesn’t create stronger emphasis. It often results in a noisier, less focused output.

Variation can be helpful when you’re describing layered details like weather, light, or ambiance. For example, instead of writing:

_Rain falls. Rain drips. Rain hits the pavement. Rain reflects the light. Rain gathers in puddles._

You could try:

_Cold drizzle falls under dim streetlights. Droplets tap against rusted metal and scatter into puddles. A sheen of water coats the sidewalk, reflecting pink signage._

However, even varied phrases can still map to similar patterns in the model’s embedding space, which means Veo might interpret them as simple repetition. As with other aspects of prompting, the most effective approach is goal-driven experimentation.

### Example Prompt

_Wide shot. A narrow alley glows under pulsating signage as cold drizzle falls from the sky. Droplets tap against rusted pipes and ripple across the soaked pavement. A sheen of water coats the sidewalk, reflecting pink signage. A hooded figure walks slowly past corroded vending machines, their reflection bending across the wet stone. Style: Cinematic, urban night._

_Audio: A distant mechanical alarm blares once, then fades. Neon buzzes softly. Static crackles from unseen speakers. A low electrical hum pulses beneath the rain._

### Observations

Even though we didn’t specifically mention “rain” in our prompt, Veo generated a drizzle (a light rain). On the left side of the shot, a few droplets tap against rusting pipes. There’s also a sheen of water on the sidewalk, reflecting pink signage, with raindrops clearly visible. The stone looks wet. Overall, we got solid results and achieved the variation we aimed for.

## Object Count and Complexity

### What It Is

This refers to how many distinct elements you include in a single shot—both different types of objects (like characters, props, background details) and how many instances of the same object you ask for.

### Best Practice

Based on our tests, Veo 3 can handle low-to-moderate object counts with good fidelity—typically up to around 15 of the same item. Beyond that, there’s a risk of vague shapes, inconsistent spacing, or objects merging together. If your shot depends on visual precision with high numbers, you’ll usually get better results by focusing the scene around one or two key elements and keeping the background simple or implied.

If your scene is complex and includes many different objects—where count also matters—keep in mind that asking Veo to render a dozen lanterns, twenty birds, or a crowd of people means asking it to manage spatial logic, scale, and interaction all at once. You can always try and see what happens, but if it doesn’t work the first time, don’t keep repeating it. Instead, think like a screenwriter: which objects actually serve the story? Once you have an answer, cut the rest.

### Example Prompt

_Only six lanterns float slowly across the surface of a misty lake, forming a wide ring. Their warm glow flickers across the glassy water, each reflection trembling softly in the haze. The lake is silent, still, encircled by tall, dark trees fading into fog. Style: Cinematic, eerie stillness._

_Audio: Low, tension-building horror score; faint water movement beneath the music._

### Observations

Specifying “only” helped the model understand that we needed exactly six lanterns. Since our goal was to get the correct number, we front-loaded this element to make sure it was prioritized. The shot is quite cinematic and could easily belong in a horror film.

## **Tone and Writing Style**

### What It Is

This refers to how you phrase your prompt. Are you writing in clear, present-tense directions? Or are you leaning into poetic language, technical phrasing, or something closer to screenplay format? While Veo doesn’t understand tone and style exactly like a human, it may react differently based on the style and rhythm of your words.

### Best Practice

Consider this short poem: _Time knelt quietly in the corner, counting breaths it never took_. Can you visualize it? Neither can Veo. While you don’t have to flatten your writing, make sure you’re always describing something that can be seen or heard in the frame.

Veo tends to respond well to prompts that read like visual direction—simple, image-focused, and written in the present tense. Think like a filmmaker: you need to create emotion through what is seen and heard, not through text.

### Example Prompt

_Wide shot. Style: cinematic. A curved corner diner glows brightly on a dark, empty street at night. Inside, three customers sit at the long counter—two men in suits and fedoras, one woman in a red dress, all quietly facing forward. A server sits quietly behind the counter, avoiding eye contact. The interior is stark and clean, lit with warm overhead light that spills out onto the sidewalk. Outside, the storefront windows reflect empty green-tinted buildings and a quiet, empty road. Audio: strong wind outside._

### Observations

Our goal with this shot was to evoke loneliness, but we never explicitly used the word in the prompt, nor did we rely on poetic or literary language. Instead, we leaned on visual cues to suggest the emotion indirectly: the lack of interaction between the customers, the distance between them, the server avoiding eye contact, the empty streets, the sound of the wind.

And if this shot feels vaguely familiar, you’re not wrong—it was inspired by Hopper’s famous [Nighthawks painting](https://en.wikipedia.org/wiki/Nighthawks_(Hopper)). Try choosing a painting you love (one that conveys a strong emotion) and recreate it in [Leonardo.Ai](https://leonardo.ai/) without explicitly naming the feeling you’re trying to evoke. Focus on the visual (and, if possible, audio) cues that build that emotion naturally.

## Conclusion

[Veo 3 is a powerful creative tool](https://leonardo.ai/veo-3/), but it’s highly sensitive to how you write. As you’ve seen throughout this guide, even small changes in prompt length, structure, or phrasing can shift the tone, pacing, or focus of a shot. That’s why clarity and intention are essential.

To get strong, consistent results, make sure your prompt includes the core elements: subject, context, action, and style. For more control, you can also add optional modifiers: camera language, ambiance, or audio.

Be mindful of how you manage prompt length and structure. Keep prompts focused, with one clear idea per shot. Use straightforward sentence structure and avoid overloading the frame with too many actions or visual elements.

Above all, have a goal. If you know what you want to see, you’ll be able to shape your prompt around that outcome and experiment with purpose. Whether you’re aiming for a specific mood, pacing, or visual payoff, clear intent makes a difference.If you want to keep exploring, try experimenting in [Leonardo.Ai](https://leonardo.ai/) and take a look at our [separate guide on audio prompting](https://leonardo.ai/how-to-prompt-audio-for-veo-3/).

[Back to the list](https://leonardo.ai/news/ "Back to the list")

### Related Articles

[Browse All](https://leonardo.ai/news/ "Browse All")

[![AI art style variations](<Base64-Image-Removed>)\\
\\
How To, Insights\\
\\
**AI Art Styles Explained: A Visual Guide With Examples**\\
\\
Try prompting something simple without mentioning the style, like a handbag on a pedestal. The model...](https://leonardo.ai/news/ai-art-styles/) [![](<Base64-Image-Removed>)\\
\\
Insights\\
\\
**The Art Behind Training Gen AI Models: An Interview with Leonardo.Ai’s Lead AI Researcher & Co-founder, Ethan Smith**\\
\\
Following the launch of our latest image generation model, Lucid Origin, and in light of its...](https://leonardo.ai/news/the-art-behind-training-gen-ai-models/) [![](<Base64-Image-Removed>)\\
\\
Insights\\
\\
**The 6 Best Midjourney Alternatives to Try (Free & Paid)**\\
\\
Midjourney is a popular text-to-image and image-to-image generator. It’s won art competitions and set copyright precedent...](https://leonardo.ai/news/midjourney-alternatives/)

### Get started with Leonardo.AI

Explore powerful tools designed to help you generate, edit, and share stunning visuals — faster than ever.

[Try it now](https://app.leonardo.ai/image-generation "Try it now")

![](<Base64-Image-Removed>)