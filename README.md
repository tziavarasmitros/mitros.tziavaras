# 1973mitros<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<html b:version='2' class='v2' expr:dir='data:blog.languageDirection' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>
  <head>
    <meta expr:content='data:blog.isMobile         ? &quot;width=device-width,initial-scale=1.0,minimum-scale=1.0,maximum-scale=1.0&quot;         : &quot;width=1100&quot;' name='viewport'/>
    <b:include data='blog' name='all-head-content'/>
    <title><data:blog.pageTitle/></title>

    <b:skin><![CDATA[/*
-----------------------------------------------
Blogger Template Style
Name:     Awesome Inc.
Designer: Tina Chen
URL:      tinachen.org
----------------------------------------------- */

/* Variable definitions
   ====================
   <Variable name="keycolor" description="Main Color" type="color" default="#ffffff" value="#ffffff"/>

   <Group description="Page" selector="body">
     <Variable name="body.font" description="Font" type="font"
         default="normal normal 13px Arial, Tahoma, Helvetica, FreeSans, sans-serif" value="normal normal 13px Arial, Tahoma, Helvetica, FreeSans, sans-serif"/>
     <Variable name="body.background.color" description="Background Color" type="color" default="#000000" value="#000000"/>
     <Variable name="body.text.color" description="Text Color" type="color" default="#ffffff" value="#ffffff"/>
   </Group>

   <Group description="Links" selector=".main-inner">
     <Variable name="link.color" description="Link Color" type="color" default="#888888" value="#888888"/>
     <Variable name="link.visited.color" description="Visited Color" type="color" default="#444444" value="#444444"/>
     <Variable name="link.hover.color" description="Hover Color" type="color" default="#cccccc" value="#cccccc"/>
   </Group>

   <Group description="Blog Title" selector=".header h1">
     <Variable name="header.font" description="Title Font" type="font"
         default="normal bold 40px Arial, Tahoma, Helvetica, FreeSans, sans-serif" value="normal bold 40px Arial, Tahoma, Helvetica, FreeSans, sans-serif"/>
     <Variable name="header.text.color" description="Title Color" type="color" default="$(body.text.color)"  value="#ffffff"/>
     <Variable name="header.background.color" description="Header Background" type="color" default="transparent"  value="transparent"/>
   </Group>

   <Group description="Blog Description" selector=".header .description">
     <Variable name="description.font" description="Font" type="font"
         default="normal normal 14px Arial, Tahoma, Helvetica, FreeSans, sans-serif" value="normal normal 14px Arial, Tahoma, Helvetica, FreeSans, sans-serif"/>
     <Variable name="description.text.color" description="Text Color" type="color"
         default="$(body.text.color)"  value="#ffffff"/>
   </Group>

   <Group description="Tabs Text" selector=".tabs-inner .widget li a">
     <Variable name="tabs.font" description="Font" type="font"
         default="normal bold 14px Arial, Tahoma, Helvetica, FreeSans, sans-serif" value="normal bold 14px Arial, Tahoma, Helvetica, FreeSans, sans-serif"/>
     <Variable name="tabs.text.color" description="Text Color" type="color" default="$(body.text.color)" value="#ffffff"/>
     <Variable name="tabs.selected.text.color" description="Selected Color" type="color" default="$(tabs.text.color)" value="#ffffff"/>
   </Group>

   <Group description="Tabs Background" selector=".tabs-outer .PageList">
     <Variable name="tabs.background.color" description="Background Color" type="color" default="#141414" value="#141414"/>
     <Variable name="tabs.selected.background.color" description="Selected Color" type="color" default="#444444" value="#444444"/>
     <Variable name="tabs.border.color" description="Border Color" type="color" default="$(widget.border.color)" value="#222222"/>
   </Group>

   <Group description="Date Header" selector=".main-inner .widget h2.date-header, .main-inner .widget h2.date-header span">
     <Variable name="date.font" description="Font" type="font"
         default="normal normal 14px Arial, Tahoma, Helvetica, FreeSans, sans-serif" value="normal normal 14px Arial, Tahoma, Helvetica, FreeSans, sans-serif"/>
     <Variable name="date.text.color" description="Text Color" type="color" default="#666666" value="#666666"/>
     <Variable name="date.border.color" description="Border Color" type="color" default="$(widget.border.color)" value="#222222"/>
   </Group>

   <Group description="Post Title" selector="h3.post-title, h4, h3.post-title a">
     <Variable name="post.title.font" description="Font" type="font"
         default="normal bold 22px Arial, Tahoma, Helvetica, FreeSans, sans-serif" value="normal bold 22px Arial, Tahoma, Helvetica, FreeSans, sans-serif"/>
     <Variable name="post.title.text.color" description="Text Color" type="color" default="$(body.text.color)" value="#ffffff"/>
   </Group>

   <Group description="Post Background" selector=".post">
     <Variable name="post.background.color" description="Background Color" type="color" default="$(widget.background.color)"  value="#141414"/>
     <Variable name="post.border.color" description="Border Color" type="color" default="$(widget.border.color)"  value="#222222"/>
     <Variable name="post.border.bevel.color" description="Bevel Color" type="color" default="$(widget.border.color)" value="#222222"/>
   </Group>

   <Group description="Gadget Title" selector="h2">
     <Variable name="widget.title.font" description="Font" type="font"
        default="normal bold 14px Arial, Tahoma, Helvetica, FreeSans, sans-serif" value="normal bold 14px Arial, Tahoma, Helvetica, FreeSans, sans-serif"/>
     <Variable name="widget.title.text.color" description="Text Color" type="color" default="$(body.text.color)" value="#ffffff"/>
   </Group>

   <Group description="Gadget Text" selector=".sidebar .widget">
     <Variable name="widget.font" description="Font" type="font"
        default="normal normal 14px Arial, Tahoma, Helvetica, FreeSans, sans-serif" value="normal normal 14px Arial, Tahoma, Helvetica, FreeSans, sans-serif"/>
     <Variable name="widget.text.color" description="Text Color" type="color" default="$(body.text.color)" value="#ffffff"/>
     <Variable name="widget.alternate.text.color" description="Alternate Color" type="color" default="#666666" value="#666666"/>
   </Group>

   <Group description="Gadget Links" selector=".sidebar .widget">
     <Variable name="widget.link.color" description="Link Color" type="color" default="$(link.color)" value="#888888"/>
     <Variable name="widget.link.visited.color" description="Visited Color" type="color" default="$(link.visited.color)" value="#444444"/>
     <Variable name="widget.link.hover.color" description="Hover Color" type="color" default="$(link.hover.color)" value="#cccccc"/>
   </Group>

   <Group description="Gadget Background" selector=".sidebar .widget">
     <Variable name="widget.background.color" description="Background Color" type="color" default="#141414" value="#141414"/>
     <Variable name="widget.border.color" description="Border Color" type="color" default="#222222" value="#222222"/>
     <Variable name="widget.border.bevel.color" description="Bevel Color" type="color" default="#000000" value="#000000"/>
   </Group>

   <Group description="Sidebar Background" selector=".column-left-inner .column-right-inner">
     <Variable name="widget.outer.background.color" description="Background Color" type="color" default="transparent"  value="transparent"/>
   </Group>

   <Group description="Images" selector=".main-inner">
     <Variable name="image.background.color" description="Background Color" type="color" default="transparent" value="#222222"/>
     <Variable name="image.border.color" description="Border Color" type="color" default="transparent" value="transparent"/>
   </Group>

   <Group description="Feed" selector=".blog-feeds">
      <Variable name="feed.text.color" description="Text Color" type="color" default="$(body.text.color)" value="#ffffff"/>
   </Group>

   <Group description="Feed Links" selector=".blog-feeds">
     <Variable name="feed.link.color" description="Link Color" type="color" default="$(link.color)" value="#888888"/>
     <Variable name="feed.link.visited.color" description="Visited Color" type="color" default="$(link.visited.color)" value="#444444"/>
     <Variable name="feed.link.hover.color" description="Hover Color" type="color" default="$(link.hover.color)" value="#cccccc"/>
   </Group>

   <Group description="Pager" selector=".blog-pager">
     <Variable name="pager.background.color" description="Background Color" type="color" default="$(post.background.color)"  value="#141414"/>
   </Group>

   <Group description="Footer" selector=".footer-outer">
     <Variable name="footer.background.color" description="Background Color" type="color" default="$(widget.background.color)"  value="#141414"/>
     <Variable name="footer.text.color" description="Text Color" type="color" default="$(body.text.color)"  value="#ffffff"/>
   </Group>

   <Variable name="title.shadow.spread" description="Title Shadow" type="length" default="-1px" min="-1px" max="100px" value="-1px"/>

   <Variable name="body.background" description="Body Background" type="background"
       color="$(body.background.color)"
       default="$(color) none repeat scroll top left" value="$(color) url(http://2.bp.blogspot.com/-Wafc-2Q_TvQ/VdrgzoxrXzI/AAAAAAAAAi4/wE4ZQUrYHMA/s0/11666183_829542763807886_7763111986889388618_n.jpg) repeat scroll top left"/>
   <Variable name="body.background.gradient.cap" description="Body Gradient Cap" type="url"
       default="none" value="none"/>
   <Variable name="body.background.size" description="Body Background Size" type="string" default="auto" value="auto"/>

   <Variable name="tabs.background.gradient" description="Tabs Background Gradient" type="url"
       default="none" value="none"/>

   <Variable name="header.background.gradient" description="Header Background Gradient" type="url" default="none"  value="none"/>
   <Variable name="header.padding.top" description="Header Top Padding" type="length" default="22px" min="0" max="100px" value="22px"/>
   <Variable name="header.margin.top" description="Header Top Margin" type="length" default="0" min="0" max="100px" value="0"/>
   <Variable name="header.margin.bottom" description="Header Bottom Margin" type="length" default="0" min="0" max="100px" value="0"/>

   <Variable name="widget.padding.top" description="Widget Padding Top" type="length" default="8px" min="0" max="20px" value="8px"/>
   <Variable name="widget.padding.side" description="Widget Padding Side" type="length" default="15px" min="0" max="100px" value="15px"/>
   <Variable name="widget.outer.margin.top" description="Widget Top Margin" type="length" default="0" min="0" max="100px" value="0"/>
   <Variable name="widget.outer.background.gradient" description="Gradient" type="url" default="none"  value="none"/>
   <Variable name="widget.border.radius" description="Gadget Border Radius" type="length" default="0" min="0" max="100px" value="0"/>
   <Variable name="outer.shadow.spread" description="Outer Shadow Size" type="length" default="0" min="0" max="100px" value="0"/>

   <Variable name="date.header.border.radius.top" description="Date Header Border Radius Top" type="length" default="0" min="0" max="100px" value="0"/>
   <Variable name="date.header.position" description="Date Header Position" type="length" default="15px" min="0" max="100px" value="15px"/>

   <Variable name="date.space" description="Date Space" type="length" default="30px" min="0" max="100px" value="30px"/>
   <Variable name="date.position" description="Date Float" type="string" default="static"  value="static"/>
   <Variable name="date.padding.bottom" description="Date Padding Bottom" type="length" default="0" min="0" max="100px" value="0"/>
   <Variable name="date.border.size" description="Date Border Size" type="length" default="0" min="0" max="10px" value="0"/>
   <Variable name="date.background" description="Date Background" type="background" color="transparent"
       default="$(color) none no-repeat scroll top left"  value="$(color) none no-repeat scroll top left"/>
   <Variable name="date.first.border.radius.top" description="Date First top radius" type="length" default="$(widget.border.radius)" min="0" max="100px" value="$(widget.border.radius)"/>
   <Variable name="date.last.space.bottom" description="Date Last Space Bottom" type="length"
       default="20px" min="0" max="100px" value="20px"/>
   <Variable name="date.last.border.radius.bottom" description="Date Last bottom radius" type="length" default="$(widget.border.radius)" min="0" max="100px" value="$(widget.border.radius)"/>

   <Variable name="post.first.padding.top" description="First Post Padding Top" type="length" default="0" min="0" max="100px" value="0"/>

   <Variable name="image.shadow.spread" description="Image Shadow Size" type="length" default="0" min="0" max="100px" value="0"/>
   <Variable name="image.border.radius" description="Image Border Radius" type="length" default="0" min="0" max="100px" value="0"/>

   <Variable name="separator.outdent" description="Separator Outdent" type="length" default="15px" min="0" max="100px" value="15px"/>
   <Variable name="title.separator.border.size" description="Widget Title Border Size" type="length" default="1px" min="0" max="10px" value="1px"/>
   <Variable name="list.separator.border.size" description="List Separator Border Size" type="length" default="1px" min="0" max="10px" value="1px"/>
   <Variable name="shadow.spread" description="Shadow Size" type="length" default="0" min="0" max="100px" value="0"/>

   <Variable name="startSide" description="Side where text starts in blog language" type="automatic" default="left" value="left"/>
   <Variable name="endSide" description="Side where text ends in blog language" type="automatic" default="right" value="right"/>

   <Variable name="date.side" description="Side where date header is placed" type="string" default="$(endSide)" value="$(endSide)"/>

   <Variable name="pager.border.radius.top" description="Pager Border Top Radius" type="length" default="$(widget.border.radius)" min="0" max="100px" value="$(widget.border.radius)"/>
   <Variable name="pager.space.top" description="Pager Top Space" type="length" default="1em" min="0" max="20em" value="1em"/>

   <Variable name="footer.background.gradient" description="Background Gradient" type="url" default="none"  value="none"/>

   <Variable name="mobile.background.size" description="Mobile Background Size" type="string"
       default="$(body.background.size)" value="$(body.background.size)"/>
   <Variable name="mobile.background.overlay" description="Mobile Background Overlay" type="string"
       default="transparent none repeat scroll top left" value="transparent none repeat scroll top left"/>
   <Variable name="mobile.button.color" description="Mobile Button Color" type="color" default="#ffffff"  value="#ffffff"/>
*/

/* Content
----------------------------------------------- */
body {
  font: $(body.font);
  color: $(body.text.color);
  background: $(body.background);
}

html body .content-outer {
  min-width: 0;
  max-width: 100%;
  width: 100%;
}

a:link {
  text-decoration: none;
  color: $(link.color);
}

a:visited {
  text-decoration: none;
  color: $(link.visited.color);
}

a:hover {
  text-decoration: underline;
  color: $(link.hover.color);
}

.body-fauxcolumn-outer .cap-top {
  position: absolute;
  z-index: 1;

  height: 276px;
  width: 100%;

  background: transparent $(body.background.gradient.cap) repeat-x scroll top left;
  _background-image: none;
}

/* Columns
----------------------------------------------- */
.content-inner {
  padding: 0;
}

.header-inner .section {
  margin: 0 16px;
}

.tabs-inner .section {
  margin: 0 16px;
}

.main-inner {
  padding-top: $(date.space);
}

.main-inner .column-center-inner,
.main-inner .column-left-inner,
.main-inner .column-right-inner {
  padding: 0 5px;
}

*+html body .main-inner .column-center-inner {
  margin-top: -$(date.space);
}

#layout .main-inner .column-center-inner {
  margin-top: 0;
}

/* Header
----------------------------------------------- */
.header-outer {
  margin: $(header.margin.top) 0 $(header.margin.bottom) 0;
  background: $(header.background.color) $(header.background.gradient) repeat scroll 0 0;
}

.Header h1 {
  font: $(header.font);
  color: $(header.text.color);
  text-shadow: 0 0 $(title.shadow.spread) #000000;
}

.Header h1 a {
  color: $(header.text.color);
}

.Header .description {
  font: $(description.font);
  color: $(description.text.color);
}

.header-inner .Header .titlewrapper,
.header-inner .Header .descriptionwrapper {
  padding-left: 0;
  padding-right: 0;
  margin-bottom: 0;
}

.header-inner .Header .titlewrapper {
  padding-top: $(header.padding.top);
}

/* Tabs
----------------------------------------------- */
.tabs-outer {
  overflow: hidden;
  position: relative;
  background: $(tabs.background.color) $(tabs.background.gradient) repeat scroll 0 0;
}

#layout .tabs-outer {
  overflow: visible;
}

