# Changelog — Carnot 2026 workshop site

Bump the version in three places when you change the site:
`index.html` header comment, the footer line (`class="ver"`), and here.

## v0.39 — 22 September 2026
- "Poster session and reception" is now "Poster session and light
  reception", noting that dinner follows, so nobody fills up on the
  reception; the poster section says the same
- "Transport to dinner" is now "Coach to the restaurant", described as a
  group bus from the PAIS building and back afterwards

## v0.38 — 22 September 2026
- Triton Photonics logo (their light lockup, for dark grounds) replaces the
  text placeholder in the sponsor panel

## v0.37 — 22 September 2026
- Markus Hehlen's affiliation changed from Los Alamos National Laboratory
  to Triton Photonics

## v0.36 — 22 September 2026
- Removed every mention of a forty-place limit, so a bigger room stays an
  option: the hero notice, the registration lede, the "Capacity" row, the
  venue's Registration and Room rows, the PAIS 1010 photo caption, and
  maximumAttendeeCapacity in the schema.org data

## v0.35 — 22 September 2026
- Premise section cut from about 290 words to about 125. It no longer
  mentions photons at all: the opening states the physics directly — a
  single-mode pump against broadband, isotropic fluorescence, and the
  difference in entropy between those two light fields — rather than
  leading with a slogan or with the correction of one
- The three operating points now appear in the same order as the diagram
  beside them, one clause each
- Hero notice no longer reads as if email were a way to register: "Register
  here. Questions: carnot.workshop@gmail.com"
- Dropped the paragraph on thermal lensing, stress and linewidth down to one
  sentence; the history paragraph is two short sentences

## v0.34 — 22 September 2026
- Organizing committees lay out four across on wide screens (two on tablets,
  one on phones), so each committee is a single row instead of three plus
  an orphan. "New Mexico", "Notre Dame" and "Maxwell Labs" are bound with
  non-breaking spaces so the narrower cards never split them
- UNM Physics & Astronomy's official logo replaces the text lockup in the
  sponsor panel, on a white tile so the mark itself is not recoloured
- Triton Photonics added under "With support from", linked to
  tritonphotonics.com, and to the schema.org sponsor list. Shown as a name
  until the logo file is in hand

## v0.33 — 22 September 2026
- Registration is live: the button and the schema.org Offer point at the
  final form (forms.gle/A5s9j5ocgsVA1uSt9); hero notice and section heading
  say "Registration is open"
- Program has a definite end: 08:00 Saturday to 15:00 Sunday, stated in the
  program introduction. The program closes at 14:00 and the optional
  laboratory tours run to 15:00. schema.org endDate and the .ics DTEND
  (with SEQUENCE bumped so calendars pick up the change) both now say 15:00
- Saturday rebuilt: registration, arrival and coffee from 08:00; opening
  shortened to 20 minutes; 15-minute workshop photograph straight after
  lunch; poster session 75 minutes; 15 minutes of coach transport before
  dinner, which is now seated at 19:35. Coffee breaks left where they are
  until the talk sign-ups are in
- Sunday opens with registration, arrival and coffee at 09:00. Laboratory
  tours moved from the Saturday poster session to Sunday afternoon; the
  closing row reads "Lab tours / adjourn". The note about possibly moving
  the tours is gone
- "Round-table" renamed "Panel discussion" throughout, including Joel
  Bixler's speaker tag
- Removed the "posters on display" note from lunch, and the claim that
  posters go up alongside the talks
- Session III theme no longer says "the stall point"; it names the pump
  wavelength at which quantum-defect heating and anti-Stokes cooling cancel
- Ghazaleh Ansari added to the local organizing committee
- Sponsor logos are links: Maxwell Labs, SELA Photonics and UNM Physics &
  Astronomy
- Hot-air balloons: the envelope now closes at a throat and the ropes hang
  from it to the basket; previously they started in mid-air beside the
  envelope

## v0.32 — 14 September 2026
- Corrected the premise section. It opened "Photons carry entropy", which is
  wrong — entropy is a property of a field or an ensemble, not of a single
  quantum. Rewritten around the asymmetry that actually does the work: the
  pump is one narrow directional mode carrying almost no entropy, the
  fluorescence is broadband and isotropic across an enormous number of modes
