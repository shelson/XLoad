This is a fork of https://github.com/rgcaudio/XLoad - but modified so that it compiles/runs on macos with the FTDI drivers there.

If you use https://github.com/trabucayre/openFPGALoader to load the `.bit` file you can then use xload on the mac to load the synth files/configure them

`openFPGALoader --board cmoda7_35t CMOD_A7_Loader.bit`
`/xload -img XVA1_102/XVA1_CMOD_A7.bin`
`./xload "t XVA1_102/XVA1_Tunings.bin"`
`./xload "put_bank XVA1_102/XVA1_Factory.bank"`

Lovely dubbly :)