.tabs-cap-top, .tabs-cap-bottom {
  position: absolute;
  width: 100%;

  border-top: 1px solid $(tabs.border.color);

}

.tabs-cap-bottom {
  bottom: 0;
}

.tabs-inner .widget li a {
  display: inline-block;

  margin: 0;
  padding: .6em 1.5em;

  font: $(tabs.font);
  color: $(tabs.text.color);

  border-top: 1px solid $(tabs.border.color);
  border-bottom: 1px solid $(tabs.border.color);
  border-$startSide: 1px solid $(tabs.border.color);

  height: 16px;
  line-height: 16px;
}

.tabs-inner .widget li:last-child a {
  border-$endSide: 1px solid $(tabs.border.color);
}

.tabs-inner .widget li.selected a, .tabs-inner .widget li a:hover {
  background: $(tabs.selected.background.color) $(tabs.background.gradient) repeat-x scroll 0 -100px;
  color: $(tabs.selected.text.color);
}

/* Headings
----------------------------------------------- */
h2 {
  font: $(widget.title.font);
  color: $(widget.title.text.color);
}

/* Widgets
----------------------------------------------- */
.main-inner .section {
  margin: 0 27px;
  padding: 0;
}

.main-inner .column-left-outer,
.main-inner .column-right-outer {
  margin-top: $(widget.outer.margin.top);
}

#layout .main-inner .column-left-outer,
#layout .main-inner .column-right-outer {
  margin-top: 0;
}

.main-inner .column-left-inner,
.main-inner .column-right-inner {
  background: $(widget.outer.background.color) $(widget.outer.background.gradient) repeat 0 0;

  -moz-box-shadow: 0 0 $(outer.shadow.spread) rgba(0, 0, 0, .2);
  -webkit-box-shadow: 0 0 $(outer.shadow.spread) rgba(0, 0, 0, .2);
  -goog-ms-box-shadow: 0 0 $(outer.shadow.spread) rgba(0, 0, 0, .2);
  box-shadow: 0 0 $(outer.shadow.spread) rgba(0, 0, 0, .2);

  -moz-border-radius: $(widget.border.radius);
  -webkit-border-radius: $(widget.border.radius);
  -goog-ms-border-radius: $(widget.border.radius);
  border-radius: $(widget.border.radius);
}

#layout .main-inner .column-left-inner,
#layout .main-inner .column-right-inner {
  margin-top: 0;
}

.sidebar .widget {
  font: $(widget.font);
  color: $(widget.text.color);
}

.sidebar .widget a:link {
  color: $(widget.link.color);
}

.sidebar .widget a:visited {
  color: $(widget.link.visited.color);
}

.sidebar .widget a:hover {
  color: $(widget.link.hover.color);
}

.sidebar .widget h2 {
  text-shadow: 0 0 $(title.shadow.spread) #000000;
}

.main-inner .widget {
  background-color: $(widget.background.color);
  border: 1px solid $(widget.border.color);
  padding: 0 $(widget.padding.side) 15px;
  margin: 20px -16px;

  -moz-box-shadow: 0 0 $(shadow.spread) rgba(0, 0, 0, .2);
  -webkit-box-shadow: 0 0 $(shadow.spread) rgba(0, 0, 0, .2);
  -goog-ms-box-shadow: 0 0 $(shadow.spread) rgba(0, 0, 0, .2);
  box-shadow: 0 0 $(shadow.spread) rgba(0, 0, 0, .2);

  -moz-border-radius: $(widget.border.radius);
  -webkit-border-radius: $(widget.border.radius);
  -goog-ms-border-radius: $(widget.border.radius);
  border-radius: $(widget.border.radius);
}

.main-inner .widget h2 {
  margin: 0 -$(separator.outdent);
  padding: .6em $(separator.outdent) .5em;
  border-bottom: 1px solid $(widget.border.bevel.color);
}

.footer-inner .widget h2 {
  padding: 0 0 .4em;

  border-bottom: 1px solid $(widget.border.bevel.color);
}

.main-inner .widget h2 + div, .footer-inner .widget h2 + div {
  border-top: $(title.separator.border.size) solid $(widget.border.color);
  padding-top: $(widget.padding.top);
}

.main-inner .widget .widget-content {
  margin: 0 -$(separator.outdent);
  padding: 7px $(separator.outdent) 0;
}

.main-inner .widget ul, .main-inner .widget #ArchiveList ul.flat {
  margin: -$(widget.padding.top) -15px 0;
  padding: 0;

  list-style: none;
}

.main-inner .widget #ArchiveList {
  margin: -$(widget.padding.top) 0 0;
}

.main-inner .widget ul li, .main-inner .widget #ArchiveList ul.flat li {
  padding: .5em 15px;
  text-indent: 0;

  color: $(widget.alternate.text.color);

  border-top: $(list.separator.border.size) solid $(widget.border.color);
  border-bottom: 1px solid $(widget.border.bevel.color);
}

.main-inner .widget #ArchiveList ul li {
  padding-top: .25em;
  padding-bottom: .25em;
}

.main-inner .widget ul li:first-child, .main-inner .widget #ArchiveList ul.flat li:first-child {
  border-top: none;
}

.main-inner .widget ul li:last-child, .main-inner .widget #ArchiveList ul.flat li:last-child {
  border-bottom: none;
}

.post-body {
  position: relative;
}

.main-inner .widget .post-body ul {
  padding: 0 2.5em;
  margin: .5em 0;

  list-style: disc;
}

.main-inner .widget .post-body ul li {
  padding: 0.25em 0;
  margin-bottom: .25em;

  color: $(body.text.color);

  border: none;
}

.footer-inner .widget ul {
  padding: 0;

  list-style: none;
}

.widget .zippy {
  color: $(widget.alternate.text.color);
}

/* Posts
----------------------------------------------- */
body .main-inner .Blog {
  padding: 0;
  margin-bottom: 1em;

  background-color: transparent;
  border: none;

  -moz-box-shadow: 0 0 0 rgba(0, 0, 0, 0);
  -webkit-box-shadow: 0 0 0 rgba(0, 0, 0, 0);
  -goog-ms-box-shadow: 0 0 0 rgba(0, 0, 0, 0);
  box-shadow: 0 0 0 rgba(0, 0, 0, 0);
}

.main-inner .section:last-child .Blog:last-child {
  padding: 0;
  margin-bottom: 1em;
}

.main-inner .widget h2.date-header {
  margin: 0 -15px 1px;
  padding: 0 0 $(date.padding.bottom) 0;

  font: $(date.font);
  color: $(date.text.color);

  background: $(date.background);

  border-top: $(date.border.size) solid $(date.border.color);
  border-bottom: 1px solid $(widget.border.bevel.color);

  -moz-border-radius-topleft: $(date.header.border.radius.top);
  -moz-border-radius-topright: $(date.header.border.radius.top);
  -webkit-border-top-left-radius: $(date.header.border.radius.top);
  -webkit-border-top-right-radius: $(date.header.border.radius.top);
  border-top-left-radius: $(date.header.border.radius.top);
  border-top-right-radius: $(date.header.border.radius.top);

  position: $(date.position);
  bottom: 100%;
  $(date.side): $(date.header.position);
  text-shadow: 0 0 $(title.shadow.spread) #000000;
}

.main-inner .widget h2.date-header span {
  font: $(date.font);
  display: block;
  padding: .5em 15px;
  border-left: $(date.border.size) solid $(date.border.color);
  border-right: $(date.border.size) solid $(date.border.color);
}

.date-outer {
  position: relative;
  margin: $(date.space) 0 20px;
  padding: 0 15px;

  background-color: $(post.background.color);
  border: 1px solid $(post.border.color);

  -moz-box-shadow: 0 0 $(shadow.spread) rgba(0, 0, 0, .2);
  -webkit-box-shadow: 0 0 $(shadow.spread) rgba(0, 0, 0, .2);
  -goog-ms-box-shadow: 0 0 $(shadow.spread) rgba(0, 0, 0, .2);
  box-shadow: 0 0 $(shadow.spread) rgba(0, 0, 0, .2);

  -moz-border-radius: $(widget.border.radius);
  -webkit-border-radius: $(widget.border.radius);
  -goog-ms-border-radius: $(widget.border.radius);
  border-radius: $(widget.border.radius);
}

.date-outer:first-child {
  margin-top: 0;
}

