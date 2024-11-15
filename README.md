# InspirationTracing
Trace inspirations for experimental follow-up hits back to their fragments

Sleuthing approach:

1. Identify Fragalysis tags that correspond to derivatives and fragment screen
2. For each derivative calculate SuCOS score against all candidate inspirations
3. Export Excel file
4. For each derivative quickly eyeball overlaid derivative and fragment and score inspiration based on visual overlap of fragment motifs

To-Do's:

- [ ] Calculate number of recapitulated interactions and add to spreadsheet
- [ ] Add extra SuCOS feature & volume scores to spreadsheet
- [ ] Determine logical filter to mimic manual eyeballing
- [ ] Do a few more targets

## A71EV2A

- 41 derivatives `tag=="[Other] P3 Compound Design" + tag=="[Other] P2 Wave 1"`
- 110 candidate inspirations `tag=="[Other] Fragment Screen"`

Manually identified:
- 56 fragment-derivative pairs `"Max Eyeball" == YES` in [A71EV2A_sucos](A71EV2A_sucos.xslx)
- 58 additional possible fragment-derivative pairs `"Max Eyeball" == MAYBE` in [A71EV2A_sucos](A71EV2A_sucos.xslx)
