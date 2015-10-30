# SVG path data polyfill

Polyfill for SVG 2 getPathData() and setPathData() methods. Does not rely on path.pathSegList API. Based on proper parser rather than regular expressions.

Based on:
- SVGPathDataParser by Gavin Kistner (MIT License)
  https://github.com/hughsk/svg-path-parser 
- SVGPathNormalizer by Tadahisa Motooka (MIT License)
  https://github.com/motooka/SVGPathNormalizer/tree/master/src
- arcToCubicCurves() by Dmitry Baranovskiy (MIT License)
  https://github.com/DmitryBaranovskiy/raphael/blob/v2.1.1/raphael.core.js#L1837

More info:
- https://svgwg.org/specs/paths/#InterfaceSVGPathData
- https://lists.w3.org/Archives/Public/www-svg/2015Feb/0036.html
- https://groups.google.com/a/chromium.org/forum/#!searchin/blink-dev/pathSegList/blink-dev/EDC3cBg9mCU/Ukhx2UXmCgAJ
