## References:
- https://reddit.com/r/anycubic/comments/y2waxu/tutorial_how_to_build_anycubic_marlin_source_code/
- https://reddit.com/r/anycubic/comments/ynvbj0/anycubic_kobra_working_config/

## Changes:
- Enabled QUICK_HOME
- Change machine name from "Vyper" to "Kobra"
- Enabled SAVED_POSITIONS so G60/G61 can be used for filament change routine
- Disable startup jingle
- ~~Swap X stepper address to accomodate the mainboard mod mentioned in [this post](https://old.reddit.com/r/anycubic/comments/ynvbj0/anycubic_kobra_working_config/) (swap X_SLAVE_ADDRESS and E0_SLAVE_ADDRESS)~~
- ~~Greatly reduce motherboard fan speed~~