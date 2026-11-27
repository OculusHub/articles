# Distance Vision Test Apps on Google Play: Which Ones Get the Optotypes Right for Accurate Test Result?

*An app review for home users, parents of children aged 6 and above, and healthcare professionals*

## Why accuracy matters

A paper eye chart works because the letters are printed at a precisely defined size for a precisely defined distance. A phone or tablet eye chart only works if the app does the same job: it must know the pixel density of your screen and scale each optotype so that it subtends the correct visual angle at the chosen test distance. Many eye chart apps skip this and either show letters at an arbitrary size or ask you to calibrate with a ruler or a credit card. Others get it wrong silently.

This review covers five apps that display optically precise optotypes **without a ruler or card calibration step by the user (Peek Acuity is the exception: it enforces a quick calibration check, though mostly the optotype is displayed correctly without such calibration)**. Everything else on the store is either inaccurate or needs calibration, so we left it out. We compare the five on two themes:

1. **Accuracy of optotypes**, including how faithfully each app follows the design rules of standard charts.
2. **Practicality**: flexible test distances, app-specific brightness, choice of visual acuity (VA) notations, chart types, in-app help and ease of use.

> A phone app is a screening and monitoring aid, not a replacement for a professional eye examination. Poor results, or any sudden change in vision, should be followed up with an eye care professional.

## At a glance

| App | Developer | Released | Test distances | App-specific brightness | Charts | VA notations | Price |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Peek Acuity | Peek Vision | 2016 | 2 m, 3 m | Yes (fixed at 100%) | Tumbling E | LogMAR, Snellen metric, Snellen imperial | Free |
| Snellen Chart | João Meneses | 2016 | Custom (default 6 m) | No | Snellen, Sloan, Tumbling E, Landolt C, Number, Children | Fraction, decimal and LogMAR shown together | Free |
| Snellen Chart | Fonlow | 2019 | 2, 3, 4, 5, 6 m, or custom 0.5 to 30 m | Yes, adjustable | Snellen | Decimal, fraction (20/40, 5/10, 6/12), LogMAR, MAR, VAS | Free |
| Tumbling E Chart | Fonlow | 2019 | 2, 3, 4, 5, 6 m, or custom 0.5 to 30 m | Yes, adjustable | Tumbling E | Decimal, fraction (20/40, 5/10, 6/12), LogMAR, MAR, VAS | Free |
| Eye Charts | Fonlow | 2018 | 2, 3, 4, 5, 6 m, or custom 0.5 to 30 m | Yes, adjustable | Snellen, ETDRS, Landolt C, Tumbling E, HOTV, Numbers, Shapes | Fraction, LogMAR, MAR, decimal, VAS, Five-Point | US$4.99 |

## [Peek Acuity](https://play.google.com/store/apps/details?id=org.peekvision.public.android) (Peek Vision) ![Logo](https://play-lh.googleusercontent.com/-wg9xxH-Sbl3IZMcU1JOLS3l4_p4oQZkOtNgSys7L_zs-C5k3raG6b8N6v4eRpxoIeHKjoE4dxrTILGUzvOGlw=s56-rw)

Peek Acuity is the simplest app here and the one that feels most like a purpose-built screening tool. It offers two predefined distances, 2 m and 3 m, and reports results as LogMAR, Snellen metric (6/6) or Snellen imperial (20/20). It runs its own brightness at a fixed 100%, which removes one source of variation between tests. The in-app help is intuitive and interactive, a real strength for first-time users.

The trade-offs are significant, though. It uses the **Tumbling E only**, shows **one optotype per row**, and works in **landscape view only** during testing. Showing a single optotype per row is a known weakness for amblyopia (lazy eye) assessment, because isolated optotypes are easier to identify than ones surrounded by neighbours (the crowding effect). The top navigation bar overlaps the phone's status bar, which makes navigation awkward on some devices. It supports Android 5 and up and is free.

Peek Vision describes the app as designed by eye care professionals to help identify people who need a further examination, not to replace one. Its listing adds four points: results come with a simulated representation of what the person sees, which helps explain scores to patients; it includes equivalents of count fingers, hand movement and light perception for very low vision; it collects no personally identifiable data; and it is not a medical device. It also asks users to perform an enforced manual calibration check before measuring acuity, so it is not entirely calibration-free like the others. The listing recommends keeping the app updated, because older versions may not work correctly on the latest Android releases.

**Best for:** quick, guided screening with a helper, for example in a community setting or at home with a parent.

## [Snellen Chart](https://play.google.com/store/apps/details?id=com.ideas.joaomeneses.snellen) (João Meneses) ![Logo](https://play-lh.googleusercontent.com/-1op9oRhnBmUmwdTHeDgf7BFDdZU9-RhZFhiVT-XR0rbBdAMIxrMbYQTereZYjY1FAow_aezEtSpIaNunorlCWw=s56-rw)

