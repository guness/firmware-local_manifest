This manifest adds a number of targets to an AOSP build. To make use of this you should;

1. Init your repo with the appropriate URL and branch (e.g. `repo init -u https://github.com/LineageOS/android.git -b lineage-20 --git-lfs`).
2. Checkout this repo into the local manifests area (e.g. `git clone https://github.com/guness/firmware-local_manifest.git .repo/local_manifests -b lineage-20-AAOS`).
3. Perform a repo sync (e.g. `repo sync`)
4. Use one of the additional targets (e.g. `brunch car_gta4xlwifi`)
