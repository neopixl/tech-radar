<!-- omit in toc -->
# Contributing to the Tech Radar

First off, thanks for taking the time to contribute! ❤️

All types of contributions are encouraged and valued. See the [Table of Contents](#table-of-contents) for different ways to help and details about how this project handles them. Please make sure to read the relevant section before making your contribution. It will make it a lot easier for us maintainers and smooth out the experience for all involved. The community looks forward to your contributions. 🎉

<!-- omit in toc -->
## Table of Contents

- [I Have a Question](#i-have-a-question)
- [I Want To Contribute](#i-want-to-contribute)
- [Reporting Bugs](#reporting-bugs)
- [Suggesting Enhancements](#suggesting-enhancements)
- [Your First Code Contribution](#your-first-code-contribution)
- [Improving The Documentation](#improving-the-documentation)
- [Styleguides](#styleguides)
- [Commit Messages](#commit-messages)
- [Join The Project Team](#join-the-project-team)



## I Have a Question

> If you want to ask a question, we assume that you have read the available [ReadMe](README.md) first.

Before you ask a question, it is best to search for existing [Issues](/issues) that might help you. In case you have found a suitable issue and still need clarification, you can write your question in this issue, or reach out to us in the company slack. It is also advisable to search the internet for answers first.

If you then still feel the need to ask a question and need clarification, we recommend the following:

- Open an [Issue](/issues/new).
- Provide as much context as you can about what you're running into.
- Provide project and platform versions (nodejs, npm, etc), depending on what seems relevant.

We will then take care of the issue as soon as possible.

## I Want To Submitting a New Technology

Adding technologies to the tech radar works through the Github issues system. When you feel like a new technology should be added (or moved to another quadrant), you can open a new [Issue](/issues/new?assignees=&labels=new-tech&projects=&template=new-technology.md&title=%5BTECH%5D+Name+of+your+tech) with the proper template, and submit it for review to the team of lead developers. 

## I Want To Write Content For a New Technology

If you have some free time and you want to help us improve the content of this tech radar, thank you :heart:!

First, please browse the techs that need writers. You can filter the [Issues](/issues?q=is%3Aopen+is%3Aissue+label%3Anew-tech+label%3A"writers+needed") by looking at the *writers needed* label.

<!-- omit in toc -->
### Fork the Repository

Unless you have direct access to this repository, you will need to fork it on your own Github account. 

<!-- omit in toc -->
### Create the page

Under the `radar` folder, please use a sub-folder with the current date (in ISO format, YYYY-MM-DD). Create one if it doesn't exist yet. Inside that folder, create new markdown (`.md`) file. 

Please use the kebab-cased technology name as the filename. 

<!-- omit in toc -->
### Writing Content

> [!IMPORTANT]
> All content **must** be written in English.
> Please do not disclose any private information (customer related information, keys...)

The items are documented in Markdown format (.md).

Each file contains a [front-matter](https://github.com/jxson/front-matter) header listing the attributes of the item:

```
---
title:      "Dagger"
ring:       hold
quadrant:   Android
---

Text goes here. You can use **markdown** formatting.
```

Following front-matter attributes are possible:

- **title**: Name of the Item
- **quadrant**: Quadrant. One of `Android`,
  `iOS`, `tools`, `React`
- **ring**: Ring section in radar. One of `trial`, `assess`, `adopt`, `hold`
- **info**: (optional) A short textual description of the item (visible in
  overview pages)
- **featured**: (optional, default "true") If you set this to `false`, the item will not be visible in the radar quadrants but still be available in the overview.
- **tags**: (Optional) You can add tags inside square brackets [], separated by commas. For example, [Animations, React Native]. These tags aid in research. Ensure all tags start with the first letter capitalized. Please verify that your tag doesn't already exist in another file.

The name of the .md file serves as the item identifier and may overwrite items with the same name from older releases.

If an item is overwritten in a new release, the attributes from the new item are merged with the old ones, and a new history entry is created for that item.

You can integrate images into your markdown by placing the image files in your public folder and referencing them.

```
![nice image](/images/nice-image.png)
```

<!-- omit in toc -->
### Pull Request
Create your file with the content, and then submit a pull request. 
Depending on the technology, you can assign it to a lead developer. 

If the pull request is accepted, it will be merged, and the Tech Radar will be updated automatically. 
If it's rejected, a comment will be added to guide you in editing the MD file correctly.

### Reporting Bugs

<!-- omit in toc -->
#### Before Submitting a Bug Report

A good bug report shouldn't leave others needing to chase you up for more information. Therefore, we ask you to investigate carefully, collect information and describe the issue in detail in your report. Please complete the following steps in advance to help us fix any potential bug as fast as possible.

- Make sure that you are using the latest version.
- Determine if your bug is really a bug and not an error on your side e.g. using incompatible environment components/versions (Make sure that you have read the [documentation](). If you are looking for support, you might want to check [this section](#i-have-a-question)).
- To see if other users have experienced (and potentially already solved) the same issue you are having, check if there is not already a bug report existing for your bug or error in the [bug tracker](issues?q=label%3Abug).
- Also make sure to search the internet (including Stack Overflow) to see if users outside of the GitHub community have discussed the issue.
- Collect information about the bug:
- Stack trace (Traceback)
- OS, Platform and Version (Windows, Linux, macOS, x86, ARM)
- Version of the interpreter, compiler, SDK, runtime environment, package manager, depending on what seems relevant.
- Possibly your input and the output
- Can you reliably reproduce the issue? And can you also reproduce it with older versions?

<!-- omit in toc -->
#### How Do I Submit a Good Bug Report?

> You must never report security related issues, vulnerabilities or bugs including sensitive information to the issue tracker, or elsewhere in public. Instead sensitive bugs must be sent by email to <>.
<!-- You may add a PGP key to allow the messages to be sent encrypted as well. -->

We use GitHub issues to track bugs and errors. If you run into an issue with the project:

- Open an [Issue](/issues/new). (Since we can't be sure at this point whether it is a bug or not, we ask you not to talk about a bug yet and not to label the issue.)
- Explain the behavior you would expect and the actual behavior.
- Please provide as much context as possible and describe the *reproduction steps* that someone else can follow to recreate the issue on their own. This usually includes your code. For good bug reports you should isolate the problem and create a reduced test case.
- Provide the information you collected in the previous section.

Once it's filed:

- The project team will label the issue accordingly.
- A team member will try to reproduce the issue with your provided steps. If there are no reproduction steps or no obvious way to reproduce the issue, the team will ask you for those steps and mark the issue as `needs-repro`. Bugs with the `needs-repro` tag will not be addressed until they are reproduced.
- If the team is able to reproduce the issue, it will be marked `needs-fix`, as well as possibly other tags (such as `critical`), and the issue will be left to be implemented by someone.

### Suggesting Enhancements

This section guides you through submitting an enhancement suggestion for ts, **including completely new features and minor improvements to existing functionality**. Following these guidelines will help maintainers and the community to understand your suggestion and find related suggestions.

<!-- omit in toc -->
#### Before Submitting an Enhancement

- Make sure that you are using the latest version.
- Read the [documentation]() carefully and find out if the functionality is already covered, maybe by an individual configuration.
- Perform a [search](/issues) to see if the enhancement has already been suggested. If it has, add a comment to the existing issue instead of opening a new one.
- Find out whether your idea fits with the scope and aims of the project. It's up to you to make a strong case to convince the project's developers of the merits of this feature. Keep in mind that we want features that will be useful to the majority of our users and not just a small subset. If you're just targeting a minority of users, consider writing an add-on/plugin library.

<!-- omit in toc -->
#### How Do I Submit a Good Enhancement Suggestion?

Enhancement suggestions are tracked as [GitHub issues](/issues).

- Use a **clear and descriptive title** for the issue to identify the suggestion.
- Provide a **step-by-step description of the suggested enhancement** in as many details as possible.
- **Describe the current behavior** and **explain which behavior you expected to see instead** and why. At this point you can also tell which alternatives do not work for you.
- You may want to **include screenshots and animated GIFs** which help you demonstrate the steps or point out the part which the suggestion is related to. You can use [this tool](https://www.cockos.com/licecap/) to record GIFs on macOS and Windows, and [this tool](https://github.com/colinkeenan/silentcast) or [this tool](https://github.com/GNOME/byzanz) on Linux. <!-- this should only be included if the project has a GUI -->
- **Explain why this enhancement would be useful** to most ts users. You may also want to point out the other projects that solved it better and which could serve as inspiration.

## Styleguides
### Commit Messages
Commit messages should follow the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/).