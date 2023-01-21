# weatherWidget
This is a page wrapping one of the windy widgets https://windy.app/blog/weather-widget-iphone-website.html <br />
With this page you can load the widget in a secure iframe instead of injecting it into your own dom.

# params
support of following query parameters

| query param | info  | example  |
| ------- | --- | --- |
| lat | latitude information of the location | 51.1054 |
| lng | longitude information of the location | 2.6502 |
| title | Optional information line to show on top of the page | My title |
| addressl1 | Optional first line of address matching lat and lng params | sesamstraat 1 |
| addressl2 | Optional second line of address matching lat and lng params | 8888 TER VELDE |

example <br />
https://brianmares.github.io/weatherWidget?lat=51.1054&lng=2.6502&title=car-516-666&addressl1=sesamstraat%201&addressl2=8888%20ter%20velde
