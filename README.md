# findspot

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A web application for exploring tourist spots in Japan by querying public SPARQL endpoints.

## Demo

https://codeforfukui.github.io/findspot/

The demo displays an interactive Google Map centered on Kyoto, showing tourist locations with markers.


![findspot user interface showing a map of Kyoto with location markers and navigation buttons](ss.jpg)


## Features

- Fetches and displays tourist spot data using SPARQL queries.
- Renders locations interactively on a Google Map.
- Finds the nearest spot to your current location (requires browser permission).
- Supports multiple SPARQL endpoints, including the Open Data Platform (ODP) and Kyoto City.
- Includes a dropdown to quickly center the map on various Japanese cities (e.g., Kyoto, Osaka, Tokyo, Fukui).

## Requirements

- A modern web browser with JavaScript enabled.

## Usage

1.  Open the [demo page](https://codeforfukui.github.io/findspot/) in your browser.
2.  The map will load with tourist spots around Kyoto Station.
3.  Use the dropdown menu to select a different city to explore.
4.  Click the "Nearest" button to find the closest spot to your current location.
5.  Use the "Prev" and "Next" buttons to cycle through the displayed spots.

## Data / API

This project retrieves data from the following SPARQL endpoints:

-   **Open Data Platform (ODP):** `https://sparql.odp.jig.jp/data/sparql`
-   **Kyoto City Open Data:** `https://sparql.city.kyoto.lg.jp/sparql/`

It also utilizes the Google Maps JavaScript API for map rendering.

## License

This project is licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
(c) Taisuke Fukuno