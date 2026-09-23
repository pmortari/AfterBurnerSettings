# AfterBurnerSettings

## Restoring settings

The repository preserves profile files for MSI Afterburner and RivaTuner
Statistics Server (RTSS). To restore them:

1. Exit MSI Afterburner and RTSS completely, including their notification-area
   icons, so they do not overwrite the restored files on exit.
2. Copy the saved MSI Afterburner profile files into:
   `C:\Program Files (x86)\MSI Afterburner\Profiles`
3. Copy the saved RTSS profile files into:
   `C:\Program Files (x86)\RivaTuner Statistics Server\Profiles`
4. Allow Windows' administrator prompt if it appears, replacing the existing
   files when asked.
5. Start RTSS first, then MSI Afterburner, and confirm the fan, clock, OSD,
   and frame-rate settings are as expected.

Before replacing anything, keep a copy of the current `Profiles` folders if
you may want to return to the settings presently installed on the machine.
