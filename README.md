# Backwards compatibility for M4.1.13

The version on this has been reduced to M4.1.13 to allow installing on M4.1 sites, however, it will not work unless core changes have also been applied.

A patch is available in the patches folder, and has been sanity tested against M4.1.13. The patch will update h5plib_v124 as well as core, so you can have both v124 and v127 installed at the same time.

Although the patch references v126, there appear to be no interface changes between v126 and v127 that require further updates to core_h5p.

With each update to Moodle, you will need to reapply the patch unless you're rolling with your own Moodle branch.

## Not supported

I cannot stress this enough, I cannot offer any support. I will only update the patch if I need to for my own requirements.

Please do all your own testing.

I am only testing against versions of Moodle I am running, so if it doesn't work for anything less than M4.1.13 I cannot help.