<a id="readme-top"></a>

<div align="center">

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

</div>


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">DisplayDuck Simple Weather Widget</h3>

  <p align="center">
    Weather icons by <a href="https://github.com/basmilius">basmilius</a> from <a href="https://github.com/basmilius/weather-icons">basmilius/weather-icons</a>
  </p>
</div>

---

## About
This widget displays the current weather conditions based on passed lat/long.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

Currently the <a href="https://docs.discord.com/developers/topics/rpc">Discord RPC API</a> states that the RPC API is in private beta, this means that you need your **own** <a href="https://discord.com/developers/applications">Discord Application ID</a> in order to use this widget.

### Setting up a Discord Application

1. Go to <a href="https://discord.com/developers/applications">applications</a>
2. Make up an application name *(eg DisplayDuck Widget)*
3. Go to `Oauth2` and setup `http://localhost` as Redirect URL under `Redirects`
4. Go (back) to `General Information` and copy the `Application ID`
5. Use this `Application ID` in the `Application Client ID` field in the widget config


<p align="right">(<a href="#readme-top">back to top</a>)</p>

---

## Configurable options
| Setting | Description |Type | Configurable Values | Default Value
|---|---|---|---|---|
| Latitude | Latitude of the location | `number` | any `number` | 0
| Longitude | Longitude of the location | `number` | any `number` | 0
| Units | Wether to show Metric or Imperial units | `dropdown` | `Metric`<br />`Imperial` | `Metric`
| Interval | The interval (in minutes) to refresh data | `number` | any `number` | 10
| Show Wind Speed | If the widget should show Windspeed | `boolean` | `true`<br />`false` | `false`
| Show Precipation | If the widget should show Precipaction % | `boolean` | `true`<br />`false` | `false`
| Show City Name | If the widget should show the city name | `boolean` | `true`<br />`false` | `false`

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Contributors:

<a href="https://github.com/brood-works/displayduck-widget-simpleweather/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=brood-works/displayduck-widget-simpleweather" />
</a>


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/brood-works/displayduck-widget-simpleweather.svg
[contributors-url]: https://github.com/brood-works/displayduck-widget-simpleweather/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/brood-works/displayduck-widget-simpleweather
[forks-url]: https://github.com/brood-works/displayduck-widget-simpleweather/network/members
[stars-shield]: https://img.shields.io/github/stars/brood-works/displayduck-widget-simpleweather
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/brood-works/displayduck-widget-simpleweather
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues