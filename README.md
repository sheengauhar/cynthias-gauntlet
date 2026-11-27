# NullAndVoidVibes : Cynthia's Gauntlet

This entry uses a legal 40-point team with the simulator's built-in battle policy.

## Run the team

1. Open the [Cynthia's Gauntlet simulator](https://cynthias-gauntlet.onrender.com/).
2. Select **Edit JSON**, paste the contents of `team.json`, and select **Validate** followed by **Save & Apply**.
3. Clear any previously applied custom policy in **Battle Policy**. Run an Arena battle or a public seed evaluation.

## Strategy

Slaking leads with bulk and Normal, Ground, Ice, and Electric coverage. Starmie and Weavile provide fast special and physical damage. Lombre supplies Grass coverage for Water and Ground matchups. Starly is immune to Ground and Ghost attacks, and Swinub supplies priority Ice damage.

This roster won 221 of 300 public practice battles (73.7%) across three seed batches. The official hidden variants were unavailable for evaluation.

## Baseline

`baseline-team.json` is the original 40-point, Lucario-led team used for comparison. It won 0 of 250 public practice battles with the built-in policy. To reproduce the baseline setup, load this file in the simulator using the same steps as for `team.json`.

## Credits

- Official Cynthia's Gauntlet simulator and published battle data (Custodia × WiTS).
- PokeAPI data, as credited in the organizers’ data package.
- Sheen Gauhar directed team selection and testing. Codex assisted with analysis and simulator testing.
