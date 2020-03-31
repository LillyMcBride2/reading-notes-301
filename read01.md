#Responsive Web Design--

The practice of building a website suitable for accessing on devices with different screen sizes. Designs dynamically adapt to different browser and device viewports, changing layout and content along the way. Design should always be done in a mobile first mindset.

#Flexible Grid Layout

Flexible layouts do not advocate the use of fixed measurement units, such as pixels or inches. Using the flexible grid formula we can take all of the fixed units of length and turn them into relative units. Taking the flexible layout concept, and formula, and reapplying it to all parts of a grid will create a completely dynamic website, scaling to every viewport size. 

#Media Queries

Generally speaking it is recommend to use the @media rule inside of an existing style sheet to avoid any additional HTTP requests. The media query expression that follows the media type may include different media features and values, which then allocate to be true or false. When a media feature and value allocate to true, the styles are applied. If the media feature and value allocate to false the styles are ignored.

#Logical Operators in Media Queries

Using the and logical operator within a media query allows an extra condition to be added, making sure that a browser or devices does both a, b, c, and so forth. Multiple individual media queries can be comma separated, acting as an unspoken or operator.

#Height and Width Meadia features

One of the most common media features revolves around determining a height or width for a device or browser viewport. The height and width may be found by using the height and width media features. Each of these media features may then also be prefixed with the min or max qualifiers, building a feature such as min-width or max-width.

#Orientation Media Feature

The orientation media feature determines if a device is in the landscape or portrait orientation. The landscape mode is triggered when the display is wider than taller, and the portrait mode is triggered when the display is taller than wider. This media feature plays a large part with mobile devices