.date-outer:last-child {
  margin-bottom: $(date.last.space.bottom);

  -moz-border-radius-bottomleft: $(date.last.border.radius.bottom);
  -moz-border-radius-bottomright: $(date.last.border.radius.bottom);
  -webkit-border-bottom-left-radius: $(date.last.border.radius.bottom);
  -webkit-border-bottom-right-radius: $(date.last.border.radius.bottom);
  -goog-ms-border-bottom-left-radius: $(date.last.border.radius.bottom);
  -goog-ms-border-bottom-right-radius: $(date.last.border.radius.bottom);
  border-bottom-left-radius: $(date.last.border.radius.bottom);
  border-bottom-right-radius: $(date.last.border.radius.bottom);
}

.date-posts {
  margin: 0 -$(separator.outdent);
  padding: 0 $(separator.outdent);

  clear: both;
}

.post-outer, .inline-ad {
  border-top: 1px solid $(post.border.bevel.color);

  margin: 0 -$(separator.outdent);
  padding: 15px $(separator.outdent);
}

.post-outer {
  padding-bottom: 10px;
}

.post-outer:first-child {
  padding-top: $(post.first.padding.top);
  border-top: none;
}

.post-outer:last-child, .inline-ad:last-child {
  border-bottom: none;
}

.post-body {
  position: relative;
}

.post-body img {
  padding: 8px;
  background: $(image.background.color);
  border: 1px solid $(image.border.color);

  -moz-box-shadow: 0 0 $(image.shadow.spread) rgba(0, 0, 0, .2);
  -webkit-box-shadow: 0 0 $(image.shadow.spread) rgba(0, 0, 0, .2);
  box-shadow: 0 0 $(image.shadow.spread) rgba(0, 0, 0, .2);

  -moz-border-radius: $(image.border.radius);
  -webkit-border-radius: $(image.border.radius);
  border-radius: $(image.border.radius);
}

h3.post-title, h4 {
  font: $(post.title.font);
  color: $(post.title.text.color);
}

h3.post-title a {
  font: $(post.title.font);
  color: $(post.title.text.color);
}

h3.post-title a:hover {
  color: $(link.hover.color);
  text-decoration: underline;
}

.post-header {
  margin: 0 0 1em;
}

.post-body {
  line-height: 1.4;
}

.post-outer h2 {
  color: $(body.text.color);
}

.post-footer {
  margin: 1.5em 0 0;
}

#blog-pager {
  padding: 15px;
  font-size: 120%;

  background-color: $(pager.background.color);
  border: 1px solid $(widget.border.color);

  -moz-box-shadow: 0 0 $(shadow.spread) rgba(0, 0, 0, .2);
  -webkit-box-shadow: 0 0 $(shadow.spread) rgba(0, 0, 0, .2);
  -goog-ms-box-shadow: 0 0 $(shadow.spread) rgba(0, 0, 0, .2);
  box-shadow: 0 0 $(shadow.spread) rgba(0, 0, 0, .2);

  -moz-border-radius: $(widget.border.radius);
  -webkit-border-radius: $(widget.border.radius);
  -goog-ms-border-radius: $(widget.border.radius);
  border-radius: $(widget.border.radius);

  -moz-border-radius-topleft: $(pager.border.radius.top);
  -moz-border-radius-topright: $(pager.border.radius.top);
  -webkit-border-top-left-radius: $(pager.border.radius.top);
  -webkit-border-top-right-radius: $(pager.border.radius.top);
  -goog-ms-border-top-left-radius: $(pager.border.radius.top);
  -goog-ms-border-top-right-radius: $(pager.border.radius.top);
  border-top-left-radius: $(pager.border.radius.top);
  border-top-right-radius-topright: $(pager.border.radius.top);

  margin-top: $(pager.space.top);
}

.blog-feeds, .post-feeds {
  margin: 1em 0;
  text-align: center;
  color: $(feed.text.color);
}

.blog-feeds a, .post-feeds a {
  color: $(feed.link.color);
}

.blog-feeds a:visited, .post-feeds a:visited {
  color: $(feed.link.visited.color);
}

.blog-feeds a:hover, .post-feeds a:hover {
  color: $(feed.link.hover.color);
}

.post-outer .comments {
  margin-top: 2em;
}

/* Comments
----------------------------------------------- */
.comments .comments-content .icon.blog-author {
  background-repeat: no-repeat;
  background-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABIAAAASCAYAAABWzo5XAAAAAXNSR0IArs4c6QAAAAZiS0dEAP8A/wD/oL2nkwAAAAlwSFlzAAALEgAACxIB0t1+/AAAAAd0SU1FB9sLFwMeCjjhcOMAAAD+SURBVDjLtZSvTgNBEIe/WRRnm3U8RC1neQdsm1zSBIU9VVF1FkUguQQsD9ITmD7ECZIJSE4OZo9stoVjC/zc7ky+zH9hXwVwDpTAWWLrgS3QAe8AZgaAJI5zYAmc8r0G4AHYHQKVwII8PZrZFsBFkeRCABYiMh9BRUhnSkPTNCtVXYXURi1FpBDgArj8QU1eVXUzfnjv7yP7kwu1mYrkWlU33vs1QNu2qU8pwN0UpKoqokjWwCztrMuBhEhmh8bD5UDqur75asbcX0BGUB9/HAMB+r32hznJgXy2v0sGLBcyAJ1EK3LFcbo1s91JeLwAbwGYu7TP/3ZGfnXYPgAVNngtqatUNgAAAABJRU5ErkJggg==);
}

.comments .comments-content .loadmore a {
  border-top: 1px solid $(tabs.border.color);
  border-bottom: 1px solid $(tabs.border.color);
}

.comments .continue {
  border-top: 2px solid $(tabs.border.color);
}

/* Footer
----------------------------------------------- */
.footer-outer {
  margin: -$(shadow.spread) 0 -1px;
  padding: $(shadow.spread) 0 0;
  color: $(footer.text.color);
  overflow: hidden;
}

.footer-fauxborder-left {
  border-top: 1px solid $(widget.border.color);
  background: $(footer.background.color) $(footer.background.gradient) repeat scroll 0 0;

  -moz-box-shadow: 0 0 $(shadow.spread) rgba(0, 0, 0, .2);
  -webkit-box-shadow: 0 0 $(shadow.spread) rgba(0, 0, 0, .2);
  -goog-ms-box-shadow: 0 0 $(shadow.spread) rgba(0, 0, 0, .2);
  box-shadow: 0 0 $(shadow.spread) rgba(0, 0, 0, .2);

  margin: 0 -$(shadow.spread);
}

/* Mobile
----------------------------------------------- */
body.mobile {
  background-size: $(mobile.background.size);
}

.mobile .body-fauxcolumn-outer {
  background: $(mobile.background.overlay);
}

*+html body.mobile .main-inner .column-center-inner {
  margin-top: 0;
}

.mobile .main-inner .widget {
  padding: 0 0 15px;
}

.mobile .main-inner .widget h2 + div,
.mobile .footer-inner .widget h2 + div {
  border-top: none;
  padding-top: 0;
}

.mobile .footer-inner .widget h2 {
  padding: 0.5em 0;
  border-bottom: none;
}

.mobile .main-inner .widget .widget-content {
  margin: 0;
  padding: 7px 0 0;
}

.mobile .main-inner .widget ul,
.mobile .main-inner .widget #ArchiveList ul.flat {
  margin: 0 -15px 0;
}

.mobile .main-inner .widget h2.date-header {
  $(date.side): 0;
}

.mobile .date-header span {
  padding: 0.4em 0;
}

.mobile .date-outer:first-child {
  margin-bottom: 0;
  border: 1px solid $(post.border.color);

  -moz-border-radius-topleft: $(date.first.border.radius.top);
  -moz-border-radius-topright: $(date.first.border.radius.top);
  -webkit-border-top-left-radius: $(date.first.border.radius.top);
  -webkit-border-top-right-radius: $(date.first.border.radius.top);
  -goog-ms-border-top-left-radius: $(date.first.border.radius.top);
  -goog-ms-border-top-right-radius: $(date.first.border.radius.top);
  border-top-left-radius: $(date.first.border.radius.top);
  border-top-right-radius: $(date.first.border.radius.top);
}

.mobile .date-outer {
  border-color: $(post.border.color);
  border-width: 0 1px 1px;
}

.mobile .date-outer:last-child {
  margin-bottom: 0;
}

.mobile .main-inner {
  padding: 0;
}

.mobile .header-inner .section {
  margin: 0;
}

.mobile .post-outer, .mobile .inline-ad {
  padding: 5px 0;
}

.mobile .tabs-inner .section {
  margin: 0 10px;
}

.mobile .main-inner .widget h2 {
  margin: 0;
  padding: 0;
}

.mobile .main-inner .widget h2.date-header span {
  padding: 0;
}

.mobile .main-inner .widget .widget-content {
  margin: 0;
  padding: 7px 0 0;
}

.mobile #blog-pager {
  border: 1px solid transparent;
  background: $(footer.background.color) $(footer.background.gradient) repeat scroll 0 0;
}

.mobile .main-inner .column-left-inner,
.mobile .main-inner .column-right-inner {
  background: $(widget.outer.background.color) $(widget.outer.background.gradient) repeat 0 0;

  -moz-box-shadow: none;
  -webkit-box-shadow: none;
  -goog-ms-box-shadow: none;
  box-shadow: none;
}

.mobile .date-posts {
  margin: 0;
  padding: 0;
}

.mobile .footer-fauxborder-left {
  margin: 0;
  border-top: inherit;
}

.mobile .main-inner .section:last-child .Blog:last-child {
  margin-bottom: 0;
}

.mobile-index-contents {
  color: $(body.text.color);
}

.mobile .mobile-link-button {
  background: $(link.color) $(tabs.background.gradient) repeat scroll 0 0;
}

.mobile-link-button a:link, .mobile-link-button a:visited {
  color: $(mobile.button.color);
}

.mobile .tabs-inner .PageList .widget-content {
  background: transparent;
  border-top: 1px solid;
  border-color: $(tabs.border.color);
  color: $(tabs.text.color);
}

