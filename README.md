# rJourney
FHWA National long distance passenger model

### Download the command line model and inputs from GitHub
  - Go to https://github.com/rsginc/rjourney
  - Select Clone or Download and then Download Zip
  - Download the [large inputs file](https://github.com/RSGInc/rJourney_resources/raw/master/inputs.zip)
  - Optional: Download the [500-zone sample household file](https://github.com/RSGInc/rJourney_resources/blob/master/azure_inputs/us_synpop_hh3_500_zone_sample.dat) for faster runtime

### Optional: Build rJourney from source
  - Required for Mac or Linux
  - Install the [Free Pascal Compiler](https://sourceforge.net/projects/freepascal/)
  - Compile rJourney:
    - Open Terminal in the project folder
    - run `fpc -Mdelphi rJourney_1_4.pas`

### Run rJourney
  - Unzip the inputs into the project folder
  - Open command prompt, PowerShell, or Terminal in the project folder
  - run `rJourney_1_4.exe .\rJourney_example_config.txt`
  - (Mac/Linux: `./rJourney_1_4 ./rJourney_example_config.txt`)

### Documentation
  - Additional resources, example configs, and documentation can be found at [rJourney_resources](https://github.com/rsginc/rjourney_resources)
