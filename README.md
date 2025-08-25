# GeoRoots Fixer
Browser based tool for correcting GeoJSON files into EU Deforestation Regulation (EUDR) compatible structure

This app can open different types of JSON and GeoJSON files, structure them to be easy for reading and provides the user with JSON parsing feedback.

There is a built in error recovery fix that can help with some frequent issues with JSON files. The app then allows the user to rename, realign and discard certain properties that were in the GeoJSON file.
This is helpful if some properties are incorrectly named or if the user wants to remove some properties for privacy protection.

## Usage

* Open the fixer.html file in your browser.
* Select a language from the dropdown at the top.
* Drag & Drop .json or .geojson file into the centre of the page or use the file selector button.
* Once loaded, you can format the JSON file, select which properties to rename or discard and choose a few other options to manipulate the data as needed.
* Once complete, press generate GeoJSON and the final file will be donwloaded by your browser and saved into your downloads.

## FAQ

##### Q: **My language is not included. Can it be added?**
A: Yes, please open an issue ticket and request a new language.

##### Q: **After using the fixer, my geolocations are appearing somewhere completely different. What's wrong?**
A: This fixer app focuses on the correct formatting of the GeoJSON file, but it assumes that your geocoorinate system is WGS 84 / Web Mercador Projection. If your original file was in different projection, the correction of the JSON structure might work, but the coordinates might remain incorrect. You need to export your data in WGS 84 system or use coordinate system convertion tools first.



## About GeoRoots: Open Source Toolkit for EUDR Compliance and geo traceability

GeoRoots is a collection of minimalistic, open-source tools designed specifically for EU Deforestation Regulation (EUDR) requirements and enhancing geo traceability.

Our philosophy is simple: provide useful tools that respect your privacy, work offline (where possible), and require no complex setup or subscription fees. Every tool runs entirely in your browser and can be downloaded for offline use.

### Why Use GeoRoots?

*   **100% Private**: All tools run locally in your browser. No data is ever transmitted to external servers.
*   **Open Source**: Fully open source and transparent. Inspect, modify, and contribute to the code.
*   **Offline Ready**: Download and use tools completely offline. Perfect for remote locations.
*   **Mobile Friendly**: Works on desktop, tablet, and mobile devices.

### Perfect for:

*   Producers and cooperatives
*   Smaller traders and exporters
*   Importers, operators
*   Sustainability consultants

### Useful Official Resources

*   [EUDR DDS on LIVE Environment](https://eudr.webcloud.ec.europa.eu/tracesnt/)
*   [EUDR DDS on TEST Environment](https://acceptance.eudr.webcloud.ec.europa.eu/tracesnt/)
*   [EUDR on Green Forum](https://green-forum.ec.europa.eu/deforestation-regulation-implementation/information-system-deforestation-regulation_en)
*   [EUDR on EUR-Lex](https://eur-lex.europa.eu/legal-content/EN/HIS/?uri=CELEX:52024PC0452)

### License

This project is licensed under the GPLv3 License. See the [LICENSE](LICENSE) file for details.

### Contributing

We welcome contributions! Please see our [contribution guidelines](CONTRIBUTING.md) for more information.


### Contact

For any questions or feedback, please open an issue on this repository.