.mobile .tabs-inner .PageList .widget-content .pagelist-arrow {
  border-$startSide: 1px solid $(tabs.border.color);
}
/* color settings */
.playerBox_gsvb div.alldone_gsvb        { color : #0000cc; }
.playerBox_gsvb a.title_gsvb            { color : #0000cc; }

.playerBox_gsvb div.alldone_gsvb:hover  { color : #0000cc; }
.playerBox_gsvb a.title_gsvb:hover      { color : #0000cc; }
.resultsBox_gsvb div.resultDiv_gsvb     { border-color : #676767; }
.floatingPlayerBox_gsvb,
.floatingPlayerBox_gsvb *               { background-color : #ffffff; }
.floatingPlayerBox_gsvb                 { border : 1px solid #f0f0f0; }
                                        }
.floatingPlayer_gsvb                    { background-color : #ffffff; }

/*
 * The Player Box
 * - visible while playing
 * - collapsed while idle
 */
.playerBox_gsvb {
  display : block;
  margin-top : 4px;
  margin-bottom : 4px;
  margin-left : 10px;
  margin-right : 10px;
  text-align : center;
}

/**
 * Floating Player Box:
 *
 * note: top, left, z-index, height, width
 * are set in code. Limit your styling to color/opacity
 * Note the z-index of floatingPlayer should be one
 * higher than the z-index of the floatingPlayerBox.
 * Adjust as needed on sites with crazy layering.
*/
.floatingPlayerBox_gsvb {
  position : absolute;
  opacity : 0.90;
  -moz-opacity : 0.90;
  filter:alpha(opacity=90);
  z-index : 9998;
}
.floatingPlayer_gsvb {
  position : absolute;
  z-index : 9999;
}
.floatingBranding_gsvb {
  position : absolute;
}

.idle_gsvb {
  display : none;
}

.playing_gsvb {
  display : block;
}

.playerInnerBox_gsvb {
  margin-top : 2px;
}

/* keep a 1.33 ratio
 * (on widths > 300px, add 20px in height for controls)
 * small player:        180x135   4:3
 * medium player:       260x195   4:3
 * large player:        320x260   4:3 + 20px at bottom
 * extra large player:  480x380   4:3 + 20px at bottom
 */
.playerInnerBox_gsvb .player_gsvb {
  width : 260px;
  height : 195px;
}

.playerInnerBox_gsvb div.player_gsvb {
  margin : auto;
}

.floatingPlayer_gsvb .playerInnerBox_gsvb div.player_gsvb {
  margin : 0;
}

.playerBox_gsvb div.alldone_gsvb {
  display : inline;
  font-size : 11px;
  cursor : pointer;
}

.playerBox_gsvb div.alldone_gsvb:hover {
  text-decoration : underline;
}


.playerBox_gsvb div.title_gsvb {
  text-align : center;
  font-size : 11px;
  margin-top : 2px;
}

.playerBox_gsvb a.title_gsvb {
  text-decoration : none;
}

.playerBox_gsvb a.title_gsvb:hover {
  text-decoration : underline;
}

/*
 * resultsTable
 * - vertical mode
 * - horizontal mode
 */
.full_gsvb {
  display : block;
}

.empty_gsvb {
  display : none;
}

table.resultTable_gsvb {
  border-collapse : collapse;
}

table.resultTable_gsvb td {
  border : none;
}

div.resultDiv_gsvb {
  border-width : 1px;
  border-style : solid;
  background-color : #000000;
  height : 79px;
  width : 104px;
  text-align : center;
}

div.smallResultDiv_gsvb {
  height : 41px;
  width : 54px;
  text-align : center;
}

div.resultDiv_gsvb img {
  cursor : pointer;
  display : inline;
}

/* Auto Execute List Status Box */
div.statusBox_gsvb {
  padding : 4px;
}

div.statusItem_gsvb {
  display : inline;
  text-decoration : underline;
  color : #0000cc;
  cursor : pointer;
  margin-right : 6px;
  font-weight : bold;
  white-space: nowrap;
}

div.statusItemSelected_gsvb {
  text-decoration : none;
  color : #000000;
}]]></b:skin>

    <b:template-skin>
      <b:variable default='960px' name='content.width' type='length' value='840px'/>
      <b:variable default='0' name='main.column.left.width' type='length' value='100px'/>
      <b:variable default='310px' name='main.column.right.width' type='length' value='210px'/>

      <![CDATA[
      body {
        min-width: $(content.width);
      }

      .content-outer, .content-fauxcolumn-outer, .region-inner {
        min-width: $(content.width);
        max-width: $(content.width);
        _width: $(content.width);
      }

      .main-inner .columns {
        padding-left: $(main.column.left.width);
        padding-right: $(main.column.right.width);
      }

      .main-inner .fauxcolumn-center-outer {
        left: $(main.column.left.width);
        right: $(main.column.right.width);
        /* IE6 does not respect left and right together */
        _width: expression(this.parentNode.offsetWidth -
            parseInt("$(main.column.left.width)") -
            parseInt("$(main.column.right.width)") + 'px');
      }

      .main-inner .fauxcolumn-left-outer {
        width: $(main.column.left.width);
      }

      .main-inner .fauxcolumn-right-outer {
        width: $(main.column.right.width);
      }

      .main-inner .column-left-outer {
        width: $(main.column.left.width);
        right: 100%;
        margin-left: -$(main.column.left.width);
      }

      .main-inner .column-right-outer {
        width: $(main.column.right.width);
        margin-right: -$(main.column.right.width);
      }

      #layout {
        min-width: 0;
      }

      #layout .content-outer {
        min-width: 0;
        width: 800px;
      }

      #layout .region-inner {
        min-width: 0;
        width: auto;
      }
      ]]>
    </b:template-skin>
    <b:include data='blog' name='google-analytics'/>
  </head>

  <body expr:class='&quot;loading&quot; + data:blog.mobileClass'>
  <b:section class='navbar' id='navbar' maxwidgets='1' name='Navbar' showaddelement='no'>
    <b:widget id='Navbar1' locked='true' title='Navbar' type='Navbar'>
      <b:includable id='main'>&lt;script type=&quot;text/javascript&quot;&gt;
    function setAttributeOnload(object, attribute, val) {
      if(window.addEventListener) {
        window.addEventListener(&#39;load&#39;,
          function(){ object[attribute] = val; }, false);
      } else {
        window.attachEvent(&#39;onload&#39;, function(){ object[attribute] = val; });
      }
    }
  &lt;/script&gt;
&lt;div id=&quot;navbar-iframe-container&quot;&gt;&lt;/div&gt;
&lt;script type=&quot;text/javascript&quot; src=&quot;https://apis.google.com/js/plusone.js&quot;&gt;&lt;/script&gt;
&lt;script type=&quot;text/javascript&quot;&gt;
        gapi.load(&quot;gapi.iframes:gapi.iframes.style.bubble&quot;, function() {
          if (gapi.iframes &amp;&amp; gapi.iframes.getContext) {
            gapi.iframes.getContext().openChild({
                url: &#39;https://www.blogger.com/navbar.g?targetBlogID\0754728462919526257125\46blogName\75dimitris+tziavaras\46publishMode\75PUBLISH_MODE_BLOGSPOT\46navbarType\75BLUE\46layoutType\75LAYOUTS\46searchRoot\75//mitros1973.blogspot.com/search\46blogLocale\75el\46v\0752\46homepageUrl\75http://mitros1973.blogspot.com/\46vt\0753120863005291375716&#39;,
                where: document.getElementById(&quot;navbar-iframe-container&quot;),
                id: &quot;navbar-iframe&quot;
            });
          }
        });
      &lt;/script&gt;&lt;script type=&quot;text/javascript&quot;&gt;
(function() {
var script = document.createElement(&#39;script&#39;);
script.type = &#39;text/javascript&#39;;
script.src = &#39;//pagead2.googlesyndication.com/pagead/js/google_top_exp.js&#39;;
var head = document.getElementsByTagName(&#39;head&#39;)[0];
if (head) {
head.appendChild(script);
}})();
&lt;/script&gt;
</b:includable>
    </b:widget>
  </b:section>

  <b:if cond='data:blog.pageType == &quot;index&quot;'>
    <div itemscope='itemscope' itemtype='http://schema.org/Blog' style='display: none;'>
      <meta expr:content='data:blog.title' itemprop='name'/>
      <b:if cond='data:blog.metaDescription'>
        <meta expr:content='data:blog.metaDescription' itemprop='description'/>
      </b:if>
    </div>
  </b:if>

  <div class='body-fauxcolumns'>
    <div class='fauxcolumn-outer body-fauxcolumn-outer'>
    <div class='cap-top'>
      <div class='cap-left'/>
      <div class='cap-right'/>
    </div>
    <div class='fauxborder-left'>
    <div class='fauxborder-right'/>
    <div class='fauxcolumn-inner'>
    </div>
    </div>
    <div class='cap-bottom'>
      <div class='cap-left'/>
      <div class='cap-right'/>
    </div>
    </div>
  </div>

  <div class='content'>
  <div class='content-fauxcolumns'>
    <div class='fauxcolumn-outer content-fauxcolumn-outer'>
    <div class='cap-top'>
      <div class='cap-left'/>
      <div class='cap-right'/>
    </div>
    <div class='fauxborder-left'>
    <div class='fauxborder-right'/>
    <div class='fauxcolumn-inner'>
    </div>
    </div>
    <div class='cap-bottom'>
      <div class='cap-left'/>
      <div class='cap-right'/>
    </div>
    </div>
  </div>

  <div class='content-outer'>
  <div class='content-cap-top cap-top'>
    <div class='cap-left'/>
    <div class='cap-right'/>
  </div>
  <div class='fauxborder-left content-fauxborder-left'>
  <div class='fauxborder-right content-fauxborder-right'/>
  <div class='content-inner'>

    <header>
    <div class='header-outer'>
    <div class='header-cap-top cap-top'>
      <div class='cap-left'/>
      <div class='cap-right'/>
    </div>
    <div class='fauxborder-left header-fauxborder-left'>
    <div class='fauxborder-right header-fauxborder-right'/>
    <div class='region-inner header-inner'>
      <b:section class='header' id='header' maxwidgets='1' name='Header' showaddelement='no'>
        <b:widget id='Header1' locked='true' title='dimitris tziavaras (Κεφαλίδα)' type='Header'>
          <b:includable id='main'>

  <b:if cond='data:useImage'>
    <b:if cond='data:imagePlacement == &quot;BEHIND&quot;'>
      <!--
      Show image as background to text. You can't really calculate the width
      reliably in JS because margins are not taken into account by any of
      clientWidth, offsetWidth or scrollWidth, so we don't force a minimum
      width if the user is using shrink to fit.
      This results in a margin-width's worth of pixels being cropped. If the
      user is not using shrink to fit then we expand the header.
      -->
      <b:if cond='data:mobile'>
        <div id='header-inner'>
          <div class='titlewrapper' style='background: transparent'>
            <h1 class='title' style='background: transparent; border-width: 0px'>
              <b:include name='title'/>
            </h1>
          </div>
          <b:include name='description'/>
        </div>
      <b:else/>
        <div expr:style='&quot;background-image: url(\&quot;&quot; + data:sourceUrl + &quot;\&quot;); &quot;                      + &quot;background-position: &quot;                      + data:backgroundPositionStyleStr + &quot;; &quot;                      + data:widthStyleStr                      + &quot;min-height: &quot; + data:height                      + &quot;_height: &quot; + data:height                      + &quot;background-repeat: no-repeat; &quot;' id='header-inner'>
          <div class='titlewrapper' style='background: transparent'>
            <h1 class='title' style='background: transparent; border-width: 0px'>
              <b:include name='title'/>
            </h1>
          </div>
          <b:include name='description'/>
        </div>
      </b:if>
    <b:else/>
      <!--Show the image only-->
      <div id='header-inner'>
        <a expr:href='data:blog.homepageUrl' style='display: block'>
          <img expr:alt='data:title' expr:height='data:height' expr:id='data:widget.instanceId + &quot;_headerimg&quot;' expr:src='data:sourceUrl' expr:width='data:width' style='display: block'/>
        </a>
        <!--Show the description-->
        <b:if cond='data:imagePlacement == &quot;BEFORE_DESCRIPTION&quot;'>
          <b:include name='description'/>
        </b:if>
      </div>
    </b:if>
  <b:else/>
    <!--No header image -->
    <div id='header-inner'>
      <div class='titlewrapper'>
        <h1 class='title'>
          <b:include name='title'/>
        </h1>
      </div>
      <b:include name='description'/>
    </div>
  </b:if>
</b:includable>
          <b:includable id='description'>
  <div class='descriptionwrapper'>
    <p class='description'><span><data:description/></span></p>
  </div>
</b:includable>
          <b:includable id='title'>
  <b:if cond='data:blog.url == data:blog.homepageUrl'>
    <data:title/>
  <b:else/>
    <a expr:href='data:blog.homepageUrl'><data:title/></a>
  </b:if>
</b:includable>
        </b:widget>
      </b:section>
    </div>
    </div>
    <div class='header-cap-bottom cap-bottom'>
      <div class='cap-left'/>
      <div class='cap-right'/>
    </div>
    </div>
    </header>

    <div class='tabs-outer'>
    <div class='tabs-cap-top cap-top'>
      <div class='cap-left'/>
      <div class='cap-right'/>
    </div>
    <div class='fauxborder-left tabs-fauxborder-left'>
    <div class='fauxborder-right tabs-fauxborder-right'/>
    <div class='region-inner tabs-inner'>
      <b:section class='tabs' id='crosscol' maxwidgets='1' name='Cross-Column' showaddelement='yes'>
        <b:widget id='VideoBar1' locked='false' title='multimitros' type='VideoBar'>
          <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>

  <div class='widget-content'>
    <div expr:id='data:widget.instanceId + &quot;_bar&quot;'>
      <span class='videoBar-status'>Loading...</span>
    </div>
  </div>

  <b:include name='quickedit'/>
</b:includable>
        </b:widget>
        <b:widget id='Image1' locked='false' title='mitrostziavarasgr' type='Image'>
          <b:includable id='main'>
    <b:if cond='data:title != &quot;&quot;'>
      <h2><data:title/></h2>
    </b:if>
    <div class='widget-content'>
      <b:if cond='data:link'>
        <a expr:href='data:link'>
          <img expr:alt='data:title' expr:height='data:height' expr:id='data:widget.instanceId + &quot;_img&quot;' expr:src='data:sourceUrl' expr:width='data:width'/>
        </a>
      <b:else/>
        <img expr:alt='data:title' expr:height='data:height' expr:id='data:widget.instanceId + &quot;_img&quot;' expr:src='data:sourceUrl' expr:width='data:width'/>
      </b:if>
      <br/>
      <b:if cond='data:caption'>
        <span class='caption'><data:caption/></span>
      </b:if>
    </div>
    <b:include name='quickedit'/>
  </b:includable>
        </b:widget>
      </b:section>
      <b:section class='tabs' id='crosscol-overflow' name='Cross-Column 2' showaddelement='no'/>
    </div>
    </div>
    <div class='tabs-cap-bottom cap-bottom'>
      <div class='cap-left'/>
      <div class='cap-right'/>
    </div>
    </div>

    <div class='main-outer'>
    <div class='main-cap-top cap-top'>
      <div class='cap-left'/>
      <div class='cap-right'/>
    </div>

    <div class='fauxborder-left main-fauxborder-left'>
    <div class='fauxborder-right main-fauxborder-right'/>
    <div class='region-inner main-inner'>

      <div class='columns fauxcolumns'>

        <div class='fauxcolumn-outer fauxcolumn-center-outer'>
        <div class='cap-top'>
          <div class='cap-left'/>
          <div class='cap-right'/>
        </div>
        <div class='fauxborder-left'>
        <div class='fauxborder-right'/>
        <div class='fauxcolumn-inner'>
        </div>
        </div>
        <div class='cap-bottom'>
          <div class='cap-left'/>
          <div class='cap-right'/>
        </div>
        </div>

        <div class='fauxcolumn-outer fauxcolumn-left-outer'>
        <div class='cap-top'>
          <div class='cap-left'/>
          <div class='cap-right'/>
        </div>
        <div class='fauxborder-left'>
        <div class='fauxborder-right'/>
        <div class='fauxcolumn-inner'>
        </div>
        </div>
        <div class='cap-bottom'>
          <div class='cap-left'/>
          <div class='cap-right'/>
        </div>
        </div>

        <div class='fauxcolumn-outer fauxcolumn-right-outer'>
        <div class='cap-top'>
          <div class='cap-left'/>
          <div class='cap-right'/>
        </div>
        <div class='fauxborder-left'>
        <div class='fauxborder-right'/>
        <div class='fauxcolumn-inner'>
        </div>
        </div>
        <div class='cap-bottom'>
          <div class='cap-left'/>
          <div class='cap-right'/>
        </div>
        </div>

        <!-- corrects IE6 width calculation -->
        <div class='columns-inner'>

        <div class='column-center-outer'>
        <div class='column-center-inner'>
          <b:section class='main' id='main' name='Main' showaddelement='no'>
            <b:widget id='Blog1' locked='true' title='Αναρτήσεις ιστολογίου' type='Blog'>
              <b:includable id='main' var='top'>
  <b:if cond='!data:mobile'>
    <!-- posts -->
    <div class='blog-posts hfeed'>

      <b:include data='top' name='status-message'/>

      <b:loop values='data:posts' var='post'>
        <b:if cond='data:post.isDateStart and not data:post.isFirstPost'>
          &lt;/div&gt;&lt;/div&gt;
        </b:if>
        <b:if cond='data:post.isDateStart'>
          &lt;div class=&quot;date-outer&quot;&gt;
        </b:if>
        <b:if cond='data:post.dateHeader'>
          <h2 class='date-header'><span><data:post.dateHeader/></span></h2>
        </b:if>
        <b:if cond='data:post.isDateStart'>
          &lt;div class=&quot;date-posts&quot;&gt;
        </b:if>
        <div class='post-outer'>
          <b:include data='post' name='post'/>
          <b:include cond='data:blog.pageType in {&quot;static_page&quot;,&quot;item&quot;}' data='post' name='comment_picker'/>
        </div>

        <!-- Ad -->
        <b:if cond='data:post.includeAd'>
          <div class='inline-ad'>
            <data:adCode/>
          </div>
        </b:if>
      </b:loop>
      <b:if cond='data:numPosts != 0'>
        &lt;/div&gt;&lt;/div&gt;
      </b:if>
    </div>

    <!-- navigation -->
    <b:include name='nextprev'/>

    <!-- feed links -->
    <b:include name='feedLinks'/>

  <b:else/>
    <b:include name='mobile-main'/>
  </b:if>

  <b:if cond='data:top.showPlusOne'>
    <data:top.googlePlusBootstrap/>
  </b:if>

</b:includable>
              <b:includable id='backlinkDeleteIcon' var='backlink'>
  <span expr:class='&quot;item-control &quot; + data:backlink.adminClass'>
    <a expr:href='data:backlink.deleteUrl' expr:title='data:top.deleteBacklinkMsg'>
      <img src='//www.blogger.com/img/icon_delete13.gif'/>
    </a>
  </span>
</b:includable>
              <b:includable id='backlinks' var='post'>
  <a name='links'/><h4><data:post.backlinksLabel/></h4>
  <b:if cond='data:post.numBacklinks != 0'>
    <dl class='comments-block' id='comments-block'>
      <b:loop values='data:post.backlinks' var='backlink'>
        <div class='collapsed-backlink backlink-control'>
          <dt class='comment-title'>
            <span class='backlink-toggle-zippy'>&#160;</span>
            <a expr:href='data:backlink.url' rel='nofollow'><data:backlink.title/></a>
            <b:include data='backlink' name='backlinkDeleteIcon'/>
          </dt>
          <dd class='comment-body collapseable'>
            <data:backlink.snippet/>
          </dd>
          <dd class='comment-footer collapseable'>
            <span class='comment-author'><data:post.authorLabel/> <data:backlink.author/></span>
            <span class='comment-timestamp'><data:post.timestampLabel/> <data:backlink.timestamp/></span>
          </dd>
        </div>
      </b:loop>
    </dl>
  </b:if>
  <p class='comment-footer'>
    <a class='comment-link' expr:href='data:post.createLinkUrl' expr:id='data:widget.instanceId + &quot;_backlinks-create-link&quot;' target='_blank'><data:post.createLinkLabel/></a>
  </p>
</b:includable>
              <b:includable id='comment-form' var='post'>
  <div class='comment-form'>
    <a name='comment-form'/>
    <b:if cond='data:mobile'>
      <h4 id='comment-post-message'>
        <a expr:id='data:widget.instanceId + &quot;_comment-editor-toggle-link&quot;' href='javascript:void(0)'><data:postCommentMsg/></a></h4>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
    <b:else/>
      <h4 id='comment-post-message'><data:postCommentMsg/></h4>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' width='100%'/>
    </b:if>
    <data:post.friendConnectJs/>
    <data:post.cmtfpIframe/>
    <script type='text/javascript'>
      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
    </script>
  </div>
</b:includable>
              <b:includable id='commentDeleteIcon' var='comment'>
  <span expr:class='&quot;item-control &quot; + data:comment.adminClass'>
    <b:if cond='data:showCmtPopup'>
      <div class='goog-toggle-button'>
        <div class='goog-inline-block comment-action-icon'/>
      </div>
    <b:else/>
      <a class='comment-delete' expr:href='data:comment.deleteUrl' expr:title='data:top.deleteCommentMsg'>
        <img src='//www.blogger.com/img/icon_delete13.gif'/>
      </a>
    </b:if>
  </span>
</b:includable>
              <b:includable id='comment_count_picker' var='post'>
  <b:if cond='data:post.commentSource == 1'>
    <span class='cmt_count_iframe_holder' expr:data-count='data:post.numComments' expr:data-onclick='data:post.addCommentOnclick' expr:data-post-url='data:post.url' expr:data-url='data:post.canonicalUrl'>
    </span>
  <b:else/>
    <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'>
      <data:post.commentLabelFull/>:
    </a>
  </b:if>
</b:includable>
              <b:includable id='comment_picker' var='post'>
  <b:if cond='data:post.commentSource == 1'>
    <b:include data='post' name='iframe_comments'/>
  <b:elseif cond='data:post.showThreadedComments'/>
    <b:include data='post' name='threaded_comments'/>
  <b:else/>
    <b:include data='post' name='comments'/>
  </b:if>
</b:includable>
              <b:includable id='comments' var='post'>
  <div class='comments' id='comments'>
    <a name='comments'/>
    <b:if cond='data:post.allowComments'>
      <h4><data:post.commentLabelFull/>:</h4>

      <b:if cond='data:post.commentPagingRequired'>
        <span class='paging-control-container'>
          <b:if cond='data:post.hasOlderLinks'>
            <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'><data:post.oldestLinkText/></a>
              &#160;
            <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'><data:post.olderLinkText/></a>
              &#160;
          </b:if>

          <data:post.commentRangeText/>

          <b:if cond='data:post.hasNewerLinks'>
            &#160;
            <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'><data:post.newerLinkText/></a>
            &#160;
            <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'><data:post.newestLinkText/></a>
          </b:if>
        </span>
      </b:if>

      <div expr:id='data:widget.instanceId + &quot;_comments-block-wrapper&quot;'>
        <dl expr:class='data:post.avatarIndentClass' id='comments-block'>
          <b:loop values='data:post.comments' var='comment'>
            <dt expr:class='&quot;comment-author &quot; + data:comment.authorClass' expr:id='data:comment.anchorName'>
              <b:if cond='data:comment.favicon'>
                <img expr:src='data:comment.favicon' height='16px' style='margin-bottom:-2px;' width='16px'/>
              </b:if>
              <a expr:name='data:comment.anchorName'/>
              <b:if cond='data:blog.enabledCommentProfileImages'>
                <data:comment.authorAvatarImage/>
              </b:if>
              <b:if cond='data:comment.authorUrl'>
                <a expr:href='data:comment.authorUrl' rel='nofollow'><data:comment.author/></a>
              <b:else/>
                <data:comment.author/>
              </b:if>
              <data:commentPostedByMsg/>
            </dt>
            <dd class='comment-body' expr:id='data:widget.instanceId + data:comment.cmtBodyIdPostfix'>
              <b:if cond='data:comment.isDeleted'>
                <span class='deleted-comment'><data:comment.body/></span>
              <b:else/>
                <p>
                  <data:comment.body/>
                </p>
              </b:if>
            </dd>
            <dd class='comment-footer'>
              <span class='comment-timestamp'>
                <a expr:href='data:comment.url' title='comment permalink'>
                  <data:comment.timestamp/>
                </a>
                <b:include data='comment' name='commentDeleteIcon'/>
              </span>
            </dd>
          </b:loop>
        </dl>
      </div>

      <b:if cond='data:post.commentPagingRequired'>
        <span class='paging-control-container'>
          <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'>
            <data:post.oldestLinkText/>
          </a>
          <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'>
            <data:post.olderLinkText/>
          </a>
          &#160;
          <data:post.commentRangeText/>
          &#160;
          <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'>
            <data:post.newerLinkText/>
          </a>
          <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'>
            <data:post.newestLinkText/>
          </a>
        </span>
      </b:if>

      <p class='comment-footer'>
        <b:if cond='data:post.embedCommentForm'>
          <b:if cond='data:post.allowNewComments'>
            <b:include data='post' name='comment-form'/>
          <b:else/>
            <data:post.noNewCommentsText/>
          </b:if>
        <b:elseif cond='data:post.allowComments'/>
          <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><data:postCommentMsg/></a>
        </b:if>
      </p>
    </b:if>
    <b:if cond='data:showCmtPopup'>
      <div id='comment-popup'>
        <iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
        </iframe>
      </div>
    </b:if>

    <div id='backlinks-container'>
    <div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
       <b:include cond='data:post.showBacklinks' data='post' name='backlinks'/>
    </div>
    </div>
  </div>
</b:includable>
              <b:includable id='feedLinks'>
  <b:if cond='data:blog.pageType != &quot;item&quot;'> <!-- Blog feed links -->
    <b:if cond='data:feedLinks'>
      <div class='blog-feeds'>
        <b:include data='feedLinks' name='feedLinksBody'/>
      </div>
    </b:if>

  <b:else/> <!--Post feed links -->
    <div class='post-feeds'>
      <b:loop values='data:posts' var='post'>
        <b:include cond='data:post.allowComments and data:post.feedLinks' data='post.feedLinks' name='feedLinksBody'/>
      </b:loop>
    </div>
  </b:if>
</b:includable>
              <b:includable id='feedLinksBody' var='links'>
  <div class='feed-links'>
  <data:feedLinksMsg/>
  <b:loop values='data:links' var='f'>
     <a class='feed-link' expr:href='data:f.url' expr:type='data:f.mimeType' target='_blank'><data:f.name/> (<data:f.feedType/>)</a>
  </b:loop>
  </div>
</b:includable>
              <b:includable id='iframe_comments' var='post'>

  <b:if cond='data:post.allowIframeComments'>
    <script expr:src='data:post.iframeCommentSrc' type='text/javascript'/>
    <div class='cmt_iframe_holder' expr:data-href='data:post.canonicalUrl' expr:data-viewtype='data:post.viewType'/>

    <b:if cond='data:post.embedCommentForm == &quot;false&quot;'>
      <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><data:postCommentMsg/></a>
    </b:if>
  </b:if>
</b:includable>
              <b:includable id='mobile-index-post' var='post'>
  <div class='mobile-date-outer date-outer'>
    <b:if cond='data:post.dateHeader'>
      <div class='date-header'>
        <span><data:post.dateHeader/></span>
      </div>
    </b:if>

    <div class='mobile-post-outer'>
      <a expr:href='data:post.url'>
        <h3 class='mobile-index-title entry-title' itemprop='name'>
          <data:post.title/>
        </h3>

        <div class='mobile-index-arrow'>&amp;rsaquo;</div>

        <div class='mobile-index-contents'>
          <b:if cond='data:post.thumbnailUrl'>
            <div class='mobile-index-thumbnail'>
              <div class='Image'>
                <img expr:src='data:post.thumbnailUrl'/>
              </div>
            </div>
          </b:if>

          <div class='post-body'>
            <b:if cond='data:post.snippet'><data:post.snippet/></b:if>
          </div>
        </div>

        <div style='clear: both;'/>
      </a>

      <div class='mobile-index-comment'>
        <b:include cond='data:blog.pageType != &quot;static_page&quot;                          and data:post.allowComments                          and data:post.numComments != 0' data='post' name='comment_count_picker'/>
      </div>
    </div>
  </div>
</b:includable>
              <b:includable id='mobile-main' var='top'>
    <!-- posts -->
    <div class='blog-posts hfeed'>

      <b:include data='top' name='status-message'/>

      <b:if cond='data:blog.pageType == &quot;index&quot;'>
        <b:loop values='data:posts' var='post'>
          <b:include data='post' name='mobile-index-post'/>
        </b:loop>
      <b:else/>
        <b:loop values='data:posts' var='post'>
          <b:include data='post' name='mobile-post'/>
        </b:loop>
      </b:if>
    </div>

   <b:include name='mobile-nextprev'/>
</b:includable>
              <b:includable id='mobile-nextprev'>
  <div class='blog-pager' id='blog-pager'>
    <b:if cond='data:newerPageUrl'>
      <div class='mobile-link-button' id='blog-pager-newer-link'>
      <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'>&amp;lsaquo;</a>
      </div>
    </b:if>

    <b:if cond='data:olderPageUrl'>
      <div class='mobile-link-button' id='blog-pager-older-link'>
      <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'>&amp;rsaquo;</a>
      </div>
    </b:if>

    <div class='mobile-link-button' id='blog-pager-home-link'>
    <a class='home-link' expr:href='data:blog.homepageUrl'><data:homeMsg/></a>
    </div>

    <div class='mobile-desktop-link'>
      <a class='home-link' expr:href='data:desktopLinkUrl'><data:desktopLinkMsg/></a>
    </div>

  </div>
  <div class='clear'/>
</b:includable>
              <b:includable id='mobile-post' var='post'>
  <div class='date-outer'>
    <b:if cond='data:post.dateHeader'>
      <h2 class='date-header'><span><data:post.dateHeader/></span></h2>
    </b:if>
    <div class='date-posts'>
      <div class='post-outer'>

        <div class='post hentry uncustomized-post-template' itemscope='itemscope' itemtype='http://schema.org/BlogPosting'>
          <b:if cond='data:post.thumbnailUrl'>
            <meta expr:content='data:post.thumbnailUrl' itemprop='image_url'/>
          </b:if>
          <meta expr:content='data:blog.blogId' itemprop='blogId'/>
          <meta expr:content='data:post.id' itemprop='postId'/>

          <a expr:name='data:post.id'/>
          <b:if cond='data:post.title'>
            <h3 class='post-title entry-title' itemprop='name'>
              <b:if cond='data:post.link'>
                <a expr:href='data:post.link'><data:post.title/></a>
              <b:elseif cond='data:post.url and data:blog.url != data:post.url'/>
                <a expr:href='data:post.url'><data:post.title/></a>
              <b:else/>
                <data:post.title/>
              </b:if>
            </h3>
          </b:if>

          <div class='post-header'>
            <div class='post-header-line-1'/>
          </div>

          <div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id' itemprop='articleBody'>
            <data:post.body/>
            <div style='clear: both;'/> <!-- clear for photos floats -->
          </div>

          <div class='post-footer'>
            <div class='post-footer-line post-footer-line-1'>
              <span class='post-author vcard'>
                <b:if cond='data:top.showAuthor'>
                  <b:if cond='data:post.authorProfileUrl'>
                    <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                      <meta expr:content='data:post.authorProfileUrl' itemprop='url'/>
                      <a expr:href='data:post.authorProfileUrl' rel='author' title='author profile'>
                        <span itemprop='name'><data:post.author/></span>
                      </a>
                    </span>
                  <b:else/>
                    <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                      <span itemprop='name'><data:post.author/></span>
                    </span>
                  </b:if>
                </b:if>
              </span>

              <span class='post-timestamp'>
                <b:if cond='data:top.showTimestamp'>
                  <data:top.timestampLabel/>
                  <b:if cond='data:post.url'>
                    <meta expr:content='data:post.canonicalUrl' itemprop='url'/>
                    <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'><abbr class='published' expr:title='data:post.timestampISO8601' itemprop='datePublished'><data:post.timestamp/></abbr></a>
                  </b:if>
                </b:if>
              </span>

              <span class='post-comment-link'>
                <b:include cond='data:blog.pageType not in {&quot;item&quot;,&quot;static_page&quot;}                                  and data:post.allowComments' data='post' name='comment_count_picker'/>
              </span>
            </div>

            <div class='post-footer-line post-footer-line-2'>
              <b:if cond='data:top.showMobileShare'>
                <div class='mobile-link-button goog-inline-block' id='mobile-share-button'>
                  <a href='javascript:void(0);'><data:shareMsg/></a>
                </div>
              </b:if>
              <b:if cond='data:top.showDummy'>
                <div class='goog-inline-block dummy-container'><data:post.dummyTag/></div>
              </b:if>
            </div>

          </div>
        </div>

        <b:include cond='data:blog.pageType in {&quot;static_page&quot;,&quot;item&quot;}' data='post' name='comment_picker'/>
      </div>
    </div>
  </div>
</b:includable>
              <b:includable id='nextprev'>
  <div class='blog-pager' id='blog-pager'>
    <b:if cond='data:newerPageUrl'>
      <span id='blog-pager-newer-link'>
      <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'><data:newerPageTitle/></a>
      </span>
    </b:if>

    <b:if cond='data:olderPageUrl'>
      <span id='blog-pager-older-link'>
      <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'><data:olderPageTitle/></a>
      </span>
    </b:if>

    <a class='home-link' expr:href='data:blog.homepageUrl'><data:homeMsg/></a>

    <b:if cond='data:mobileLinkUrl'>
      <div class='blog-mobile-link'>
        <a expr:href='data:mobileLinkUrl'><data:mobileLinkMsg/></a>
      </div>
    </b:if>

  </div>
  <div class='clear'/>
</b:includable>
              <b:includable id='post' var='post'>
  <div class='post hentry uncustomized-post-template' itemprop='blogPost' itemscope='itemscope' itemtype='http://schema.org/BlogPosting'>
    <b:if cond='data:post.firstImageUrl'>
      <meta expr:content='data:post.firstImageUrl' itemprop='image_url'/>
    </b:if>
    <meta expr:content='data:blog.blogId' itemprop='blogId'/>
    <meta expr:content='data:post.id' itemprop='postId'/>

    <a expr:name='data:post.id'/>
    <b:if cond='data:post.title'>
      <h3 class='post-title entry-title' itemprop='name'>
      <b:if cond='data:post.link or (data:post.url and data:blog.url != data:post.url)'>
        <a expr:href='data:post.link ? data:post.link : data:post.url'><data:post.title/></a>
      <b:else/>
        <data:post.title/>
      </b:if>
      </h3>
    </b:if>

    <div class='post-header'>
    <div class='post-header-line-1'/>
    </div>

    <!-- Then use the post body as the schema.org description, for good G+/FB snippeting. -->
    <div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id' expr:itemprop='(data:blog.metaDescription ? &quot;&quot; : &quot;description &quot;) + &quot;articleBody&quot;'>
      <data:post.body/>
      <div style='clear: both;'/> <!-- clear for photos floats -->
    </div>

    <b:if cond='data:post.hasJumpLink'>
      <div class='jump-link'>
        <a expr:href='data:post.url + &quot;#more&quot;' expr:title='data:post.title'><data:post.jumpText/></a>
      </div>
    </b:if>

    <div class='post-footer'>
    <div class='post-footer-line post-footer-line-1'>
      <span class='post-author vcard'>
        <b:if cond='data:top.showAuthor'>
          <data:top.authorLabel/>
            <b:if cond='data:post.authorProfileUrl'>
              <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                <meta expr:content='data:post.authorProfileUrl' itemprop='url'/>
                <a class='g-profile' expr:href='data:post.authorProfileUrl' rel='author' title='author profile'>
                  <span itemprop='name'><data:post.author/></span>
                </a>
              </span>
            <b:else/>
              <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                <span itemprop='name'><data:post.author/></span>
              </span>
            </b:if>
        </b:if>
      </span>

      <span class='post-timestamp'>
        <b:if cond='data:top.showTimestamp'>
          <data:top.timestampLabel/>
          <b:if cond='data:post.url'>
            <meta expr:content='data:post.canonicalUrl' itemprop='url'/>
            <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'><abbr class='published' expr:title='data:post.timestampISO8601' itemprop='datePublished'><data:post.timestamp/></abbr></a>
          </b:if>
        </b:if>
      </span>

      <span class='reaction-buttons'>
        <b:if cond='data:top.showReactions'>
          <table border='0' cellpadding='0' cellspacing='0' width='100%'><tr>
            <td class='reactions-label-cell' nowrap='nowrap' valign='top' width='1%'>
              <span class='reactions-label'>
              <data:top.reactionsLabel/></span>&#160;</td>
            <td><iframe allowtransparency='true' class='reactions-iframe' expr:src='data:post.reactionsUrl' frameborder='0' name='reactions' scrolling='no'/></td>
           </tr></table>
        </b:if>
      </span>

      <span class='post-comment-link'>
        <b:include cond='data:blog.pageType not in {&quot;item&quot;,&quot;static_page&quot;}                          and data:post.allowComments' data='post' name='comment_count_picker'/>
      </span>

       <!-- backlinks -->
       <span class='post-backlinks post-comment-link'>
         <b:if cond='data:blog.pageType not in {&quot;item&quot;,&quot;static_page&quot;}                      and data:post.showBacklinks'>
           <a class='comment-link' expr:href='data:post.url + &quot;#links&quot;'><data:top.backlinkLabel/></a>
         </b:if>
       </span>

      <span class='post-icons'>
        <!-- email post links -->
        <b:if cond='data:post.emailPostUrl'>
          <span class='item-action'>
          <a expr:href='data:post.emailPostUrl' expr:title='data:top.emailPostMsg'>
            <img alt='' class='icon-action' height='13' src='//img1.blogblog.com/img/icon18_email.gif' width='18'/>
          </a>
          </span>
        </b:if>

        <!-- quickedit pencil -->
        <b:include data='post' name='postQuickEdit'/>
      </span>

      <!-- share buttons -->
      <div class='post-share-buttons goog-inline-block'>
        <b:include cond='data:post.sharePostUrl' data='post' name='shareButtons'/>
      </div>

      </div>

      <div class='post-footer-line post-footer-line-2'>
      <span class='post-labels'>
        <b:if cond='data:post.labels'>
          <data:postLabelsLabel/>
          <b:loop values='data:post.labels' var='label'>
            <a expr:href='data:label.url' rel='tag'><data:label.name/></a><b:if cond='not data:label.isLast'>,</b:if>
          </b:loop>
        </b:if>
      </span>
      </div>

      <div class='post-footer-line post-footer-line-3'>
      <span class='post-location'>
        <b:if cond='data:top.showLocation'>
          <b:if cond='data:post.location'>
            <data:postLocationLabel/>
            <a expr:href='data:post.location.mapsUrl' target='_blank'><data:post.location.name/></a>
          </b:if>
        </b:if>
      </span>
      </div>
      <b:if cond='data:post.authorAboutMe'>
        <div class='author-profile' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
          <b:if cond='data:post.authorPhoto.url'>
            <img expr:src='data:post.authorPhoto.url' itemprop='image' width='50px'/>
          </b:if>
          <div>
            <a class='g-profile' expr:href='data:post.authorProfileUrl' itemprop='url' rel='author' title='author profile'>
              <span itemprop='name'><data:post.author/></span>
            </a>
          </div>
          <span itemprop='description'><data:post.authorAboutMe/></span>
        </div>
      </b:if>
    </div>
  </div>
</b:includable>
              <b:includable id='postQuickEdit' var='post'>
  <b:if cond='data:post.editUrl'>
    <span expr:class='&quot;item-control &quot; + data:post.adminClass'>
      <a expr:href='data:post.editUrl' expr:title='data:top.editPostMsg'>
        <img alt='' class='icon-action' height='18' src='//img2.blogblog.com/img/icon18_edit_allbkg.gif' width='18'/>
      </a>
    </span>
  </b:if>
</b:includable>
              <b:includable id='shareButtons' var='post'>
  <b:if cond='data:top.showEmailButton'><a class='goog-inline-block share-button sb-email' expr:href='data:post.sharePostUrl + &quot;&amp;target=email&quot;' expr:title='data:top.emailThisMsg' target='_blank'><span class='share-button-link-text'><data:top.emailThisMsg/></span></a></b:if><b:if cond='data:top.showBlogThisButton'><a class='goog-inline-block share-button sb-blog' expr:href='data:post.sharePostUrl + &quot;&amp;target=blog&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=270,width=475\&quot;); return false;&quot;' expr:title='data:top.blogThisMsg' target='_blank'><span class='share-button-link-text'><data:top.blogThisMsg/></span></a></b:if><b:if cond='data:top.showTwitterButton'><a class='goog-inline-block share-button sb-twitter' expr:href='data:post.sharePostUrl + &quot;&amp;target=twitter&quot;' expr:title='data:top.shareToTwitterMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToTwitterMsg/></span></a></b:if><b:if cond='data:top.showFacebookButton'><a class='goog-inline-block share-button sb-facebook' expr:href='data:post.sharePostUrl + &quot;&amp;target=facebook&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=430,width=640\&quot;); return false;&quot;' expr:title='data:top.shareToFacebookMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToFacebookMsg/></span></a></b:if><b:if cond='data:top.showPinterestButton'><a class='goog-inline-block share-button sb-pinterest' expr:href='data:post.sharePostUrl + &quot;&amp;target=pinterest&quot;' expr:title='data:top.shareToPinterestMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToPinterestMsg/></span></a></b:if><b:if cond='data:top.showPlusOne'><div class='goog-inline-block google-plus-share-container'><data:post.googlePlusShareTag/></div></b:if>
</b:includable>
              <b:includable id='status-message'>
  <b:if cond='data:navMessage'>
  <div class='status-msg-wrap'>
    <div class='status-msg-body'>
      <data:navMessage/>
    </div>
    <div class='status-msg-border'>
      <div class='status-msg-bg'>
        <div class='status-msg-hidden'><data:navMessage/></div>
      </div>
    </div>
  </div>
  <div style='clear: both;'/>
  </b:if>
</b:includable>
              <b:includable id='threaded-comment-form' var='post'>
  <div class='comment-form'>
    <a name='comment-form'/>
    <b:if cond='data:mobile'>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
    <b:else/>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' width='100%'/>
    </b:if>
    <data:post.friendConnectJs/>
    <data:post.cmtfpIframe/>
    <script type='text/javascript'>
      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
    </script>
  </div>
</b:includable>
              <b:includable id='threaded_comment_js' var='post'>
  <script async='async' expr:src='data:post.commentSrc' type='text/javascript'/>

  <script type='text/javascript'>
    (function() {
      var items = <data:post.commentJso/>;
      var msgs = <data:post.commentMsgs/>;
      var config = <data:post.commentConfig/>;

// <![CDATA[
      var cursor = null;
      if (items && items.length > 0) {
        cursor = parseInt(items[items.length - 1].timestamp) + 1;
      }

      var bodyFromEntry = function(entry) {
        if (entry.gd$extendedProperty) {
          for (var k in entry.gd$extendedProperty) {
            if (entry.gd$extendedProperty[k].name == 'blogger.contentRemoved') {
              return '<span class="deleted-comment">' + entry.content.$t + '</span>';
            }
          }
        }
        return entry.content.$t;
      }

      var parse = function(data) {
        cursor = null;
        var comments = [];
        if (data && data.feed && data.feed.entry) {
          for (var i = 0, entry; entry = data.feed.entry[i]; i++) {
            var comment = {};
            // comment ID, parsed out of the original id format
            var id = /blog-(\d+).post-(\d+)/.exec(entry.id.$t);
            comment.id = id ? id[2] : null;
            comment.body = bodyFromEntry(entry);
            comment.timestamp = Date.parse(entry.published.$t) + '';
            if (entry.author && entry.author.constructor === Array) {
              var auth = entry.author[0];
              if (auth) {
                comment.author = {
                  name: (auth.name ? auth.name.$t : undefined),
                  profileUrl: (auth.uri ? auth.uri.$t : undefined),
                  avatarUrl: (auth.gd$image ? auth.gd$image.src : undefined)
                };
              }
            }
            if (entry.link) {
              if (entry.link[2]) {
                comment.link = comment.permalink = entry.link[2].href;
              }
              if (entry.link[3]) {
                var pid = /.*comments\/default\/(\d+)\?.*/.exec(entry.link[3].href);
                if (pid && pid[1]) {
                  comment.parentId = pid[1];
                }
              }
            }
            comment.deleteclass = 'item-control blog-admin';
            if (entry.gd$extendedProperty) {
              for (var k in entry.gd$extendedProperty) {
                if (entry.gd$extendedProperty[k].name == 'blogger.itemClass') {
                  comment.deleteclass += ' ' + entry.gd$extendedProperty[k].value;
                } else if (entry.gd$extendedProperty[k].name == 'blogger.displayTime') {
                  comment.displayTime = entry.gd$extendedProperty[k].value;
                }
              }
            }
            comments.push(comment);
          }
        }
        return comments;
      };

      var paginator = function(callback) {
        if (hasMore()) {
          var url = config.feed + '?alt=json&v=2&orderby=published&reverse=false&max-results=50';
          if (cursor) {
            url += '&published-min=' + new Date(cursor).toISOString();
          }
          window.bloggercomments = function(data) {
            var parsed = parse(data);
            cursor = parsed.length < 50 ? null
                : parseInt(parsed[parsed.length - 1].timestamp) + 1
            callback(parsed);
            window.bloggercomments = null;
          }
          url += '&callback=bloggercomments';
          var script = document.createElement('script');
          script.type = 'text/javascript';
          script.src = url;
          document.getElementsByTagName('head')[0].appendChild(script);
        }
      };
      var hasMore = function() {
        return !!cursor;
      };
      var getMeta = function(key, comment) {
        if ('iswriter' == key) {
          var matches = !!comment.author
              && comment.author.name == config.authorName
              && comment.author.profileUrl == config.authorUrl;
          return matches ? 'true' : '';
        } else if ('deletelink' == key) {
          return config.baseUri + '/delete-comment.g?blogID='
               + config.blogId + '&postID=' + comment.id;
        } else if ('deleteclass' == key) {
          return comment.deleteclass;
        }
        return '';
      };

      var replybox = null;
      var replyUrlParts = null;
      var replyParent = undefined;

      var onReply = function(commentId, domId) {
        if (replybox == null) {
          // lazily cache replybox, and adjust to suit this style:
          replybox = document.getElementById('comment-editor');
          if (replybox != null) {
            replybox.height = '250px';
            replybox.style.display = 'block';
            replyUrlParts = replybox.src.split('#');
          }
        }
        if (replybox && (commentId !== replyParent)) {
          replybox.src = '';
          document.getElementById(domId).insertBefore(replybox, null);
          replybox.src = replyUrlParts[0]
              + (commentId ? '&parentID=' + commentId : '')
              + '#' + replyUrlParts[1];
          replyParent = commentId;
        }
      };

      var hash = (window.location.hash || '#').substring(1);
      var startThread, targetComment;
      if (/^comment-form_/.test(hash)) {
        startThread = hash.substring('comment-form_'.length);
      } else if (/^c[0-9]+$/.test(hash)) {
        targetComment = hash.substring(1);
      }

      // Configure commenting API:
      var configJso = {
        'maxDepth': config.maxThreadDepth
      };
      var provider = {
        'id': config.postId,
        'data': items,
        'loadNext': paginator,
        'hasMore': hasMore,
        'getMeta': getMeta,
        'onReply': onReply,
        'rendered': true,
        'initComment': targetComment,
        'initReplyThread': startThread,
        'config': configJso,
        'messages': msgs
      };

      var render = function() {
        if (window.goog && window.goog.comments) {
          var holder = document.getElementById('comment-holder');
          window.goog.comments.render(holder, provider);
        }
      };

      // render now, or queue to render when library loads:
      if (window.goog && window.goog.comments) {
        render();
      } else {
        window.goog = window.goog || {};
        window.goog.comments = window.goog.comments || {};
        window.goog.comments.loadQueue = window.goog.comments.loadQueue || [];
        window.goog.comments.loadQueue.push(render);
      }
    })();
// ]]>
  </script>
</b:includable>
              <b:includable id='threaded_comments' var='post'>
  <div class='comments' id='comments'>
    <a name='comments'/>
    <h4><data:post.commentLabelFull/>:</h4>

    <div class='comments-content'>
      <b:include cond='data:post.embedCommentForm' data='post' name='threaded_comment_js'/>
      <div id='comment-holder'>
         <data:post.commentHtml/>
      </div>
    </div>

    <p class='comment-footer'>
      <b:if cond='data:post.allowNewComments'>
        <b:include data='post' name='threaded-comment-form'/>
      <b:else/>
        <data:post.noNewCommentsText/>
      </b:if>
    </p>

    <b:if cond='data:showCmtPopup'>
      <div id='comment-popup'>
        <iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
        </iframe>
      </div>
    </b:if>

    <div id='backlinks-container'>
    <div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
      <b:include cond='data:post.showBacklinks' data='post' name='backlinks'/>
    </div>
    </div>
  </div>
</b:includable>
            </b:widget>
          </b:section>
        </div>
        </div>

        <div class='column-left-outer'>
        <div class='column-left-inner'>
          <aside>
          <macro:include id='main-column-left-sections' name='sections'>
            <macro:param default='0' name='num' value='1'/>
            <macro:param default='sidebar-left' name='idPrefix'/>
            <macro:param default='sidebar' name='class'/>
            <macro:param default='true' name='includeBottom'/>
          </macro:include>
          </aside>
        </div>
        </div>

        <div class='column-right-outer'>
        <div class='column-right-inner'>
          <aside>
          <macro:include id='main-column-right-sections' name='sections'>
            <macro:param default='2' name='num' value='2'/>
            <macro:param default='sidebar-right' name='idPrefix'/>
            <macro:param default='sidebar' name='class'/>
            <macro:param default='true' name='includeBottom'/>
          </macro:include>
          </aside>
        </div>
        </div>

        </div>

        <div style='clear: both'/>
      <!-- columns -->
      </div>

    <!-- main -->
    </div>
    </div>
    <div class='main-cap-bottom cap-bottom'>
      <div class='cap-left'/>
      <div class='cap-right'/>
    </div>
    </div>

    <footer>
    <div class='footer-outer'>
    <div class='footer-cap-top cap-top'>
      <div class='cap-left'/>
      <div class='cap-right'/>
    </div>
    <div class='fauxborder-left footer-fauxborder-left'>
    <div class='fauxborder-right footer-fauxborder-right'/>
    <div class='region-inner footer-inner'>
      <macro:include id='footer-sections' name='sections'>
        <macro:param default='2' name='num'/>
        <macro:param default='footer' name='idPrefix'/>
        <macro:param default='foot' name='class'/>
        <macro:param default='false' name='includeBottom'/>
      </macro:include>
      <!-- outside of the include in order to lock Attribution widget -->
      <b:section class='foot' id='footer-3' name='Footer' showaddelement='no'>
        <b:widget id='Attribution1' locked='true' title='' type='Attribution'>
          <b:includable id='main'>
    <b:if cond='data:feedbackSurveyLink'>
      <div class='mobile-survey-link' style='text-align: center;'>
        <data:feedbackSurveyLink/>
      </div>
    </b:if>

    <div class='widget-content' style='text-align: center;'>
      <b:if cond='data:attribution != &quot;&quot;'>
       <data:attribution/>
      </b:if>
    </div>

    <b:include name='quickedit'/>
  </b:includable>
        </b:widget>
      </b:section>
    </div>
    </div>
    <div class='footer-cap-bottom cap-bottom'>
      <div class='cap-left'/>
      <div class='cap-right'/>
    </div>
    </div>
    </footer>

  <!-- content -->
  </div>
  </div>
  <div class='content-cap-bottom cap-bottom'>
    <div class='cap-left'/>
    <div class='cap-right'/>
  </div>
  </div>
  </div>

  <script type='text/javascript'>
    window.setTimeout(function() {
        document.body.className = document.body.className.replace(&#39;loading&#39;, &#39;&#39;);
      }, 10);
  </script>
</body>

<macro:includable id='sections' var='col'>
  <macro:if cond='data:col.num == 0'>
  <macro:else/>
    <b:section mexpr:class='data:col.class' mexpr:id='data:col.idPrefix + &quot;-1&quot;' preferred='yes' showaddelement='yes'/>

    <macro:if cond='data:col.num &gt;= 2'>
      <table border='0' cellpadding='0' cellspacing='0' mexpr:class='&quot;section-columns columns-&quot; + data:col.num'>
      <tbody>
      <tr>
        <td class='first columns-cell'>
          <b:section mexpr:class='data:col.class' mexpr:id='data:col.idPrefix + &quot;-2-1&quot;'/>
        </td>

        <td class='columns-cell'>
          <b:section mexpr:class='data:col.class' mexpr:id='data:col.idPrefix + &quot;-2-2&quot;'/>
        </td>

        <macro:if cond='data:col.num &gt;= 3'>
          <td class='columns-cell'>
            <b:section mexpr:class='data:col.class' mexpr:id='data:col.idPrefix + &quot;-2-3&quot;'/>
          </td>
        </macro:if>

        <macro:if cond='data:col.num &gt;= 4'>
          <td class='columns-cell'>
            <b:section mexpr:class='data:col.class' mexpr:id='data:col.idPrefix + &quot;-2-4&quot;'/>
          </td>
        </macro:if>
      </tr>
      </tbody>
      </table>

      <macro:if cond='data:col.includeBottom'>
        <b:section mexpr:class='data:col.class' mexpr:id='data:col.idPrefix + &quot;-3&quot;' showaddelement='no'/>
      </macro:if>
    </macro:if>
  </macro:if>
</macro:includable>

<b:section-contents id='sidebar-left-1'/><b:section-contents id='sidebar-right-1'>
  <b:widget id='PlusBadge1' locked='false' title='Google+ Badge' type='PlusBadge'>
    <b:includable id='main'>

  <script type='text/javascript'>
  window.___gcfg = {
    lang: &#39;<data:language/>&#39;
  };
  </script>

  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div data-rel='author' expr:class='&quot;g-&quot; + data:badgeType' expr:data-href='data:profileUrl' expr:data-layout='data:layout' expr:data-showcoverphoto='data:showCoverPhoto' expr:data-showtagline='data:showTagline' expr:data-theme='data:theme' expr:data-width='data:width'>
  </div>
</b:includable>
  </b:widget>
  <b:widget id='PlusOne1' locked='false' title='+1 Button' type='PlusOne'>
    <b:includable id='main'>

  <div class='widget-content'>
    <g:plusone expr:annotation='data:annotation' expr:href='data:blog.canonicalHomepageUrl' expr:size='data:size' source='blogger:blog:plusone' width='250'/>

    <script type='text/javascript'>
      window.___gcfg = {&quot;lang&quot;: &quot;<data:language/>&quot;};
    </script>
  </div>

</b:includable>
  </b:widget>
  <b:widget id='BlogArchive1' locked='false' title='Αρχειοθήκη ιστολογίου' type='BlogArchive'>
    <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'>
    <h2><data:title/></h2>
  </b:if>
  <div class='widget-content'>
  <div id='ArchiveList'>
  <div expr:id='data:widget.instanceId + &quot;_ArchiveList&quot;'>
    <b:include cond='data:style == &quot;HIERARCHY&quot;' data='data' name='interval'/>
    <b:include cond='data:style == &quot;FLAT&quot;' data='data' name='flat'/>
    <b:include cond='data:style == &quot;MENU&quot;' data='data' name='menu'/>
  </div>
  </div>
  <b:include name='quickedit'/>
  </div>
</b:includable>
    <b:includable id='flat' var='data'>
  <ul class='flat'>
    <b:loop values='data:data' var='i'>
      <li class='archivedate'>
        <a expr:href='data:i.url'><data:i.name/></a> (<data:i.post-count/>)
      </li>
    </b:loop>
  </ul>
</b:includable>
    <b:includable id='interval' var='intervalData'>
  <b:loop values='data:intervalData' var='interval'>
    <ul class='hierarchy'>
      <li expr:class='&quot;archivedate &quot; + data:interval.expclass'>
        <b:include cond='data:interval.toggleId' data='interval' name='toggle'/>
        <a class='post-count-link' expr:href='data:interval.url'>
          <data:interval.name/>
        </a>
        <span class='post-count' dir='ltr'>(<data:interval.post-count/>)</span>
        <b:include cond='data:interval.data' data='interval.data' name='interval'/>
        <b:include cond='data:interval.posts' data='interval.posts' name='posts'/>
      </li>
    </ul>
  </b:loop>
</b:includable>
    <b:includable id='menu' var='data'>
  <select expr:id='data:widget.instanceId + &quot;_ArchiveMenu&quot;'>
    <option value=''><data:title/></option>
    <b:loop values='data:data' var='i'>
      <option expr:value='data:i.url'><data:i.name/> (<data:i.post-count/>)</option>
    </b:loop>
  </select>
</b:includable>
    <b:includable id='posts' var='posts'>
  <ul class='posts'>
    <b:loop values='data:posts' var='post'>
      <li><a expr:href='data:post.url'><data:post.title/></a></li>
    </b:loop>
  </ul>
</b:includable>
    <b:includable id='toggle' var='interval'>
  <a class='toggle' href='javascript:void(0)'>
    <span expr:class='&quot;zippy&quot; + (data:interval.expclass == &quot;expanded&quot; ? &quot; toggle-open&quot; : &quot;&quot;)'>
      <b:if cond='data:interval.expclass == &quot;expanded&quot;'>
        &#9660;&#160;
      <b:elseif cond='data:blog.languageDirection == &quot;rtl&quot;'/>
        &#9668;&#160;
      <b:else/>
        &#9658;&#160;
      </b:if>
    </span>
  </a>
</b:includable>
  </b:widget>
</b:section-contents><b:section-contents id='sidebar-right-2-1'>
  <b:widget id='CustomSearch1' locked='false' title='https://cse.google.gr:443/cse/publicurl?cx=015705803977090371190:fjdqrltw2bs' type='CustomSearch'>
    <b:includable id='main'>
    <!-- only display title if it's non-empty -->
    <b:if cond='data:title != &quot;&quot;'>
      <h2 class='title'><data:title/></h2>
    </b:if>

    <div class='widget-content'>
      <div expr:id='data:widget.instanceId + &quot;_form&quot;'>
        <span class='cse-status'><data:loadingMsg/></span>
      </div>
    </div>

    <!-- override gsearch.css -->
    <style type='text/css'>
      #uds-searchControl .gs-result .gs-title,
      #uds-searchControl .gs-result .gs-title *,
      #uds-searchControl .gsc-results .gsc-trailing-more-results,
      #uds-searchControl .gsc-results .gsc-trailing-more-results * {
        color:<data:linkColor/>;
      }

      #uds-searchControl .gs-result .gs-title a:visited,
      #uds-searchControl .gs-result .gs-title a:visited * {
        color:<data:visitedLinkColor/>;
      }

      #uds-searchControl .gs-relativePublishedDate,
      #uds-searchControl .gs-publishedDate {
        color: <data:dateColor/>;
      }

      #uds-searchControl .gs-result a.gs-visibleUrl,
      #uds-searchControl .gs-result .gs-visibleUrl {
        color: <data:urlColor/>;
      }

      #uds-searchControl .gsc-results {
        border-color: <data:borderColor/>;
        background-color: <data:backgroundColor/>;
      }

      #uds-searchControl .gsc-tabhActive {
        border-color: <data:borderColor/>;
        border-top-color: <data:activeBorderColor/>;
        background-color: <data:backgroundColor/>;
        color: <data:textColor/>;
      }

      #uds-searchControl .gsc-tabhInactive {
        border-color: <data:borderColor/>;
        background-color: transparent;
        color: <data:linkColor/>;
      }

      #uds-searchClearResults {
        border-color: <data:borderColor/>;
      }

      #uds-searchClearResults:hover {
        border-color: <data:activeBorderColor/>;
      }

      #uds-searchControl .gsc-cursor-page {
        color: <data:linkColor/>;
      }

      #uds-searchControl .gsc-cursor-current-page {
        color: <data:textColor/>;
      }
    </style>

    <b:include name='quickedit'/>
  </b:includable>
  </b:widget>
  <b:widget id='Profile1' locked='false' title='dimitris tziavaras' type='Profile'>
    <b:includable id='main'>
    <b:if cond='data:title != &quot;&quot;'>
      <h2><data:title/></h2>
    </b:if>
    <div class='widget-content'>
    <b:if cond='data:team'> <!-- team blog profile -->
      <ul>
        <b:loop values='data:authors' var='i'>
          <li><a class='profile-name-link g-profile' expr:href='data:i.userUrl' expr:style='&quot;background-image: url(&quot; + data:i.profileLogo + &quot;);&quot;'><data:i.display-name/></a></li>
        </b:loop>
      </ul>

    <b:else/> <!-- normal blog profile -->

      <b:if cond='data:photo.url != &quot;&quot;'>
        <a expr:href='data:userUrl'><img class='profile-img' expr:alt='data:photo.alt' expr:height='data:photo.height' expr:src='data:photo.url' expr:width='data:photo.width'/></a>
      </b:if>

      <dl class='profile-datablock'>
        <dt class='profile-data'>
          <a class='profile-name-link g-profile' expr:href='data:userUrl' expr:style='&quot;background-image: url(&quot; + data:profileLogo + &quot;);&quot;' rel='author'>
            <data:displayname/>
          </a>
          <b:if cond='data:hasgoogleprofile'>
            <br/>
            <div class='g-follow' data-annotation='bubble' data-height='20' expr:data-href='data:userUrl'/>
          </b:if>
        </dt>

        <b:if cond='data:showlocation'>
          <dd class='profile-data'><data:location/></dd>
        </b:if>

        <b:if cond='data:aboutme != &quot;&quot;'><dd class='profile-textblock'><data:aboutme/></dd></b:if>
      </dl>
      <a class='profile-link' expr:href='data:userUrl' rel='author'><data:viewProfileMsg/></a>
    </b:if>

     <b:include name='quickedit'/>
    </div>
  </b:includable>
  </b:widget>
</b:section-contents><b:section-contents id='sidebar-right-2-2'/><b:section-contents id='sidebar-right-3'/><b:section-contents id='footer-1'/><b:section-contents id='footer-2-1'/><b:section-contents id='footer-2-2'/></html>
