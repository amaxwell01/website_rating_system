website_rating_system
=====================

A optional standard's based meta tag to rate websites based on a suggested age of users who can access it. 
This is an optional meta tag which will allow website owners and search engines to better tell the users what 
type of content they are expected to see. If a parent or guardian wants to block all websites with a specific 
website rating, this will make it easier for users to understand what type of material is being block/shown.

###Note:
Leaving this content rating off will default to a G rating.


## G — General Audiences. All Ages Admitted.
A G-rated motion picture contains nothing in theme, language, nudity, sex, violence or other matters that, in the view
of the Rating Board, would offend parents whose younger children view the motion picture. The G rating is not
a "certificate of approval," nor does it signify a "children’s" motion picture. Some snippets of language may go
beyond polite conversation but they are common everyday expressions. No stronger words are present in G-rated motion
pictures. Depictions of violence are minimal. No nudity, sex scenes or drug use are present in the motion picture.
```html
<meta name="web-rating" content="G" />
```

## PG — Parental Guidance Suggested. Some Material May Not Be Suitable For Children.
A PG-rated motion picture should be investigated by parents before they let their younger children attend.
The PG rating indicates, in the view of the Rating Board, that parents may consider some material unsuitable for
their children, and parents should make that decision. The more mature themes in some PG-rated motion pictures may
call for parental guidance. There may be some profanity and some depictions of violence or brief nudity. But these
elements are not deemed so intense as to require that parents be strongly cautioned beyond the suggestion of parental
guidance. There is no drug use content in a PG-rated motion picture.
```html
<meta name="web-rating" content="PG" />
```

## PG-13 — Parents Strongly Cautioned. Some Material May Be Inappropriate For Children Under 13.
A PG-13 rating is a sterner warning by the Rating Board to parents to determine whether their children under age 13
should view the motion picture, as some material might not be suited for them. A PG-13 motion picture may go beyond
the PG rating in theme, violence, nudity, sensuality, language, adult activities or other elements, but does not
reach the restricted R category. The theme of the motion picture by itself will not result in a rating greater than
PG-13, although depictions of activities related to a mature theme may result in a restricted rating for the motion
picture. Any drug use will initially require at least a PG-13 rating. More than brief nudity will require at least
a PG-13 rating, but such nudity in a PG-13 rated motion picture generally will not be sexually oriented. There may
be depictions of violence in a PG-13 movie, but generally not both realistic and extreme or persistent violence. A
motion picture’s single use of one of the harsher sexually-derived words, though only as an expletive, initially
requires at least a PG-13 rating. More than one such expletive requires an R rating, as must even one of those words
used in a sexual context. The Rating Board nevertheless may rate such a motion picture PG-13 if, based on a special
vote by a two-thirds majority, the Raters feel that most American parents would believe that a PG-13 rating is
appropriate because of the context or manner in which the words are used or because the use of those words in the
motion picture is inconspicuous.
```html
<meta name="web-rating" content="PG-13" />
```

## R — Restricted. Children Under 17 Require Accompanying Parent or Adult Guardian.
An R-rated motion picture, in the view of the Rating Board, contains some adult material. An R-rated motion 
picture may include adult themes, adult activity, hard language, intense or persistent violence, 
sexually-oriented nudity, drug abuse or other elements, so that parents are counseled to take this rating very
seriously. Children under 17 are not allowed to attend R-rated motion pictures unaccompanied by a parent or adult
guardian. Parents are strongly urged to find out more about R-rated motion pictures in determining their suitability
for their children. Generally, it is not appropriate for parents to bring their young children with them to R-rated
motion pictures.
```html
<meta name="web-rating" content="R" />
```

## NC-17 — No One 17 and Under Admitted.
An NC-17 rated motion picture is one that, in the view of the Rating Board, most parents would consider patently too
adult for their children 17 and under. No children will be admitted. NC-17 does not mean "obscene" or "pornographic"
in the common or legal meaning of those words, and should not be construed as a negative judgment in any sense. 
The rating simply signals that the content is appropriate only for an adult audience. An NC-17 rating can be based
on violence, sex, aberrational behavior, drug abuse or any other element that most parents would consider too strong
and therefore off-limits for viewing by their children
```html
<meta name="web-rating" content="NC-17" />
```

## XXX — Website contains pornography. 
```html
<meta name="web-rating" content="XXX" />
```