This free app has a set of chart styles of the free options: Snellen, Sloan, Tumbling E, Landolt C, Number and Children charts. It shows fraction, decimal and LogMAR values at the same time, which is handy for people who need to convert between systems. Colours of the optotypes and the background are adjustable, and an external keyboard is supported.

The listing presents it as an mHealth tool that lets ordinary users and health professionals estimate visual acuity with a classical Snellen chart. Swipe gestures step from one optotype to the next, and the chart adapts to different screen sizes, resolutions and user distances.

The weaknesses are in the details:

- **Distance display:** the default shows 599.9988 cm rather than 6 m, probably a floating-point rounding issue. It does not affect usability much but looks unpolished.
- **Optotype spacing:** multiple optotypes can be shown in one row, but the gaps are too narrow. Standard Snellen and ETDRS designs specify spacing relative to optotype width, so this departs from the chart design and may affect crowding and test validity.
- **Layout resets:** switching between landscape and portrait resets the optotypes to the largest size that fits the screen, which interrupts a test.
- **Browse only:** swiping steps from optotype to optotype, but there is no scoring mode that records your answers and gives a result. The user has to work out the result themselves.
- **Help:** primitive.

It requires Android 9 and up.

**Best for:** a professional or knowledgeable user who wants a free app with many chart types and is happy to read the acuity value off the screen.

## [Snellen Chart](https://play.google.com/store/apps/details?id=com.fonlow.snellen) (Fonlow) ![Logo](https://play-lh.googleusercontent.com/fjd-90lTlDPfKZNOjGNJk6tQhvhkgD5ROM_Qt68a4uHRySvJ0NvgAlt33fsaBbRAjql5wEsOeSfTsY2ZVrzp=s56-rw)

This app focuses on the classic Snellen chart. It offers predefined distances of 2, 3, 4, 5 and 6 m plus a custom distance from 0.5 m to 30 m, app-specific brightness independent of the device setting, and both landscape and portrait orientation. The starting optotype size corresponds to a 20/20 result, so the test begins at the standard reference line rather than at an arbitrary size. External keyboards are supported. It needs Android 6 and up.

The listing targets children over 6, parents of young children and general practitioners, and frames distance testing as an early step in spotting myopia. Beyond metric distances it offers imperial presets of 20, 15, 12, 10 and 6 feet, and four scenarios: doctor and patient, self-test with a mirror, self-test with a Bluetooth keyboard, and self-test within arm's reach. It supports seven notations (decimal, three fractions in 20/40, 5/10 and 6/12 style, LogMAR, MAR and VAS) and two test modes, autoplay and manual.

With Record Scores switched on, results for several test subjects can be tracked over time. VAS is calculated as 100 minus 50 times LogMAR, so higher is better. In the score review, 100 in blue marks the reference standard, scores above 100 in green suggest no myopia, and scores below 100 in red may indicate myopia.

The flexible distance range is the main practical advantage over the two apps above. Short distances help in small rooms or for people with low vision, and long distances suit clinics with a longer lane.

**Best for:** users who specifically want a familiar Snellen chart with flexible distance and independent brightness.

## [Tumbling E Chart](https://play.google.com/store/apps/details?id=com.fonlow.E) (Fonlow) ![Logo](https://play-lh.googleusercontent.com/jrCqhPsB4fC6gDLj5ptdHxBG6i_BvFm2E1d5T6c3pvBlzpNS95ULDdUqEhE2hYdEpwaJQzhHxMIUv4oqNyMaaA=s48-rw)

This is the Tumbling E counterpart of the app above, with the same distance options (predefined 2 to 6 m, custom 0.5 to 30 m), app-specific brightness, orientation support, a 20/20 starting size and external keyboard support.

It shows the Standard Tumbling E by default, with the Modified Tumbling E (shortened middle arm) as an option.

The Tumbling E is the standard choice for young children and anyone who cannot name letters, because the response is just a direction (up, down, left, right) and can be given by pointing or by using a hand-held E.

**Best for:** parents of children aged 6 and above, and any non-literate or non-English-reading user. A free option with good flexibility.

## [Eye Charts](https://play.google.com/store/apps/details?id=com.fonlow.VAC) (Fonlow) ![Logo](https://play-lh.googleusercontent.com/NxQ6BnWO5YYPrGug5CqZUAm7dRteYexCS2vYDUae5HG-zDL2AWhxD7uxWo89pzIePUwPzcRwDb-eiyg3BEez=s56-rw)

Eye Charts is the most complete app of the group and the only paid one (US$4.99). It combines seven chart types: Snellen, ETDRS, Landolt C, Tumbling E, HOTV, Numbers and Shapes. That covers literate adults, children who know only some letters (HOTV), and young children who recognise shapes. ETDRS and Landolt C are the choices of clinical research and of many professional settings.

