# Recursive Screenshot Prompts

A compact open-source prompt pack for creating a recursive chain of realistic mobile screenshots:

1. Instagram DM screenshot with a realistic Coca-Cola photo
2. ChatGPT app screenshot containing the Instagram DM image
3. ChatGPT Thinking screenshot containing the previous ChatGPT image
4. Reddit post screenshot containing the nested ChatGPT image
5. Final ChatGPT screenshot containing the Reddit screenshot

The prompts are written to emphasize realistic iPhone proportions, readable text, authentic app-like spacing, and clean English-only UI details.

## Prompt List

| # | Prompt | File |
|---|---|---|
| 1 | Instagram DM screenshot | [prompts/01-instagram-dm-screenshot.md](prompts/01-instagram-dm-screenshot.md) |
| 2 | ChatGPT app showing the Instagram DM image | [prompts/02-chatgpt-app-instagram-dm-image.md](prompts/02-chatgpt-app-instagram-dm-image.md) |
| 3 | ChatGPT Thinking screenshot with nested ChatGPT image | [prompts/03-chatgpt-thinking-nested-image.md](prompts/03-chatgpt-thinking-nested-image.md) |
| 4 | Reddit post containing the nested image | [prompts/04-reddit-post-nested-image.md](prompts/04-reddit-post-nested-image.md) |
| 5 | Final ChatGPT screenshot containing the Reddit screenshot | [prompts/05-final-chatgpt-reddit-screenshot.md](prompts/05-final-chatgpt-reddit-screenshot.md) |

You can also read the whole sequence in [prompts/all-prompts.md](prompts/all-prompts.md).

## How To Use

Use each prompt as a standalone image-generation prompt, or generate them in order to preserve the recursive visual logic.

Recommended sequence:

1. Generate Prompt 1 first.
2. Use the resulting image as the embedded reference for Prompt 2.
3. Use the Prompt 2 result as the nested reference for Prompt 3.
4. Use the Prompt 3 result inside Prompt 4.
5. Use the Prompt 4 result inside Prompt 5.

For the cleanest results, keep the output format vertical, iPhone-like, and screenshot-first. Avoid adding poster composition, marketing layout, watermarks, captions, or extra UI.

## Notes

- These prompts reference third-party product names and interface styles for descriptive purposes only.
- This project is not affiliated with Instagram, Meta, OpenAI, ChatGPT, Reddit, or Coca-Cola.
- Generated outputs should be used responsibly and should not be presented as real private conversations or official app screenshots.

## License

MIT. See [LICENSE](LICENSE).