- The three operating points are now stated mechanistically rather than
  metaphorically: quantum-defect heating, pumping red of the mean fluorescence
  wavelength, and the pump wavelength at which the two cancel. "Run it in
  reverse" and "the stall point" are gone from both the prose and the diagram
- The linewidth claim is now posed as an open question rather than a settled
  result, which is what it is

## v0.31 — 13 September 2026
- Registration held back: the form link is removed again while the form is
  rebuilt. The registration card keeps its button in place, styled as a
  pending outline reading "Registration form — opening shortly", so the
  section still tells people where to look
- Hero notice and section heading reworded from "Registration is open" to
  "opens in the next few days"; email offered as a way to reserve a place
  in the meantime
- schema.org Offer now points at the site's own #register section rather
  than a form URL that is not public
- Corrected two stale claims that contradicted the form: abstracts are not
  submitted with registration, and the form takes three minutes, not five

## v0.30 — 13 September 2026
- Registration form is live: the `REGISTRATION_FORM_URL` placeholder replaced
  with the published Google Form in both the registration section's button and
  the schema.org Offer block

## v0.29 — 13 September 2026
- Joel Bixler's profile updated at his request: affiliation changed from Air
  Force Research Laboratory to Air Force Office of Scientific Research, and the
  interests line replaced with his current role, Program Officer for the
  High-Energy Radiation-Matter Systems (HERMES) portfolio

## v0.28 — 12 September 2026
- Registration section added between the poster session and the venue: free,
  forty places, 10 October deadline, poster abstracts submitted with the
  registration, and a card linking to the Google Form
- Hero notice changed from "Registration opens shortly" to "Registration is
  open", pointing at the new section; the venue block's Registration row and
  the navigation follow
- JSON-LD gains `isAccessibleForFree`, `maximumAttendeeCapacity` and a zero-price
  `Offer`, so search engines can show the workshop as a free event
- The form URL appears twice in index.html as the placeholder
  REGISTRATION_FORM_URL — replace both before publishing

## v0.27 — 9 September 2026
- Two photographs added: Albuquerque seen from the crest of the Sandias, which
  now leads the "extra day" row and illustrates the tramway entry beside it,
  and the Sandias lit gold at the end of the day, paired with the red rock in
  the venue column
- Crops tightened: the crest shot loses most of its empty upper sky so the city
  and the rock ledge carry the frame; the red rock re-cropped to 4:3 to match
  its new partner
- The "extra day" gallery is pinned to four columns (two, then one, as the
  viewport narrows) so the fourth photograph no longer orphans onto its own row

## v0.26 — 9 September 2026
- The PAIS 1010 photograph moved up into the empty space beside the programme
  heading, where it does more work: it is the room every item on the timetable
  happens in
- Removed from "The building" gallery rather than shown twice on one page, so
  that gallery is now the atrium and the courtyard — the spaces around the room

## v0.25 — 9 September 2026
- New Mexico photographs fill the empty right-hand column of the venue block:
  cholla at sunset, ristras at a roadside stand, and red rock with juniper,
  stacked under the PAIS exterior shot
- A second gallery under "If you can stay an extra day" — Taos Pueblo, adobe
  and vigas in Santa Fe, volcanic rock on the way toward Los Alamos — cropped
  16:9 to match the building gallery above it
- All six ship as separate lazy-loaded files under photos/, so index.html does
  not grow; footer photo credit widened to "PAIS and New Mexico"

## v0.24 — 9 September 2026
- Alejandro Rodriguez portrait added; every name on the page now carries a
  face, and no initials monograms remain outside the speakers grid

## v0.23 — 9 September 2026
- Portraits added for the local organizing committee: Alexander Albrecht,
  Max Gardner and Morteza Darvishi. Alejandro Rodriguez is the last remaining
  initials monogram

## v0.22 — 9 September 2026
- Committee cards now carry circular portraits, so attendees can put faces to
  the people running the workshop — particularly the local committee, who are
  not introduced anywhere else on the page
- Seletskiy, Kuno and Pauzauskie reuse the portraits already inlined in their
  speaker cards, so the page gains no weight for those three
