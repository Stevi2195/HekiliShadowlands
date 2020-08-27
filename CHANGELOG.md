# Hekili

## [v9.0.1-1.0-alpha15](https://github.com/Hekili/hekili/tree/v9.0.1-1.0-alpha15) (2020-08-23)
[Full Changelog](https://github.com/Hekili/hekili/commits/v9.0.1-1.0-alpha15) [Previous Releases](https://github.com/Hekili/hekili/releases)

- Feral:  Predatory Swiftness spell ID changed.  Not sure why.  
- When forecasting channel ticks, try a couple of options for tick times.  
- MM Hunter:  Contributed by Stevi2195, with revisions for Steady Focus.  Requires review.  
- Shadow:  Initial SL commit.  Legendaries not accounted for.  Playable.  
- On reset, queue channel tick events.  
- More debugging info re: channeled spells; need to respect channel interrupt requirements in event-based system.  
    Add channel ticks to event queue even if there's no ability.tick function; we may have resources generated from auras.  
- WW:  Default allow\_fsk to false; it's annoying.  Tweak priority.  
- Tweak Delays > Extend Cooldown Sweep again for the 10,000,000th time.  
- Feral:  Try to make incremental tweaks for new Bloodtalons to work.  
- Elemental:  Flag as ranged.  
- Brewmaster:  Expel Harm spell ID changed.  
    Implement Gift of the Ox as a buff.  
    Retire T20 bonus.  
- Frost DK:  Retire legiondaries.  
- Blood:  Remove Legiondaries.  
- Convert versatility mods to decimals (divide by 100).  
    Remove debug lines from TimeToReady.  
- KJBW broken in Shadowlands?  
- Brewmaster:  Divide by zero protection.  
    Support Purified Chi mechanics.  
    Tweak priority a little.  
- Max health is always 1 or more.  (Avoid division by zero.)  
- Brewmaster:  Initial support (no legendaries, conduits).  Priority is nonsense.  
- Guardian:  Ironfur is off GCD.  
- Prevent error when a class has no resources.  
- Beast Mastery:  First pass on abilities and talents.  Priority has not been revised.  
- Add Primal Rage to Bloodlusts.  
- Elemental:  Fulmination, remove Seismic Thunder, add Static Discharge...  
- Enhancement:  Ice Strike, Elemental Assault changes.  
- Retribution:  HoW during AW requires level 58.  
- Test annoying warning for Demon Hunters using Demon Blades.  
- Fix new SL Hot Hand effect.  
    Windstrike uses Stormstrike's spell ID for known.  
- Prevent an error when a script hasn't been loaded for a specialization.  
- Merge pull request #391 from Bloodmallet/shadowlands  
- Use Primal Strike for Stormstrike's range check.  
- runeforge.X.enabled or legendary.X.enabled for legendaries.  
    Split ability.range vs. ability.rangeSpell.  
- Fix regression for reactive mode.  
- update update-date to be up to date  
- replace apl with easy apl  
- remove dangling totem variable, add seismic thunder to lava beam, clean up totem mastery  
- Merge branch 'shadowlands' of github.com:Hekili/hekili into shadowlands  
- Use UnitPhaseReason (new API) as UnitInPhase is deprecated.  
- add general TODO list  
- replace ' with "  
- add fulmination and seismic thunder  
- Windwalker:  Lazy fix for Touch of Death blocking the priority.  
- Merge branch 'shadowlands' of github.com:Hekili/hekili into shadowlands  
- Treat Vesper Totem like an actual totem.  
- Add Phial of Serenity action.  
- Windwalker Monk added (with legendaries).  
- second pass, adding TODOs  
- enable elemental (boy...please don't)  
- remove white spaces and make shaman check consistent  
- first update based on skeleton and by hand comparison  
- Only one set of PvP talents now.  
- More Blood DK stuff:  
    Rune of Hysteria RP gain.  
    Track ghoul info via totem API.  
    Track Control Undead info via pet/debuff API.  
    Add Blood Tap.  
    Tweak Sacrificial Pact.  
    Tweak priority for ghoul/pact.  
- Some Blood DK priority tweaks.  
- Refresh options when a default action pack is loaded.  
- Blood DK legendaries.  
- Add Blood DK.  
    Legendaries NYI.  
- Add Door of Shadows to all classes.  
- Enable Feral.  
- Reset Eye Beam and Blade Dance on Metamorphosis.  
- Tweak Havoc priority.  
    Fix Immolation Aura Fury generation.  
- Update legendary names.  
- Remove former PvP talents (now trinketed).  
- Correct Interface version to 90001.  
