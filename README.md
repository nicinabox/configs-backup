# Usage

    $ configs backup
    => Backing up sabnzbd
    => Backing up sickbeard
    ...

    $ configs restore
    => Restoring up sabnzbd
    => Restoring up sickbeard
    ...

    $ configs restore sabnzbd
    => Restoring up sabnzbd

# Config

Default config lists lots of possible services so there's good coverage ootb. Only found services will be backed up.

    {
      "services": {
        "sabnzbd": '/path/to/sabnzbd',
        "sickbeard": '/path/to/sickbeard'
      },
      "backup_dir": "~/.configs"
    }

# Backup directory structure

    .configs
      sabnzbd
        settings.ini
      sickbeard
        settings.ini