- Rodriguez, Albrecht, Gardner and Darvishi show initials monograms on brand
  navy until photographs arrive — swap the placeholder for an <img> in the
  matching .org-av block

## v0.21 — 9 September 2026
- Fixed: the Maxwell Labs chip overlapped the facts row on wide screens. The
  hero rail had been absolutely positioned at a fixed offset from the hero's
  bottom edge; v0.19's registration notice grew that edge and pushed the rail
  up into the text. The rail is now a real grid column, so anything added below
  it moves the layout rather than colliding with it

## v0.20 — 9 September 2026
- LinkedIn event linked from the site: the hero notice now offers both routes
  ("Join the LinkedIn event or email carnot.workshop@gmail.com"), matched in
  the venue block's Registration row and the footer
- `sameAs` added to the Event JSON-LD pointing at the LinkedIn event, so search
  engines treat the two listings as one event rather than competing ones

## v0.19 — 9 September 2026
- Registration notice added to the hero, directly under the facts row and above
  the fold on both desktop and mobile: "Registration opens shortly. Write to
  carnot.workshop@gmail.com to be notified."
- carnot.workshop@gmail.com wired in as the workshop's contact address — the
  hero notice, the Registration row in the venue block, the sponsors paragraph
  (previously "contact the organizing committee" with no address), and the
  footer

## v0.18 — 9 September 2026
- The site is public: the `<meta name="robots" content="noindex, nofollow">`
  line is gone, so search engines can index the page
- Open Graph URLs made absolute (`og:image`) and `og:url` added, so LinkedIn
  and X resolve the link preview reliably. Re-run the URL through LinkedIn's
  Post Inspector after any future change to these tags
- `Event` structured data (schema.org JSON-LD) added — dates, venue, organizer
  and sponsors — making the workshop eligible for Google event listings
- `carnot-2026.ics` added with an "Add the workshop to your calendar" link in
  the venue block
- README updated to match

## v0.17 — 8 September 2026
- The fourteenth invited talk now has a name: Pengning Chao (Maxwell Labs)
  replaces the "To be announced" placeholder; talk title still to come
- Local organizing committee and the new speaker carried onto the printed
  poster, which also picks up the site's "Workshop sponsor" wording

## v0.16 — 4 September 2026
- Page reordered: Speakers now comes before the Tentative program, with the
  Sponsors panel between them. The program then runs into the poster session
  and the venue, so the room photographs follow naturally from the schedule
- Section backgrounds re-balanced to keep the tinted/white alternation intact
  (Speakers on tint, Sponsors on white); the program keeps the tinted ground
  its white day cards need for contrast
- Navigation reordered to match

## v0.15 — 4 September 2026
- Format fact no longer states a headcount: "~30 people" became
  "discussion-focused". The number read as a cap on attendance and also
  contradicted PAIS 1010's 40 seats; room capacity now lives only in the
  venue section, where it belongs as a fact about the room

## v0.14 — 4 September 2026
- Hero now uses the empty right side on wide screens: "Organized by" (the four
  committee members) and "Sponsored by" with the Maxwell Labs logo on a navy
  chip linking to the sponsors section; hidden below 1200px where the space
  does not exist
- Sponsors section moved up the page, from second-to-last to directly after
  the speakers; "Sponsors" added to the navigation

## v0.13 — 4 September 2026
- Fourteenth invited talk reserved for Maxwell Labs (speaker TBA); card added
  to the speakers grid, Session IV extended to 3 × 30 min, Day One afternoon
  shifted by 30 minutes (round-table 16:30, posters 18:00–19:30, dinner 19:30)
- Alejandro Rodriguez (Princeton / Maxwell Labs) added to the organizing
  committee
- Local organizing committee added: Alexander Albrecht, Max Gardner,
  Morteza Darvishi (all UNM)
- Sponsors section rebuilt: Maxwell Labs as workshop sponsor with logo, UNM
  Physics & Astronomy and SELA Photonics under "With support from"; logo
  masters added under brand/
- SELA Photonics credited as sponsor of the poster prizes in the posters
  section

