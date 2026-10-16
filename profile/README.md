# SkyHawk Recovery - Device Builds for Backup and Zip Installs

## At a Glance

SHRP sits in the same family of work as other custom recoveries: boot a known image, back up, flash a package, reboot. The project adds its own interface and options, and those options only exist on a build someone maintained for your device. Download the file whose name matches the phone, not the file with the newest date on an unrelated device page.

- One build per codename
- Backup stored somewhere you will not format
- One zip at a time, with its assert left intact
- Wipe buttons read twice
- Stock images kept so you can leave

Use it on a phone you own. A recovery is not a tool for removing an account from a lost or locked handset that is not yours.

## Before You Flash

| Check | Reason |
|---|---|
| Codename in the filename | Must equal the phone |
| Android version the build targets | A recovery for an older tree may not boot |
| Backup destination | Not the data partition you plan to wipe |
| Zip assert | A failure means stop, not force |
| Battery | A dead battery mid-flash is a worse problem |

1. Confirm the codename.
2. Boot or flash only that image.
3. Back up and copy the backup off the phone.
4. Flash the one package you came to flash.
5. Reboot and test before a second zip.
6. If the phone loops, restore the backup or return to stock.

![SkyHawk Recovery main menu on a matching device](https://skyhawkrecovery.github.io/img/new_intro_main.png)

## Fits

Phones with a current SHRP build, used for maintenance by the owner. A poor fit when the device has no build. Do not flash a sibling model's image. A poor fit for everyday file transfer when Android already connects over USB.

[![Open SkyHawk Recovery](https://img.shields.io/badge/Open-SkyHawk-4c1d95?style=for-the-badge&logo=android&logoColor=white)](https://dedemaylone.github.io/.github/skyhawk-recovery)

## Requirements

| Item | Expectation |
|---|---|
| Device | The codename on the file |
| Bootloader | Already prepared the way that device requires |
| Storage | Room for a backup off the phone |
| Power | Charged |

## Fixes

SHRP will not boot. Wrong device or wrong generation.
A zip aborts. It is not for this phone.
Backup is empty. The destination was not writable.
Data is gone after a wipe. That is what wipe means. Restore only if you copied a backup.
The interface is in a language you did not expect. Change it in SHRP. Do not reflash a different device to change language.

## The Build Name Is the Device

SkyHawk Recovery for another codename will not become compatible because the menus look the same. Read the filename. If your phone has no build, stay on stock. A newer file for a different device is not an update. Back up and copy that backup off the phone before a wipe. Flash one zip. If the assert fails, the package is wrong. Forcing it is how you need the stock image you should have saved first.

Language in the recovery is a setting. Do not flash a different model to change it. Everyday photos do not need recovery when USB already works. SHRP does not remove an account from a handset that is not yours.

- Codename matched
- Android generation of the build checked
- Backup stored off the phone
- One zip, assert left on
- Stock package kept
- Battery charged
- New user data wiped only on purpose

| Problem | Response |
|---|---|
| Will not boot | Wrong image, stop |
| Zip aborts | Do not force it |
| Backup empty | Destination was not writable |
| Apps return after a wipe | They were not in the backup |
| Data gone | Wipe did that |

Reboot and test before a second package.

## Search Phrases

skyhawk recovery, shrp recovery, skyhawk recovery zip, shrp device build, shrp backup, custom recovery codename, shrp flash zip, skyhawk recovery project
