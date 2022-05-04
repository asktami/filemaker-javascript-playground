# filemaker-javascript-playground

## Using JavaScript in a FileMaker Webviewer

### 51 examples as of 1/1/2022

FileMaker 19 experiments with various JavaScript functions and libraries.
<strong>Fully tested on Mac. Not fully tested on Windows.</strong>

I created this file so that I could experiment with various JavaScript libraries and the new <strong>FileMaker 19 Perform JavaScript in Web Viewer</strong> and <strong>Execute FileMaker Data API</strong> script steps.

The RESOURCE table holds CSS and JavaScript code / libraries / frameworks for use with different demos.

The HTML_RESOURCE table links the demo to its associated CSS and JavaScript code / libraries / frameworks.

The HTML table holds 1 record for each demo, aka the "HTML Template".

<strong>Note:</strong>
In some of my examples I use a special FUNCTION Web Viewer to run a JavaScript function and then use those results in my demo. This shows how you can use a Web Viewer to perform a specific function/calculation/etc. that you then use in another Web Viewer/script/etc.

Let me know if you have any questions/comments.

<strong>[Sign-up](http://eepurl.com/h11rk) if you want to be notified about updates to this file.</strong>

Enjoy!

![About](https://github.com/asktami/filemaker-javascript-playground/blob/main/screenshots/About.png)

## Main Demos

![Main_Demos](https://github.com/asktami/filemaker-javascript-playground/blob/main/screenshots/Main_Demos.png)

<ul>
<strong>Demo Name (Record ID)</em></strong>
<li>Blinking Text (1)</li>
<li>Bootstrap Animated Progress Bar (5)</li>
<li>Bootstrap Masonry (42)</li>
<li>C3 Chart (8)</li>
<li>C3JS Chart (12)</li>
<li>C3JS Chart Test  (14)</li>
<li>C3JS JSON Chart Data Test (13)</li>
<li>C3JS JSON Chart Data Test 2  (15)</li>
<li>C3JS JSON Chart Data Test 3 (16)</li>
<li>C3JS with JSON data from ExecuteDataAPI (20)</li>
<li>Carafe.FM Pivot.js (28)</li>
<li>Carafe.FM SanKey (data sorted by Channel and State) (27)</li>
<li>CSV2JSON: Convert CSV to JSON (7)</li>
<li>DataTables (for portals) - shift+click to select multiple rows, command+click to select non-adjacent rows (21)</li>
<li>DataTables TEST - FM18 Survey Questions as Cards, with flag for question already in selected survey (45)</li>
<li>DataTables TEST - Survey Questions as a table (43)</li>
<li>DataTables TEST - Survey Questions as Cards, with flag for question already in selected survey (44)</li>
<li>Faker.js - Create People Test Records  - look at script before clicking "Run Faker" (26)</li>
<li>Faker.js - Create Person and Donation Test Records - look at script before clicking "Run Faker" (25)</li>
<li>FM18 getFieldData array of JSON objects from ExecuteDataAPI script step finding all MARKER records (10)</li>
<li>FM19 getFieldData array of JSON objects from ExecuteDataAPI script step finding all MARKER records (9)</li>
<li>FM19 window.location=FileMaker.PerformScript (17)</li>
<li>GoogleMap (50)</li>
<li>GoogleMap An Address (51)</li>
<li>Hello World (2)</li>
<li>jQueryUI Accordian - Default (46)</li>
<li>jQueryUI Accordian - Dynamic (47)</li>
<li>jQueryUI Range Slider - Default (48)</li>
<li>jQueryUI Range Slider - Dynamic (like PipsSlider) (49)</li>
<li>JS Error Handling - Try, Catch, Finally (11)</li>
<li>JSONATA - 1 (29)</li>
<li>JSONATA - 2 (30)</li>
<li>JSONATA - 3 (31)</li>
<li>JSONATA - My Conversion - 1 (32)</li>
<li>JSONATA - My Conversion - 2 (33)</li>
<li>JSONATA - My Conversion - 3 (34)</li>
<li>LeafletJS Marker Clusters with Filters (CLICK to select a marker; DOUBLE-CLICK to add a marker) (6)</li>
<li>Moving Graphic (40)</li>
<li>NoUI Sliders - Multiple Sliders at Once (41)</li>
<li>PapaParse jQuery CSV parser: CSV to JSON (22)</li>
<li>PapaParse: CSV to JSON Form (24)</li>
<li>PapaParse: JSON to CSV (23)</li>
<li>PipSlider using fmScript and scriptParam fields and GetWebViewerValues script (3)</li>
<li>PipsSlider - FM18 using fmURL and fmURLOptions field (4)</li>
<li>PipsSlider - FM18 using fmURL and GetWevViewerValues_ALT script (18)</li>
<li>PipsSlider - FM19 using FileMaker.PerformScript and GetWevViewerValues_ALT (19)</li>
<li>Really Big Time with Seconds (39)</li>
<li>Spinner (38)</li>
<li>WebForm-1 (35)</li>
<li>WebForm-2 (36)</li>
<li>WebForm-3 (37)</li>
</ul>

## Other Demos

![Other_Demos](https://github.com/asktami/filemaker-javascript-playground/blob/main/screenshots/Other_Demos.png)

# Change Log

## 12/31/2021

- Added GoogleMap and GoogleMap An Address

## 12/30/2021

- Added jQueryUI Range Slider and Accordian
- Fixed Webforms 1-3 so that Rating value displays correctly after form submitted

## 10/27/2021

- Added user-defined parameters to PivotJS demo

## 10/24/2021

- Updated CSS and JS libraries;
- Added non-FileMaker JavaScript demos, Bootstrap Masonry with JS and Datatables "Cards"

## 10/20/2021

- Minor changes to PivotJS, NoUI Sliders - Multiple and jQuery WebForm demos

## 10/12/2021

- Added JSONATA and WebForm examples and check for internet connecton onOpen; added pause before Perform JavaScript in Web Viewer script step
