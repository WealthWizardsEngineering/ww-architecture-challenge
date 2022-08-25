# ww-architecture-challenge

## Motivation

We want to write a web application and sell it to multiple customers.

The application comprises an HTML/Javascript frontend communicating with calculation logic on the server side, and will be used both on mobile and desktop browsers.

We have a strong preference for cloud hosting.

## Business Requirements

While the core functionality of the application will be the same for everyone, it needs to be deployable so that it’s customised to each customer’s needs:

* features may be switched on or off
* customers may supply their own text content and images
* constants and calculations strategies will vary from one customer to the next
* the visual appearance - colour scheme, typography, and potentially other UI-related aspects of the app will vary from one customer to the next

A few large customers will demand extensive and detailed customisation.

We would also like to sell the app to potentially hundreds of small customers, to whom we would offer more limited customisation options. There is likely to be one or more medium-sized customer tiers in-between.

We want to start selling early, so we want early value with a path towards fleshing it out.

## How would you architect such an app?

Please prepare to present your solution over a Zoom call using any medium you feel comfortable with, your presentation should last up to 15 minutes and you should expect to answer questions about your proposed solution.

Things to consider:

* code repository layout
* granularity of build artefacts
* build and deployment process
* version management both of code and configuration
* division of ownership (e.g. code vs configuration vs content)
* regulatory sign-off
