# Reporting an issue

[Public support repository](https://github.com/Astro-Atomica/Minecraft-Block-Graph-Public) · [Browse existing reports](https://github.com/Astro-Atomica/Minecraft-Block-Graph-Public/issues) · [Back to the support overview](../README.md)

You can report bugs, Minecraft data corrections, and feature requests through the contact form without a GitHub account or site login. Mention **The Block Graph** and include the relevant details below. Contact reports are private and do not automatically create a public issue. Reading this repository and its issues requires no login. [GitHub report forms](https://github.com/Astro-Atomica/Minecraft-Block-Graph-Public/issues/new/choose), comments, and subscriptions require GitHub sign-in.

Report one distinct problem per issue. Related symptoms of the same problem can stay together.

## Website bugs

Include:

- **Page:** paste the full affected URL. Include the resource or farm name if the URL does not identify it.
- **Edition:** Java or Bedrock as selected on the website.
- **Website build:** copy the release version and Build number from the footer. If the page will not load, say so.
- **Environment:** browser name/version, operating system, and device. For layout issues, mention portrait/landscape, browser zoom, or approximate window size when relevant.
- **Steps:** a short numbered sequence from opening the page to seeing the problem.
- **Result:** what you expected and what actually happened, including any visible error text.

The home page is an introduction; the tools have their own URLs. Open the tool where the problem happens and copy that address. Clicking the logo/title returns to the introduction. Links and edition selections are useful reproduction details; you do not need to include the website's source code.

For a page without a version footer, open [website release metadata](https://blockgraph.projects.astroatomica.net/release.json) and copy `releaseVersion`, `buildNumber`, and `releaseDate`. The release date uses UTC and can differ from your local calendar date. If you kept an app tab open through an update, note the build in that tab as well as the metadata; they may differ. The website build and the Minecraft dataset/game version are separate numbers.

Example of a useful description (illustrative, not a known bug):

> On Progression with Bedrock selected, I added a crafting-table goal, entered four oak planks, and chose Inventory solution. I expected a plan to craft the table, but the goal remained unsolved. It happens again with a new plan. The attached plan contains my starting items and goal.

If you try reloading or another browser, include the result. Export any important plan or draft before clearing browser storage: saved state can be necessary to reproduce the problem.

## Loading, appearance, and accessibility problems

If a page is blank, stuck loading, or displays a retry message, include the URL, visible error, approximate time and time zone, and whether it happens again after a normal reload. Say whether the introduction loads and which tool fails. If you already use extensions, content blockers, a VPN, or restricted networking, mention anything relevant; changing those settings is not required to file a report. Do not clear saved plans just to report a loading failure.

For appearance issues, include **Day** or **Night**, your browser zoom and approximate screen/window size, and which control is clipped or hard to read. For keyboard or assistive-technology problems, describe the keys you pressed, where focus moved, and the screen reader if applicable. A text description is sufficient when you cannot provide a screenshot.

## Solver and saved-plan problems

On Progression, use **Save plan** to download the existing JSON export. Review its contents, then attach the file if GitHub accepts it, or paste the JSON into a fenced code block. Include:

- The goals, starting inventory and quantities, and placed base blocks/stations.
- Whether you used **Inventory solution** or **All paths**.
- The operation or missing material that looks wrong, and what you expected instead.

The export helps reproduce your inputs; it is not a screenshot of the solver result. Include the result separately. For a blueprint problem, include an export if that tool offers one, or a screenshot and the steps you used to build it.

## Minecraft data corrections

Identify the affected resource, recipe, trade, loot source, acquisition route, or farm. An identifier such as `minecraft:oak_log` is helpful if you know it, but a visible name is enough.

State:

1. What the website currently says or shows.
2. What should change, including whether it affects Java, Bedrock, or both.
3. The website's dataset version (shown in the footer or [dataset manifest](https://blockgraph.projects.astroatomica.net/data/manifest.json)).
4. Your actual game edition/version, if you tested the behavior.
5. Evidence: a relevant release note, official documentation, Minecraft Wiki page, or your own reproduction steps and screenshots/video.

For in-game observations, include relevant conditions such as biome, dimension, difficulty, tools/enchantments, and any mods, add-ons, experiments, or commands. Say if you have not tested the claim. A video demonstrating another edition or version is useful context, but does not establish behavior in the website's selected version.

A missing source reference, a missing route, and a farm that fails in-game are different findings. Explain which you observed; we can investigate from there.

## Feature requests

Explain what you are trying to accomplish, where the current experience gets in the way, and an example of how the improvement would help. Include any workaround you use. Mockups and implementation suggestions are optional.

## Screenshots and attachments

Screenshots should show the affected control or diagram and enough surrounding context to locate it. Add a text description so the report is understandable without the image. Short recordings can help with problems involving interaction or animation.

Review attachments and copied logs before posting. Remove personal information, account details, credentials, and unrelated browser or desktop content. Do not post a full browser-storage dump. Use [Contact Astro Atomica](https://www.astroatomica.com/contact) for private information.
