# css-mediaquery

### Media Queries

this are what make modern responsive design possible.

## what is media queries?

     a media query is a specific feature in css that lets you apply styles based on media type.

# syntax of media query

    - @media screen (min-width-320px) and (max-width:760px)

            - @media- specifies media query declaration.

    - media type--> it specifies what type of media are we trying to target.
         - screen---> it allows to use values here, as this makes sense in many of the media types we are trying to match our devices. ( MATCHES DEVICES WITH SCREENS)
         - all ---> Matches all devices.
         - print ---> it matches documents that are viewed in a print preview or any media that breaks the content up into pages intent to print.

     - Media Features - it defines what features we are trying to match to
            - Desktop-- > (min-width:1024px);
            - Tablet ---> (min-width:768px)  and (max-width:1023px);
            - smartphone-- > (min-width:340px) and (max-width:767px);
