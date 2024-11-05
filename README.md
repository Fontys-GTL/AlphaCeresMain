# AlphaCeres
Repository with documentation, settings etc

## References 


* [docs ROX](https://roxautomation.gitlab.io/machines/almighty/almighty-gps)


## Integration notes 2024.11.05

1. Install usbtin with instructions from [rox-usbtin repo](https://gitlab.com/roxautomation/tools/usbtin)
2. Install [odrive-can](https://gitlab.com/roxautomation/components/odrive-can)

## Notes

* odrive can was not working with 0.5.1 (unkown firmware).
* updated firmware by
    - shut down drive
    - set dip switch in DFU mode
    - run `odrivetool dfu`
    - power cycle drive
