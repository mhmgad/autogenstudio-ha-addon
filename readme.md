# Autogenstudio as an Add-on

## About

This add-on runs autogenstudio as a service.


## Installation

### HACS Installation (Recommended)

1. Make sure you have [HACS](https://hacs.xyz/) installed in your Home Assistant instance
2. Click on HACS in the sidebar
3. Click on "Integrations"
4. Click the three dots in the top right corner
5. Select "Custom repositories"
6. Add `https://github.com/yourusername/ha-autogenstudio` with category "Integration"
7. Click "Add"
8. Search for "Autogenstudio" in HACS
9. Click "Install"
10. Restart Home Assistant

### Manual Installation

1. Download or clone this repository
2. Create a `custom_components` directory in your Home Assistant configuration directory if it doesn't already exist
3. Copy the `autogenstudio` directory from this repository to your `custom_components` directory
4. Restart Home Assistant

After installation, the integration will be available to configure through the Home Assistant UI under Settings > Devices & Services.



## Configuration

no configuration is needed till now