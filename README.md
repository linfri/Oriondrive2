# Oriondrive 2: The Unbeatable Captcha

The emergence of ChatGPT and other AI-based technologies has stirred up a lot of unease in the creative community. Artists and musicians have voiced their concerns that these technological advancements could make their professions obsolete and, in turn, cut off their main source of income. However, we believe that the human mind and creativity are still and will forever be irreplaceable. To support this notion, we're launching a new project with the aim of creating captchas that only a human being can solve - ones that no automated captcha solver can crack. As an artist/music producer, you are invited to contribute to the first phase of this project!

## Unleash Your Creativity

For this phase of the project, we need you to think of **a phrase** that makes sense, or doesn't, as long as it can be understood by the user. It should be no longer than 4-5 words, just like a captcha. **Record yourself saying the phrase out loud and clearly.** If you prefer, you can run the phrase through text-to-speech, but it would be better if it's your own voice. If you want, you can also record **a music track**, but it should not exceed 10-15 seconds. Once you are done, **send** the voice recording, track and phrase to linn.friberg@pm.me attached to the email.

We'll be adding your track to the repository in three different versions: one with clear voice mixed with music, which should be recognizable by speech-to-text APIs; one with distorted voice mixed with music, which will not be recognized by these APIs; and something in-between; we'll experiment to determine the threshold of recognition. Initially, we'll be using OpenAI's Whisper for transcribing the files and evaluating the results for each track. Every time the model fails to recognize the speech will be a "win for humanity" and the creative community in particular, and we'll be looking into adding other evaluation options (like Google and/or Amazon APIs) to the project later.

As our project advances, the next step is to create a prototype captcha service once we have gathered sufficient data. Whether or not we get to the production stage will depend on the project's progress, but either way we'll have achieved an important milestone. There is no set timeframe for contributing phrases and audio files - the project is open indefinitely.

## Frequently Asked Questions

*I'm a bit skeptical about this project. Could it be possible for someone to develop a model that is able to generalize the submitted material and successfully break through the "unbeatable" captcha?*

The aim of this project is purely educational, so we'd love to see anyone attempt to create a captcha solver for Oriondrive 2. However, it's a bit trickier than it seems - new contributions increase the variability of the data, making it harder to generalize. That's why we keep the project open for contributions - the more the patterns change, the longer it will stay unbeatable. To further complicate it, some of the contributions will disappear from the archive randomly over time to control the data supply and prevent neural networks from gaining an advantage. Don't be alarmed when this happens - the contributions will just be moved to special podcasts, making data collection even more difficult. If this approach would be defeated, we'll definitely come up with another solution!