Two points from its listing set it apart. First, it was evaluated independently in a [peer-reviewed study in JAMA Ophthalmology](https://pmc.ncbi.nlm.nih.gov/articles/PMC7809609/), under its earlier name Visual Acuity Charts. Charts are sized on LogMAR steps. Results can be recorded per test subject and shown as simple graphs, so a parent or clinician can see gradual change, stability after an intervention, and differences between visits. It offers three ways to test: doctor and patient, mirror self-test with an eye patch (the effective distance doubles), and Bluetooth keyboard self-test from a few meters away. 

Standout features:

- **Multiple optotypes in one row**, which is useful for assessing amblyopia.
- **Six VA notations**: fraction (20/20, 6/6, 5/5), LogMAR, MAR, decimal, VAS and Five-Point, which covers most clinical and regional conventions.
- **Mirror mode**, so you can test in a small room by reading the reflection of the screen in a mirror at an effective doubled distance.
- The same distance flexibility (2 to 6 m, custom 0.5 to 30 m), app-specific brightness, a 20/20 starting size, landscape and portrait support and external keyboard support as the other Fonlow apps.

The help is clear, though it assumes familiarity with paper charts.

**Best for:** healthcare professionals, and families who need a chart type matched to a particular child.

## Accuracy of optotypes

All five apps pass the entry requirement of displaying optotypes at the correct size for the chosen distance without manual calibration. Beyond that, the differences are about **fidelity to the chart standard**:

- **Peek Acuity** is accurate but limited to the Tumbling E with one symbol per row, so it does not reproduce the crowding of a full chart.
- **Snellen Chart (João Meneses)** scales correctly but narrows the inter-optotype gap, which departs from Snellen and ETDRS spacing rules. Optotype size can also reset when the orientation changes.
- **The three Fonlow apps** start at the 20/20 size and support multiple optotypes per row (Eye Charts explicitly so). Our notes do not describe their spacing in detail, so we make no claim beyond what was observed.

A general caution applies to every phone chart: very small optotypes at short distances are limited by the screen's pixel size, and glare and screen reflections matter. Use the same device, distance and room lighting for repeat tests.

On validation, only Eye Charts cites an independent peer-reviewed evaluation in its listing. The other descriptions make no such claim. Peek Acuity relies on a calibration check rather than automatic scaling alone.

## Practicality

**Test distances.** The Fonlow' vision test apps are the most flexible, with five metric presets (2 to 6 m), imperial presets (6 to 20 ft), and a custom range of 0.5 to 30 m. João Meneses accepts custom distances but displays them oddly. Peek Acuity is limited to 2 m and 3 m.

**Brightness.** Peek Acuity and the Fonlow apps use app-specific brightness, which means a consistent screen brightness for each test regardless of how the phone is set. Peek fixes it at 100%, while the Fonlow apps let you adjust it. Brightness handling for the João Meneses app is absent, but it offers colour customisation.

**VA notations.** The Fonlow Snellen and Tumbling E apps offer seven (decimal, three fraction styles, LogMAR, MAR and VAS), Eye Charts offers six, João Meneses shows three at once, and Peek Acuity offers three.

**Help and ease of use.** Peek Acuity has the best interactive help. The Fonlow apps have clear instructions but assume paper chart familiarity. João Meneses has primitive help and no test mode.

**Compatibility.** Peek Acuity runs on Android 5+, the Fonlow apps on Android 6+, and João Meneses on Android 9+, which could exclude older phones and tablets.

**Scoring and tracking.** The Fonlow apps can record scores for multiple test subjects, and Eye Charts graphs them over time. Peek Acuity reports a score of 6/6 which is the last row of the VA test. João Meneses offers no scoring or recording.

## Recommendations by reader

| If you are... | Consider | Why |
| --- | --- | --- |
| A home user wanting a quick check | Peek Acuity or Snellen Chart (Fonlow) | Peek has guided help; Fonlow has more distances and brightness control |
| A parent of a child aged 6+ | Tumbling E Chart (Fonlow), or Eye Charts for HOTV and Shapes | The E needs no letter knowledge; Eye Charts adds child-friendly optotypes and crowded rows |
| A healthcare professional | Eye Charts (Fonlow) | ETDRS, Landolt C, multiple notations, crowding rows and mirror mode |
| On a budget with an older phone | Peek Acuity or Tumbling E Chart | Free and supports Android 5 or 6 and up |
| After the widest free variety of charts | Snellen Chart (João Meneses) | Six chart types, but browse only and tight spacing |

## Verdict

If you want a free, guided screening tool, **Peek Acuity** is the easiest to pick up, though its single-optotype rows and landscape-only testing limit its use. **Snellen Chart by João Meneses** offers variety at no cost but is the least polished and falls short on chart spacing and test workflow. The Fonlow apps are the most flexible on distance and brightness: **Tumbling E Chart** is the pick for families, and **Eye Charts** is the most capable all-round app and the clear choice for professionals, justifying its US$4.99 price.

Whichever app you choose, test at the stated distance, keep lighting and glare consistent, test each eye separately, and see an eye care professional about any concerning result.