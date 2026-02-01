# 0.9.16

- Add support for creature selection for encounters

# 0.9.15

- Add support for assigning SRD-related spells to spellcasters

# 0.9.14

- Increase Context size limit from 2,500 to 8,000 characters
- Increase overall limit from 12,000 to 50,000 characters
- Add Discovery as an encounter type
- Add a "Get More?" CTA in Usage

# 0.9.13

- Adds (beta) support for generating Simple Hazards
- Adds an explicit level selector for NPCs/Creatures
- Significant amount of code refactoring to allow for easier implementation of new modules in the future (such as Vehicles)

# 0.9.12

- Adds support for generating Auras on actors
- Introduces feature gating support so that old clients won't generate broken Auras

# 0.9.11

- Support the detached browser flow required for authentication by Electron app users

# 0.9.10

- When images fail to generate due to moderation errors, allow the generation to complete without an image and report it properly

# 0.9.9

- Add support for opting out of AI image generation

# 0.9.8

- Add support for client-side inclusion of standard actions such as push, trip, grapple, etc.
- Add support for effect item creation to automate actions
- Numerous minor bug fixes

# 0.9.7

- Improve handling of defaults to be world-specific where appropriate
- Default the creation type based on the tab used to open the app
- Add command line tools for support to make state inspection easy

# 0.9.6

- Add support for saved and reusable contexts
- Add moderation support for context prompts

# 0.9.5

- Add support for encounter generation
- Change image generation to gpt-image-1 model
- Set the maximum release to 13
- Numerous stability improvements, minor fixes, and enhancements

# 0.9.4

- Bump the minimum verified release to 13.345

# 0.9.3

- Open the form immediately and handle authentication asynchronously
- Provide immediate feedback when submitting a creation
- Fix v13 progress bar compatibility issues

# 0.9.2

- Initial beta release
