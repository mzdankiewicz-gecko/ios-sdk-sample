1.0.1 (2013-11-25)
==================

Bug Fixes
---------

- Removed false positives of custom ad size warning.

Corrections on documentation
----------------------------

- Ad classes now are documented under their correct name.
- Backfilling instructions for AdMob were corrected.
- Repeated content in LiquidMAdViewController was reduced by general information in the overview section.
- Delegate properties and connected protocols are better linked together.

Location awareness
------------------

- LiquidMAdViewController now has a location property that can be used for location aware advertising.
- An option "LiquidMAdViewControllerOptionLocation" for the controller factory was added for the initial location.

AdMob mediation
---------------

- "GADMAdapterLiquidM" implements Google's SDK adapter interface.
- Google's custom events are implemented by the classes "GADMAdapterLiquidMCustomEventBanner" and "GADMAdapterLiquidMCustomEventInterstitial".
