# n2ntray

I was planning to write a simple wrapper of n2n edge on windows. Then I found this repo: https://github.com/rexdf/CommandTrayHost so I decided to stop reinventing the wheel.

I built the n2n edge binary myself, using the latest commit of https://github.com/meyerd/n2n

## Usage

Download the release binary, extract into a local dir, for example: `d:\n2ntray`. Edit the `config.json`, based on your situation.

Then install `tapdriver\n2neg_install_v1.0.exe`, we need the TAP driver but we are not using this program.

Run the `CommandTrayHost.exe`, manually start n2n in the tray menu, or make it autostart.
