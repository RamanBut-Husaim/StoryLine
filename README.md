# StoryLine

Welcome to **StoryLine** framework used to create integration tests!

This [wiki](https://github.com/DiamondDragon/StoryLine/wiki) is the main source of documentation for developers working with (or contributing to) the **StorLine** project.

**StoryLine** project defines base classes and interfaces used to construct test scenarios. It's very unlikely that this library can be used alone. It's expected that library is used with conjunction with one of the following libraries which provides specific actions and expectations:

* [StoryLine.Rest](https://github.com/DiamondDragon/StoryLine.Rest) is a set of REST-specific actions which simplify testing of HTTP-based services.
* [StoryLine.Wiremock](https://github.com/DiamondDragon/StoryLine.Wiremock) is a set of [WireMock](http://wiremock.org/)-specific actions and expectations. This library can serve as WireMock client which is compatible with **StoryLine** framework.
* [StoryLine.Utils](https://github.com/DiamondDragon/StoryLine.Utils) is a set of helper actions and expectations which are not specific to any area.

