# Change Log

## [v1.2.1](https://github.com/gitbrent/pptxgenjs/tree/v1.2.1) (2017-02-26)
[Full Changelog](https://github.com/gitbrent/pptxgenjs/compare/v1.2.0...v1.2.1)

**Fixed Bugs:**
- Fixed issue with using percentages with `x`,`y`,`w`,`h` in `addTable()`
- Table formatting bug with rowspans and colspans [\#46](https://github.com/gitbrent/PptxGenJS/issues/46) ([itskun](https://github.com/itskun))

**Implemented Enhancements:**
- Allow more than a single 'x' and/or 'y' table location during Table Paging [\#43](https://github.com/gitbrent/PptxGenJS/issues/43) ([jenkinsns](https://github.com/jenkinsns))
- Bullets do not work with text objects in addText() method [\#44](https://github.com/gitbrent/PptxGenJS/issues/44) ([ellisgl](https://github.com/ellisgl))
- Table location and pagination [\#47](https://github.com/gitbrent/PptxGenJS/issues/47) ([itskun](https://github.com/itskun))
- Meta: Improve auto-paging in 'addTable()' [\#48](https://github.com/gitbrent/PptxGenJS/issues/48) ([gitbrent](https://github.com/gitbrent))
- Created a new common file (`pptxgenjs-demo.js`) to hold all demo code - now used by both the browser and the node demos.

## [v1.2.0](https://github.com/gitbrent/pptxgenjs/tree/v1.2.0) (2017-02-15)
[Full Changelog](https://github.com/gitbrent/pptxgenjs/compare/v1.1.6...v1.2.0)

**Implemented Enhancements:**
- Pagination for `slideObj.addTable()`? [\#21](https://github.com/gitbrent/PptxGenJS/issues/21) ([TheDorkSide74](https://github.com/TheDorkSide74))
- Add support for media (Audio,Video,YouTube) [\#26](https://github.com/gitbrent/PptxGenJS/issues/26) ([shashank2104](https://github.com/shashank2104))
- How to set text shadow? [\#28](https://github.com/gitbrent/PptxGenJS/issues/28) ([itskun](https://github.com/itskun))
- Allow custom Layout sizes (ex: A3) [\#29](https://github.com/gitbrent/PptxGenJS/issues/29) ([itskun](https://github.com/itskun))
- Table cell marginPt should allow zero and take TRBL array [\#32](https://github.com/gitbrent/PptxGenJS/issues/32) ([ellisgl](https://github.com/ellisgl))
- Formatting rules do not apply to string with '\n' in `addText()` [\#34](https://github.com/gitbrent/PptxGenJS/issues/34) ([itskun](https://github.com/itskun))
- Node module appends to last generated PPT on `save()` [\#38](https://github.com/gitbrent/PptxGenJS/issues/38) ([alexanderpepper](https://github.com/alexanderpepper))
- callback support for save method [\#40](https://github.com/gitbrent/PptxGenJS/issues/40) ([ellisgl](https://github.com/ellisgl))
- Callback for save method (nodejs only) [\#41](https://github.com/gitbrent/PptxGenJS/pull/41) ([ellisgl](https://github.com/ellisgl))

**Fixed Bugs:**
- Table formatting bug in `addTable()` [\#36](https://github.com/gitbrent/PptxGenJS/issues/36) ([itskun](https://github.com/itskun))

## [v1.1.6](https://github.com/gitbrent/pptxgenjs/tree/v1.1.6) (2017-01-19)
[Full Changelog](https://github.com/gitbrent/pptxgenjs/compare/v1.1.5...v1.1.6)

**Implemented Enhancements:**
- Support for animated GIFs in `addImage()` [\#22](https://github.com/gitbrent/PptxGenJS/issues/22) ([shashank2104](https://github.com/shashank2104))
- Added new `slideNumber` option allowing `x` and `y` placement of slide number [\#25](https://github.com/gitbrent/PptxGenJS/issues/25) ([priyaraskar](https://github.com/priyaraskar))

## [v1.1.5](https://github.com/gitbrent/pptxgenjs/tree/v1.1.5) (2017-01-17)
[Full Changelog](https://github.com/gitbrent/pptxgenjs/compare/v1.1.4...v1.1.5)

**Fixed Bugs:**
- Trouble running in NW.js [\#19](https://github.com/gitbrent/PptxGenJS/issues/19) ([GregReser](https://github.com/GregReser))
- Supported usage via node program instead of HTML [\#23](https://github.com/gitbrent/PptxGenJS/issues/23) ([parsleyt](https://github.com/parsleyt))

## [v1.1.4](https://github.com/gitbrent/pptxgenjs/tree/v1.1.4) (2017-01-04)
[Full Changelog](https://github.com/gitbrent/pptxgenjs/compare/v1.1.3...v1.1.4)

**Fixed Bugs:**
- Table formatting options set to default on empty cells [\#20](https://github.com/gitbrent/PptxGenJS/issues/20) ([rikvdk](https://github.com/rikvdk))
- Fixed issue with `addTable()` where passing "#" before hex value for `color` or `fill` option would generate an invalid slide

## [v1.1.3](https://github.com/gitbrent/pptxgenjs/tree/v1.1.3) (2016-12-28)
[Full Changelog](https://github.com/gitbrent/pptxgenjs/compare/v1.1.2...v1.1.3)

**Implemented Enhancements:**
- Add new options to `addSlidesForTable()` allowing for placement and size: `x`,`y`,`w`,`h` [\#18](https://github.com/gitbrent/PptxGenJS/issues/18) ([priyaraskar](https://github.com/priyaraskar))

**Fixed Bugs:**
- Cannot read property 'opts' of null [\#17](https://github.com/gitbrent/PptxGenJS/issues/17) ([ninas880025](https://github.com/ninas880025))

## [v1.1.2](https://github.com/gitbrent/pptxgenjs/tree/v1.1.2) (2016-12-16)
[Full Changelog](https://github.com/gitbrent/pptxgenjs/compare/v1.1.1...v1.1.2)

**Implemented Enhancements:**
- The Slide `addTable()` method was modified to reduce the options passed from 2 objects to a single one

**Fixed Bugs:**
- The colW `addTable()` option is not working [\#15](https://github.com/gitbrent/PptxGenJS/issues/15) ([ninas880025](https://github.com/ninas880025))
- Modified `addSlidesForTable()`: table selectors made more specific by selecting only direct children now (nested tables would cause excessive looping) [\#14](https://github.com/gitbrent/PptxGenJS/issues/14) ([forrahul123](https://github.com/forrahul123))
- Fixed crash caused by calling `addText` without an options object

## [v1.1.1](https://github.com/gitbrent/pptxgenjs/tree/v1.1.1) (2016-12-08)
[Full Changelog](https://github.com/gitbrent/pptxgenjs/compare/v1.1.0...v1.1.1)

**Implemented Enhancements:**
- Major documentation update
- Added instructions to `pptxgenjs.masters.js` file, plus more examples and code
- Added sandbox/ad-hoc code area to demo page

**Fixed Bugs:**
- Table with 7 columns generates an invalid pptx file [\#12](https://github.com/gitbrent/PptxGenJS/issues/12) ([rikvdk](https://github.com/rikvdk))

## [v1.1.0](https://github.com/gitbrent/pptxgenjs/tree/v1.1.0) (2016-11-22)
[Full Changelog](https://github.com/gitbrent/pptxgenjs/compare/v1.0.1...v1.1.0)

**Implemented Enhancements:**
- Added support for base64-encoded images
- Adding npm dependencies [\#4](https://github.com/gitbrent/PptxGenJS/pull/1) ([DzmitryDulko](https://github.com/DzmitryDulko))
- Added support for italic text [\#6](https://github.com/gitbrent/PptxGenJS/issues/6) ([stevenljacobsen](https://github.com/stevenljacobsen))
- Added ability to selectively override Master Slide background color/image [\#7](https://github.com/gitbrent/PptxGenJS/issues/7) ([stevenljacobsen](https://github.com/stevenljacobsen))
- How can customize pptx theme? [\#9](https://github.com/gitbrent/PptxGenJS/issues/9) ([ielijose](https://github.com/ielijose))
- Add Rectangle to supported Master Slide shapes [\#10](https://github.com/gitbrent/PptxGenJS/pull/10) ([ielijose](https://github.com/ielijose))
- Added support for bulleted text [\#11](https://github.com/gitbrent/PptxGenJS/issues/11) ([gojko](https://github.com/gojko))

**Fixed Bugs:**
- Fix repo URL in package.json [\#5](https://github.com/gitbrent/PptxGenJS/pull/5) ([pdehaan](https://github.com/pdehaan))

## [v1.0.1](https://github.com/gitbrent/pptxgenjs/tree/v1.0.1) (2016-09-03)
[Full Changelog](https://github.com/gitbrent/pptxgenjs/compare/v1.0.0...v1.0.1)

**Implemented enhancements:**
- Moved from `cx` and `cy` option keys to `w` and `h`
- Adding ability to load data uri as images/Updating jszip library [\#2](https://github.com/gitbrent/PptxGenJS/pull/2) ([DzmitryDulko](https://github.com/DzmitryDulko))
- Publish library as npm package [\#3](https://github.com/gitbrent/PptxGenJS/issues/3) ([DzmitryDulko](https://github.com/DzmitryDulko))

**Fixed Bugs:**
- Fixed resource references [\#1](https://github.com/gitbrent/PptxGenJS/pull/1) ([DzmitryDulko](https://github.com/DzmitryDulko))

## [v1.0.0](https://github.com/gitbrent/pptxgenjs/tree/v1.0.0) (2016-03-29)

**Initial Release**