## v0.12 — 1 September 2026
- New confirmed speaker: Michel Digonnet (Stanford), speaking on
  radiation-balanced lasers; card added with portrait
- Session III (Radiation-balanced lasers) extended to 3 × 30 min; Day One
  afternoon shifted by 30 minutes — Session IV at 14:30, coffee 15:30,
  round-table 16:00, flash talks 17:00, posters 17:30–19:00, dinner 19:00
- Talks renumbered: thirteen invited talks, Day Two now Talks 11–13

## v0.11 — 26 August 2026
- Portraits added for Dragic, Fattahi and Ghonge; all twelve speaker cards now
  carry a photograph, no initials placeholders remain

## v0.10 — 26 August 2026
- Three confirmed speakers added: Peter Dragic (Illinois), Hanieh Fattahi
  (Max Planck Institute for the Science of Light), Sushrut Ghonge (Saint Mary's)
- New Session VI, "Pumping with incoherent light", placed on Day Two morning —
  sun-pumped radiation-balanced lasers, and cooling with broadband light
- Day Two rebuilt around it: session at 09:30, contributed talks 11:15,
  roadmap 12:00, adjourn 14:00
- Program now twelve invited talks, not nine

## v0.9 — 26 August 2026
- PAIS 1010 also has a glass wall onto the inner courtyard — added to the room
  description; the courtyard photo is the view from inside the workshop room

## v0.8 — 26 August 2026
- Corrected: PAIS 1010 has TWO walls of whiteboard, not three
- Posters are in PAIS 1010 with the talks, not the atrium — captions and the
  poster section corrected
- Third photo renamed and recaptioned: it is the inner courtyard, framed as
  somewhere to take the breaks outdoors in late October

## v0.7 — 24 August 2026
- Real photographs of PAIS replace the drawn illustration (own work, no
  licensing question): exterior on the venue block, plus a three-image gallery
  of the atrium, PAIS 1010 and the courtyard break-out space
- Room specification added: PAIS 1010, 40 seats, three walls of whiteboard,
  large projection screen
- Photo credit added to the footer
- Photos ship as separate files under photos/ and load lazily, so the page
  itself stays light

## v0.6 — 24 August 2026
- Copyright line added to the footer, with an explicit carve-out for speaker
  portraits (which belong to the speakers and their institutions, not us)

## v0.5 — 24 August 2026
- Logo replaced with the true vector master (brand/carnot-logo.svg); the hero,
  nav mark and footer are now resolution-independent
- Brand colours corrected to the official values: navy #0A2448, teal #13A8B7,
  amber #F6A21A (previously sampled approximations from a raster)
- Footer no longer ships two themed PNG lockups — one vector inherits the theme
- Favicon regenerated from the vector mark
- Page ~40 KB lighter

## v0.4 — 24 August 2026
- Program: format chips added (talks, flash talks, posters, round-table,
  funding session, lab tours) so the range of the program reads at a glance
- Venue: New Mexico written up properly — the light, the altitude, late October
- New "If you can stay an extra day" block: Sandia Peak Tramway, the VLA,
  Santa Fe and Los Alamos, and the state question

## v0.3 — 24 August 2026
- Travel details corrected and expanded: Sunport is 10 minutes from Hotel Parq
  Central, which runs a complimentary airport shuttle 7:30 am – 10:30 pm
- Route between hotel and PAIS added: free 777 Express bus, or a 25-minute walk
- Removed the unverified "15 minutes from campus" airport estimate

## v0.2 — 23 August 2026
- Arash Mafi corrected to University of Kansas
- Peter Pauzauskie corrected to University of Washington (PNNL removed)
- PAIS street address added: 210 Yale Boulevard NE, Albuquerque, NM 87106
- Hotel Parq Central street address added: 806 Central Avenue SE, Albuquerque, NM 87102
- Map links added: PAIS, Hotel Parq Central, and hotel-to-PAIS directions
- Speakers heading changed from a fixed count to "Confirmed speakers"
- Organizing committee heading simplified
- Version tracking introduced

## v0.1 — 23 August 2026
- Initial site: hero, premise, tentative program, speakers with portraits,
  poster session, venue and travel, organizing committee, sponsors
- Published unlisted at https://carnot-workshop.github.io/
