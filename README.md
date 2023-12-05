# PES Lightmanager for PES 2020 / PES 2021

Version 0.2.0d

## Installation

Install this plugin to Blender by going to Edit > Preferences > Addons > Install...

And then activating the plugin:

![alt text](https://i.imgur.com/0Om8Kqk.png)

The plugin will attempt to install a package via the "pip" command to your Blender which are required for export. If you encounter issues after trying to install the AddOn, close blender.exe and reopen as Administrator and that should fix your issue.

```python
pip install Pillow
```

## Usage

* **Spot ID:** This will assign your HEX value to the SpotLight. ***(Make sure no duplicate SpotIDs are inside your Scene!)***

* **Temperature:** Add warmth to your light with this value. The higher your temperature the more orange it gets.
* **Cast Shadow:** Set to "1" if you want your light to produce shadows. Set to "0" to disable.
* **Bounce Lights:** Set to "1" if you want light to bounce off objects (similar to ray tracing). Set to "0" to disable.
* **Enabled:** Set to "1" to enable your light. Set to "0" to disable (the light will no longer appear in-game).
* **Power:** Set the strength of your light.
* **UmbraAngle:** Determines the overall angle of the spotlight cone.
* **penUmbraAngle:** Specifies the angle at which the light intensity starts to decrease (penUmbra) and becomes fully attenuated (Umbra).

![alt text](https://i.imgur.com/GrhL5zV.png)

## Tools

You can find this Blender AddOn equipped with many useful tools such as:
* **Bulk Edit SpotLights:** Blender does not allow you to change the properties of multiple selected SpotLights. Want to change the brightness of all your lights? Now you can with this tool!
* **Mirror Tool:** If your stadium is symmetric you can use this tool to save a lot of time by simply mirroring your SpotLights to the other side of the stadium! ***(Use the Tool "Fix SpotLights" if you encounter duplicate SpotLights like .001, .002, .003)***
* **Fix SpotLights:** This tool will attempt reassign SpotIDs, useful tool if your exports are not working or if you already have existing SpotLights added before using this AddOn.

  
* ***(NEW)*** **Export Dynamic Objects:** Add Flags which are animated to be waved around in-game or add trees with windy leaves to give your exteriors a more lively look!

#### Tools can be found here:

![image](https://github.com/PallasDav/pes_lightmanager/assets/152204413/e0693d17-34aa-4b1f-ba65-8c34f0e90ff7)

