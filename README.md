# Index
Here's a list of things I've done. Mainly made for myself, so I can easily reference previous stuff.

1. [GitHub Projects](#github-projects)
2. [Scanlation](#scanlation)

## GitHub projects

### [Tachiyomi extensions](https://github.com/tachiyomiorg/tachiyomi-extensions/)

- 2022-01-06: [Tapas: Added option for author's notes at end of chapter](https://github.com/tachiyomiorg/tachiyomi-extensions/pull/10366)
  > Added a toggle for the Tapas extension that adds two extra pages to chapters with an author's note: One for the heading and one for the note itself.
  > The text is scraped from the Tapas website, polished, wordwrapped and measured and then is sent to the
  > [`placeholder.jp`](https://placehold.jp/en.html) API to be converted to an image that is displayable in Tachiyomi.
- 2022-01-09: [WebToon: Optional author's notes at end of chapters (& a Tapas bugfix)](https://github.com/tachiyomiorg/tachiyomi-extensions/pull/10398)
  > Ported that feature to WebToon too.
- 2022-05-02: [Fix WebToon author's notes](https://github.com/tachiyomiorg/tachiyomi-extensions/pull/11691)
  > WebToon changed their author's notes, so the CSS selectors to scrape the text had to be updated.
- 2022-09-02: [Fix WebToon & Tapas Author's Notes](https://github.com/tachiyomiorg/tachiyomi-extensions/pull/13304)
  > The [`placeholder.jp`](https://placehold.jp/en.html) API went down, so I switched to another API, [`fakeimg.pl`](https://fakeimg.pl).
  > That looked good, but [@stevenyomi](https://github.com/stevenyomi) suggested a piece of code that would be able to generate the image
  > locally on the users' device itself!
  > A couple of hours later, after messing around with that code snippet, I had a working prototype!
  > After that, it was only a matter of polish, which I did after a break. \
  > The advantages of this new method are many:
  > - No need to rely on a 3rd part service anymore!!
  > - The word wrapping is done by Android itself and is now actually good! The previous method was just a hackjob approximation.
  > - Only one image is now needed for both the heading and author's note itself, because both can be drawn to the same image.
  > So now the author's notes of both WebToon and Tapas look and work exquisitly! :D
  
### [Anime Girls Holding Programming Books](https://github.com/cat-milk/Anime-Girls-Holding-Programming-Books/)
- 2022-01-19: [Add Kitagawa Marin Holding Two Books: "The C Programming Language" and "The Nature of Code"](https://github.com/cat-milk/Anime-Girls-Holding-Programming-Books/pull/287)
  > A couple of friends and I were watching the My Dress-Up Darling anime, and when we saw this frame, we instantly we knew it could be Used.
  > I spend the next couple of hours painting in Krita to put in the books. I made sure to make the Krita file modular,
  > so I can very easily add in any book I wish, just by swapping out the cover image.

---

## Scanlation

I'm also a scanlator specializing in redrawing, but I can also typeset and proofread. Basically, everything except for the actual translating. (I can read Hiragana and Katakana, though)

### Brutalbot Scans
- 2021-06-23 - now: [Beast Tamer](https://mangadex.org/title/d0c60a11-0106-45cf-abfc-d131cb49868f/beast-tamer) (Chapter 27 and up)
  > Tasks: CL, RD,
- 2021-12-21 - now: [Ossan](https://mangadex.org/title/53282330-8754-44db-943f-958a6620b401/ossan-yuusha-to-maou-wo-hirou) (Chapter 11 and up)
  > Tasks: CL, RD, TS, (PR)
### knight heron
- 2022-01-16 - 2022-01-23 (Release: 2022-02-10): [Our 15 minute secret garden (Kumosuzume oneshot)](https://dynasty-scans.com/chapters/our_15_minute_secret_garden)
  > Tasks: RD
- 2022-02-27 - 2022-04-22 (Release: 2022-05-25): [Fall for me and dye me red (Nakano Mayaka oneshot)](https://dynasty-scans.com/chapters/fall_for_me_and_dye_me_red)
  > Tasks: RD
- 2022-04-30 - 2022-07-18 (Release: TBA) 
  > Tasks: RD
