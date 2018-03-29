Changelog
=========

Version 0.1.2.0
---------------

*Mar 29, 2018*

<https://github.com/mstksg/hmatrix-backprop/releases/tag/v0.1.2.0>

*   `zipWithVector` family rewritten in the same way as `dvmap`/`dvmap` were
    for version 0.1.1.0, which is a breaking API change.  However, again, it is
    unlikely that any code using the previous versions compiled at all, so in
    practicality, no actual code that previously worked is now breaking.

Version 0.1.1.0
---------------

*Mar 25, 2018*

<https://github.com/mstksg/hmatrix-backprop/releases/tag/v0.1.1.0>

*   `dvmap`/`dmmap` family rewritten, which is a breaking API change.  Previous
    version of `dvmap`/`dmmap` would not even compile at all if used, though,
    because of nonsensical constraints, so it is likely that no code that
    previously worked is now breaking.
*   *backprop* types re-exported for convenience

*Internal*

*   Rewrote much code to use `isoVar` instead of `opIso`, for increased clarity
    and cleanliness.  Requires *backprop-0.1.4.0*.

Version 0.1.0.0
---------------

*Feb 10, 2018*

<https://github.com/mstksg/hmatrix-backprop/releases/tag/v0.1.0.0>

*   Initial release