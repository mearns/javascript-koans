# Contributing to Javascript Koans

All contributions that are accepted into the JavaScript Koans are released to the public domain
under the license of the work. By submitting a pull request, you are releasing your work under
the same conditions.

## Additions

If you hve new koans, please add them to the end of the `koans.md` file in the appropriate
language, give the koan a unique numeric ID preceding the title (unless there is a good reason
not too, the ID should follow as an incrementing 0-padded decimal number from the previous koan),
and submit a pull request to have your koan considered for addition.

Please keep in mind the spirit of the koans, and the following conventions and guidelines:

* Koans are best when they are relatively short and simple, but not obvious. Koans are intended
  for meditation and study. However, a skilled JavaScript practitioner should be able to make
  sense of your koan.
* Hypothetical or proverbial subjects in the koan should be gender unspecified, using "they" as
  the gender neutral pronoun.
* Make limited use of real persons in your koans; when doing so, use a neutral to slightly positive
  presentation of the individual.
* Libel or abusive language or content will not be accepted.

## Modifications

Modifications will be carefully considered, but in general, koans are not intended to be modified
after publication. Minor changes may be accepted, but any changes more signficant than
punctionation or small, inconsequential word choices are not likely to be made. If there is a
compelling reason to change a published koan in a signficant way, the more likely course of action
is to deprecate the old koan and publish the new version as a new koan.

## Translations

We would love to reach more people by having our koans translating into more languages. If you
are fluent in a language and are comfortable with both the nuances of the language and the nuances
of the koans, please consider translating some of the koans and sending a pull request to get it
merged in.

Koans are organized into folder by [IETF language tags](https://tools.ietf.org/html/rfc5646) under
the root `koans/` directory: the first level directory is the primary language subtag (e.g., `en/`
for English language), and the second level directory is the full language tag, repeating the
primary language tag for clarity (e.g., `en/en-US` for English language as used in the United
States). For language tags with more than two subtags, please only use these three levels of
organization (e.g., koans written in the Serbian language with Latin script for, for use in Serbia
would be placed under `koans/sr/st-Latn-RS/`).

Koans are uniquely identified by the numeric ID string preceding the title. There is no specific
meaning to these IDs, except they mut be unique to the koan. When translating koans, the title
and content of the koan should be translated into the target language, but the numeric ID of the
koan should be preserved verbatim so it can be identified across translations. This includes both
the language, writing conventions, and character set.
