## Maintainer Guide

This document lists the responsibilities and resources available to maintainers of the Solidity documentation translation forks.

### Maintainer Responsibilities

As maintainers of one of the Solidity doc translations we ask you to please:
- Track the process of the translation in the [translation progress checklist](https://github.com/solidity-docs/translation-guide/blob/main/progress-checklist.md).
- Review PRs made by contributors in a timely manner.
- Make sure that the translations follow the [translation style guide](https://docs.soliditylang.org/en/latest/contributing.html#documentation-style-guide) outlined in the Solidity docs.
- Regularly check if the translation is up-to-date.
- Inform the Solidity team once your translation has reached the state where it can be published by adding it to the Solidity docs.
- Act as point of contact for your language and answer questions from both contributors to your language and the core Solidity team.

### Tips

#### File, Tags and Reference Names
Please do not change the names of the files and also keep the names of all tags and references. 

There are some special [Sphinx](https://docs.readthedocs.io/en/stable/intro/getting-started-with-sphinx.html) markup syntax to look for such as:
- [References](https://www.sphinx-doc.org/en/master/usage/restructuredtext/roles.html#cross-referencing-arbitrary-locations): `.. _translations:` and `:ref:_translations`
- [Paragraph Level Markup](https://www.sphinx-doc.org/en/master/usage/restructuredtext/directives.html#paragraph-level-markup): `.. note::` , `.. warning::`

#### Glossary
Consider making a glossary of the translations of technical and Solidity-specific terms. Put this in a highly visible location (the README or a pinned issue).

#### Language-Specific Style Guide
If needed, you can create a language-specific style guide to define additional rules to follow when translating. See the general [Solidity docs style guide](https://docs.soliditylang.org/en/latest/contributing.html#documentation-style-guide) for rules that should apply to all translations.

#### Review Process

Decide how many reviewers you want to review each translated page before it can be merged. If your team is small and busy, you may only be able to have one reviewer so that translators don't get blocked. If your team is bigger, consider having two reviewers so you have a stronger guarantee that the page is correct.

#### Translatable Files

If you like, you can create translatable files following [this readthedocs translations guide](https://docs.readthedocs.io/en/stable/guides/manage-translations.html#create-translatable-files). While these can be helpful for some, they are not necessarily needed to translate the documentation.

#### Machine Translations

Machine translations (e.g. using [DeepL](https://www.deepl.com/translator)) can help get big texts translated more quickly. Please make sure to carefully proof-read all machine translations since especially technical terms might not be reflected correctly.
 
### Need Help or Have Questions?
If you have a question that isn't addressed here, you can visit the [Documentation category](https://forum.soliditylang.org/c/documentation/8) of the Solidity forum and ask for help!

You can also reach out to us in the solidity-dev [Gitter](https://gitter.com/ethereum/solidity) or [Matrix](https://matrix.to/#/#ethereum_solidity:gitter.im) chat.

_Credits: This doc is derived from the [Maintainer Guide](https://github.com/reactjs/reactjs.org-translation/blob/master/maintainer-guide.md) of the ReactJS Localization Team._
