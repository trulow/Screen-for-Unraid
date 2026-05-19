# Screen for Unraid

![Screen for Unraid](https://github.com/trulow/Screen-for-Unraid/blob/main/icon.png?raw=true)

Go to the Plugins tab > Install Plugin

Enter the following URL

    https://raw.githubusercontent.com/trulow/Screen-for-Unraid/main/plugin/Screen-for-Unraid.plg

# Source

    https://slackware.pkgs.org/current/slackware-x86_64/

# CHANGE LOG:

    ### 2026.05.17 (Provided by @rasooll)
        - Removed the fixed screenBuild package value.
        - Added dynamic lookup for the latest available screen-5.0.1-x86_64-*.txz build from CHECKSUMS.md5.
        - Kept checksum validation before installation.
        - Kept mirror fallback support.
        - Updated the plugin version to 2026.05.17.
        - Updated changelog entries in the plugin and README.
        Validation
        - Verified the plugin XML with xmllint.
        - Verified the embedded install script with bash -n.
        - Tested the build selection logic to confirm it chooses the highest numeric build.

    ### 2026.05.17
        - Install the latest available 5.0.1 build with automatic checksum validation and mirror fallback

    ### 2026.01.23
        - Install 5.0.1 with automatic checksum validation and mirror fallback

    ### 2024.06.11
        - Initial release to install screen-4.9.0-x86_64-1
